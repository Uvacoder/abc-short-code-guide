---
title: FAQ
description: 'Frequently asked questions, CMD/CTR + F this page to find answer to common problems.'
---

# Frequently Asked Questions

Find commonly asked questions you have about development, deployment and course content.
You can use `CMD/CTR + F` on this page to quickly find the questions you have. 

## Setup instructions

You can check out [setup installation](/learn/setup-installation); a detailed write up of 
the steps required to install VS Code, Node.js and the web dev project is written there.

## How do I set up the project?
```shell
npm init heartcode-web-dev
```

If you are using a Windows computer, there might be some issues with the cache if your PC
name contains a space. You can check out this [Stackoverflow article](https://stackoverflow.com/questions/59405152)
for more information.

## How do run the project?

> Why is my project not running?

```shell
# cd heartcode-web-dev
npm run dev
```

## How do I deploy?
```shell
# cd heartcode-web-dev
npm run deploy
```

## How do I install code highlight?

[Vetur Plugin](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

## VS Code Live Share

Live Share enables your team to quickly collaborate on the same codebase without the need 
to synchronize code or to configure the same development tools, settings, or environment.

## What are the list of reserved keywords in js, nuxt and vue?

> The words that you cannot use.

- `<n-link>`, `<nuxt-link>`, `<router-link>`
- `<client-only>`, `<no-ssr>`
- `<nuxt>`, `<nuxt-child>`
- `<slot>`, `<template>`
- `delete`