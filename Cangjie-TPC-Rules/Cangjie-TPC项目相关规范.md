# Cangjie-TPC 项目相关规范

## Cangjie-TPC 项目命名指导

### Cangjie-TPC 项目命名规范

- 只能由小写字母、数字、_和-组成
- 总长度小于等于128个字符
- 必须以字母开头
- 不能是仓颉关键字

### Cangjie-TPC 项目命名建议

当您选择三方库名称时，请满足命名规范，同时也请选择名称是：

- 独特的
- 符合描述性的
- 符合正常逻辑的，例如：请不要给您的三方库起一个冒犯性的名字，也不要使用别人的商标名
- 尚未归他人所有
- 与另一个三方库名称的拼写方式不同
- 不会混淆其他作者身份

## Cangjie-TPC 项目版本命名指导

### 版本号命名规则

- 正式版： 主版本.次版本.修订版本
- 候选发布版本：主版本.次版本.修订版本-rc

### 版本号变更规则

- 主版本号：全盘重构时增加；重大功能或方向改变时增加；大范围不兼容时增加。
- 次版本号：增加新的业务功能，并且向下兼容的更新时增加。
- 修订版本号：当软件修复了BUG或是做了一些小的变动时增加。
- 主版本号变更时，次版本号与修订版本号重置为0.
- 次版本号变更时，修订版本号重置为0。
- 项目毕业前版本号小于1.0.0。

## Cangjie-TPC 项目配置指导

### 必须有 README 文件

模板参考：[README](https://gitcode.com/Cangjie-TPC/TPC-Resource/blob/main/project-template/README.md)

标题：
+ release：项目主线分支版本号（例如：v0.0.1）。
+ cjc：项目主线分支支持的仓颉编程语言版本（例如：0.53.4）
+ cjcov：项目主线分支单元测试覆盖率（推荐使用cjcov测试覆盖率，参考仓颉语言工具使用指南）
+ state：项目是否经过社区质量标准验收，如果没有请填写孵化，如果已经通过请填写毕业
+ domain：如果项目适用于鸿蒙原生应用开发，请填写HOS；项目适用于云原生应用开发，请填写Cloud；项目适用于AI应用开发，请填写AI，其他领域按照情况填写英文缩写

内容：
+ 介绍：必须包括项目特性以及项目计划描述，并按照描述控制项目演进方向
+ 架构：必须包括项目结构以及接口说明
+ 使用说明：必须包括编译构建以及功能示例，编译构建流程必须确保流程无误以及可操作性；功能示例必须可编译运行
+ 参与贡献：必须明确维护单位/个人，声明LICSENSE，明确 committer

### 必须有 LICSENSE 文件

模板参考：[LICSENSE](https://gitcode.com/Cangjie-TPC/TPC-Resource/blob/main/project-template/LICENSE)

推荐使用 Apache License Version 2.0，其他LICSENSE参考[Cangjie 社区项目代码许可证规则与特殊许可证评审指导](https://gitcode.com/Cangjie-TPC/TPC-Resource/blob/main/Cangjie-Rules/Cangjie%20%E7%A4%BE%E5%8C%BA%E9%A1%B9%E7%9B%AE%E4%BB%A3%E7%A0%81%E8%AE%B8%E5%8F%AF%E8%A7%84%E5%88%99%E4%B8%8E%E7%89%B9%E6%AE%8A%E8%AE%B8%E5%8F%AF%E8%AF%81%E6%8C%87%E5%AF%BC.md)

### 必须有 CHANGELOG 文件

模板参考：[CHANGELOG](https://gitcode.com/Cangjie-TPC/TPC-Resource/blob/main/project-template/CHANGELOG.md)

[版本号]：请优先显示最新版本CHANGELOG

Feature：版本新增特性

Bugfix：版本修改缺陷

Remove：版本移除特性及接口