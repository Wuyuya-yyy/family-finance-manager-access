# 管家婆项目协作权限申请

本仓库是私有课程项目 [`family-finance-manager`](https://github.com/Wuyuya-yyy/family-finance-manager) 的公开访问申请入口，**不包含项目源码**。

## 申请入口

[提交协作权限申请](https://github.com/Wuyuya-yyy/family-finance-manager-access/issues/new?template=access-request.yml)

1. 使用你准备参与项目的 GitHub 账号登录。
2. 填写项目角色和计划承担的任务；不要公开学号、手机号、邮箱或其他敏感信息。
3. 提交申请后，由仓库所有者线下核验项目组身份。
4. 审核通过后，你会收到 GitHub 协作者邀请；接受邀请后即可读写私有主仓库。

## 获得权限后

```bash
git clone git@github.com:Wuyuya-yyy/family-finance-manager.git
cd family-finance-manager
git checkout -b feature/<topic>
git push -u origin feature/<topic>
```

请通过 Pull Request 合并到 `main`，并确保 CI 通过。

## 安全约定

- 仅向已核验的项目组成员授予权限。
- 不要提交密码、令牌、私钥、真实家庭财务数据或 `.env` 文件。
- 不要在公开申请中填写学号、手机号、邮箱等个人敏感信息。
- 本仓库仅处理访问申请，不接受项目代码提交。
