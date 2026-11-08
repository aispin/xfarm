# xfarm · 溪田花境 PWA（发布仓库）

**这个仓库只放构建产物，源码不在这里。**

| 项 | 位置 |
|---|---|
| 源码（私有） | https://github.com/aispin/ai-acts |
| 线上地址 | https://aispin.github.io/xfarm/ |
| 产物分支 | `gh-pages`（由 CI 覆盖式写入，手改会被下次发布冲掉） |

## 怎么发布

在 `aispin/ai-acts` 上推 `main` 且改动涉及 `apps/web/**`，CI 会构建 `apps/web/dist` 并用部署密钥推到这里；也可在 ai-acts 的 Actions 里手动 `workflow_dispatch`。

细节见 ai-acts 的 `apps/web/docs/pwa.md`。
