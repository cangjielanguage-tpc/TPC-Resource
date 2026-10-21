# 如何为 Cangjie-TPC 贡献代码

## 1 熟知 Cangjie 社区行为守则

Cangjie-TPC 是 Cangjie 社区用于汇集基于仓颉编程语言开发的开源三方库的主干仓，帮助开发者方便、快捷、高质量构建仓颉程序，完全依赖于社区提供友好地开发和协作环境。在参与社区贡献之前，请先阅读并遵守[Cangjie-TPC社区行为守则](./Cangjie-Rules/code_of_conduct_zn.md)（[Cangjie Community Code of Conduct](./Cangjie-Rules/code_of_conduct_en.md)）。

## 2 熟知 Cangjie 社区治理规则

[Cangjie-TPC 开源合规规范](./Cangjie-TPC-Rules/Cangjie-TPC%20开源合规规范.md)

[Cangjie-TPC 项目相关规范](./Cangjie-TPC-Rules/Cangjie-TPC%20项目相关规范.md)

## 3 根据您的目的选择贡献流程

### 3.1 贡献仓库

#### STEP 1 提交创建项目申请 issue

请点击链接，[选择项目创建申请 issue 模版](https://gitcode.com/Cangjie-TPC/TPC-Resource/issues/create/choose)，按照模版，详尽填写信息（如果创建项目申请 issue 不够详细，社区不会通过该申请），并提交 issue

#### STEP 2 签署 CLA 协议

请点击链接，[签署 CLA ](https://clasign.cangjie-lang.cn/sign/Z2l0Y29kZSUyRkNhbmdqaWU=)

**注意：**

+ CCLA 为公司/组织/单位的贡献协议

+ ICLA 为个人贡献协议

#### STEP 3 提交创建项目申请 email

请点击下方链接，[下载项目创建申请 email 模版](https://gitcode.com/Cangjie-TPC/TPC-Resource/blob/main/%E3%80%90Cangjie-TPC%E7%A4%BE%E5%8C%BA%E3%80%91%E9%A1%B9%E7%9B%AE%E5%88%9B%E5%BB%BA%E7%94%B3%E8%AF%B7.docx)，按照模版，详尽填写信息（如果创建项目申请 email 不够详细，社区不会通过该申请），并向 `cangjie@huawei.com` 发送该邮件

注意：邮件附件推荐包括项目初始化内容（包含README，LICENSE，CHANGELOG，cjpm.toml），模板请参考[项目初始化模版](https://gitcode.com/Cangjie-TPC/TPC-Resource/blob/main/template.zip)，请以`项目名称.zip`方式附加至邮件

#### STEP 4 Cangjie-TPC 组织评审

[TPC Team](https://gitcode.com/Cangjie/community/blob/main/team/team_tpc/team_tpc_cn.md) 将在**5个工作日**内进行评审，评审结果将以邮件形式返回


#### STEP 5 创建项目

评审通过后，[TPC Team](https://gitcode.com/Cangjie/community/blob/main/team/team_tpc/team_tpc_cn.md) 将在**5个工作日**内创建项目，并邀请您加入项目

+ **注意：** 若项目创建后一个月内仍为空仓，将按废弃处理并删除仓库。如仍有建仓需求，需重新提交申请。建议在项目创建后尽快完成首次代码提交。


### 3.2 贡献 PR

#### STEP 1 将 issue 分配给自己

请针对具体缺陷/需求提交 issue，并将该 issue 分配给自己

#### STEP 2 编写代码与测试用例

针对解决该 issue 编写代码以及测试用例（如果您的 issue 没有测试用例可能不会被接纳）

#### STEP 3 提交 PR 并签署 CLA

提交 PR 并签署 CLA，PR 模板如下：

```
标题：
[项目名称][需求/缺陷]：PR 标题

正文：
[issue number]：
[impact files]: 

（请描述您的pr所做的工作）
```

#### STEP 4 由 Committer 审核并合入代码

由Committer对PR进行审核，通过审核后即可合入代码。
