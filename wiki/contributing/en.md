---
layout: article
title: Contributing
date: 2025-07-08T04:04:53.522Z
description: A how-to on properly contributing to the Camellia Wiki.
---

If you're reading this, you're likely interested in contributing to the Camellia Wiki - and we're excited to have you!

## Contribution Guidelines

### Our standards

- Please keep all articles respectful, unbiased, and professional.
- Articles must be easy to understand and digest.
- Content must follow [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119).
- Please ensure to use [proper markdown](https://www.markdownguide.org/cheat-sheet/) for writing.
- All trademarks in any content must be correctly typed, including games, media, music, etc. For example: Discord, YouTube, BEMANI, etc.
- Any media uploaded, including videos and photos, must be one of the following: your own work; freely licensed; within the public domain; or under fair use.
- All articles must follow the correct format:

```md
---
layout: article
title: Your Title Here
date: ISO 8601 (like 2025-07-08T04:04:53.522Z)
description: Brief summary of what this article is about.
image: An optional link to a cover image. (may be relative)
---
```

### Contributions

A good portion (if not all) of the Camellia Wiki uses GitHub and Git. You will need to familiarize yourself with both [GitHub](https://github.com/) and [Git](https://git-scm.com/).

## How to contribute

### Getting started

To begin your contribution journey, please ensure you have read and understand our standards. Next, you will need to fork the GitHub repository (or "repo" for short) that you wish to work on. This will allow you to create changes without affecting our main repos. Please fork one of the following:

- **Articles** (Site content): [wiki-articles](https://github.com/FlowerShaper/wiki-articles)
- **Frontend** (The site in itself): [wiki-frontend](https://github.com/FlowerShaper/wiki-frontend)
- **Backend** (Provides content and other data to site): [wiki-backend](https://github.com/FlowerShaper/wiki-backend)

> Please read any README.md file! Where applicable, there will be important instructions to setup the environment needed to make things work.

Afterwards, you may begin your contribution edits.

If you are writing Wiki Articles, we have a fancy [Preview](https://camellia.wiki/preview) system, which allows you to roughly view your changes, even in-time, as it would appear on the site.

> Don't forget to commit and push changes to your fork. You will NOT be able to edit from the main repos.
> {: .warning }

### Getting your contribution(s) published

Woohoo! If you've made it this far, congrats - it's time to check to ensure everything looks good and you've followed our standards. If you're sure that you're ready to go, please create a Pull Request on the main repo that you have forked. Code reviewers may be requested automatically, but you may request individuals when applicable.

Once your contribution(s) have been reviewed, you'll be notified whether your contribution(s) were merged or need further changes.

- **If merged**, you're all set and you can see them live.
- **If not merged**, the reviewer will usually leave a comment or two so you can go back and perform those necessary changes. Any changes made to your fork will automatically apply within the context of the Pull Request.

## Need help or unsure about something?

If you have any questions, comments, or concerns about anything in this guide or in general, feel free to let us know in the [#💻dev-discussion](https://discord.com/channels/435720333786480641/1174624963584610334) channel in our [Discord](https://discord.gg/camellia).
