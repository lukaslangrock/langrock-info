---
title: "Git Server"
summary: "THe Gitea instance under langrock.info"
url: "git"
searchHidden: false
---

Langrock.info now hosts a Gitea instance under [git.langrock.info](https://git.langrock.info). This was migrated from libre.moe as the instance there has been replaced with GitLab.

The instance here will remain available in order to not break links, but lacks SSH connection and is routed through Cloudflare, as the service has been under attack by (probably AI) bots, scarping every possible available page - which are quite a few for a Git server, where every commit in every branch provides unique links to the entire project directory tree. In other words - the links are endless and the bots don't care, especially the Chinese ones.

Signing up through Git itself is not possible, and not really encouraged. If you are looking for a Git server, try my GitLab on [lab.libre.moe](https://lab.libre.moe). If you really want to sign up, that still works if you use an account from libre.moe and authenticate via SSO to Gitea.
