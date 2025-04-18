# 2025-04-18
## Projects
- AnythingLLM
- MCP w/AnythingLLM

## Resources
- [Use MCP in AnythingLLM](https://docs.anythingllm.com/mcp-compatibility/overview)
- [Write to host](https://docs.anythingllm.com/mcp-compatibility/docker)
  - Configure PVC for persistence
- [Grafana MCP](https://github.com/grafana/mcp-grafana)

# 2025-04-09
## Projects
- Update website
  - Update submodules with the following commands:
    - `git submodule update --remote`
    - `git add <submodule-path>`
    - `git commit -m "chore: updated submodule"`
    - `git push`
- K8s homelab

## Resources

# 2025-04-03
## Projects
- Revamp website

## Resources

# 2025-04-02
## Projects
- Revamp website

## Resources
- [Install APK](https://www.baeldung.com/linux/apk-alpine-install)
- [Hugo static website example](https://learn.microsoft.com/en-us/azure/static-web-apps/publish-hugo)
- [Git Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
  - How was I not aware of Git submodules before?!
  - `git submodule add <url>`
  - `git submodule update --init --recursive`
- [Cloudflare Deploy MkDocs](https://developers.cloudflare.com/pages/framework-guides/deploy-an-mkdocs-site/)

# 2025-04-01
## Projects
- [x] [GHA for KubeCraft Docs Publishing](https://github.com/mischavandenburg/kubecraft/issues/35)

## Resources
- [VS Code dev container for MkDocs Material](https://gist.github.com/akosdudas/f0f14a1e6c0c5653f976af9cd79c56ad)
- [Mastering Git Log Grep](https://gitscripts.com/git-log-grep)
- [Workflow Variables](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/store-information-in-variables)
- [GHA Expressions](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/evaluate-expressions-in-workflows-and-actions)

# 2025-03-31
## Projects
- [GHA for KubeCraft Docs Publishing](https://github.com/mischavandenburg/kubecraft/issues/35)

## Resources
- [GitHub Actions runner](https://github.com/actions/runner)
- [GitHub Actions local container](https://github.com/nektos/act)
- [Git log cheatsheet](https://devhints.io/git-log-format)
- [Git log docs](https://git-scm.com/docs/git-log)
- [GitHub Actions self-hosted runner docs](https://docs.github.com/en/actions/hosting-your-own-runners/managing-self-hosted-runners/about-self-hosted-runners#linux)
- [GitHub Actions CheckoutV4](https://github.com/actions/checkout)
  - Only a single commit is fetched by default, for the ref/SHA that triggered the workflow. 
  - Set `fetch-depth: 0` to fetch all history for all branches and tags.
