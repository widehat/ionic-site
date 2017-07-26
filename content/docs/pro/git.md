---
layout: v2_fluid/pro_docs_base
category: pro-git
id: pro-git
title: Working with Git - Ionic Pro Documentation
hide_header_search: true
pre_footer: true
dark_header: true
---

# Working with Git

Ionic Pro uses a git-based workflow to manage updates and to push new builds through Ionic View, Live Deploy, and more.

## Setup

If you haven't followed the quick setup guide in the Ionic Pro Dashboard after creating an app, follow the instructions below.

First, install the latest version of the Ionic CLI:

```bash
npm install -g ionic@latest
```

Next, find your App ID from the Ionic Pro Dashboard. Then run:

```bash
ionic start myApp --pro-id APP_ID
```

Where `APP_ID` is the ID for your app from the Ionic Pro Dashboard.

Finally, `cd` into the app directory and use git to push your changes to Ionic Pro:

```bash
cd myApp
git push ionic master
```

## Adding SSH Keys
