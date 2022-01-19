---
theme: unicorn
background: https://source.unsplash.com/collection/94734566/1920x1080
highlighter: shiki
lineNumbers: true
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: Web 体验技术发展前沿（偏产品向）
---

# Web 体验技术发展前沿（偏产品向）

本文内容具有一定局限性，不代表社区真实现状，仅做参考！

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
     小芋头君@yootou.com
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <!-- <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button> -->
  <a href="https://github.com/yu-tou" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# 本文主要内容

- 实时体验（Realtime experience）
- 在线协作（Online collaboration）
- Web 3D 技术
- 浏览器系统能力
- 体验应用快速开发
- 移动端
- 区块链

---

# 一 实时体验

---

# 实时体验

<br/>

[https://vercel.com](https://vercel.com)

<br/>

在 2021 年 6 月，Next.js 框架背后的开发商 Vercel 在 C 轮融资中筹集了 1.02 亿美金，使其估值达到 11 亿美元，正式成为了一家独角兽企业。11 月份，Vercel 再次宣布获得新的融资，其在 D 轮融资中筹集了 1.5 亿美元，使其估值相比之前翻了一番，达到 25 亿美元。

- 70 CITIES
- 24B+ REQUESTS PER WEEK
- 10PB DATA SERVED
- 99.99% GUARANTEED UPTIME

<br/>

部署前端应用的云服务，也支持简单的服务端、存储等。

---

# <svg role="img" aria-label="Vercel Inc." height="40" viewBox="0 0 283 64" fill="var(--geist-foreground)"><path d="M37 0l37 64H0L37 0zM159.6 34c0-10.3-7.6-17.5-18.5-17.5s-18.5 7.2-18.5 17.5c0 10.1 8.2 17.5 19.5 17.5 6.2 0 11.8-2.3 15.4-6.5l-6.8-3.9c-2.1 2.1-5.2 3.4-8.6 3.4-5 0-9.3-2.7-10.8-6.8l-.3-.7h28.3c.2-1 .3-2 .3-3zm-28.7-3l.2-.6c1.3-4.3 5.1-6.9 9.9-6.9 4.9 0 8.6 2.6 9.9 6.9l.2.6h-20.2zM267.3 34c0-10.3-7.6-17.5-18.5-17.5s-18.5 7.2-18.5 17.5c0 10.1 8.2 17.5 19.5 17.5 6.2 0 11.8-2.3 15.4-6.5l-6.8-3.9c-2.1 2.1-5.2 3.4-8.6 3.4-5 0-9.3-2.7-10.8-6.8l-.3-.7H267c.2-1 .3-2 .3-3zm-28.7-3l.2-.6c1.3-4.3 5.1-6.9 9.9-6.9 4.9 0 8.6 2.6 9.9 6.9l.2.6h-20.2zM219.3 28.3l6.8-3.9c-3.2-5-8.9-7.8-15.8-7.8-10.9 0-18.5 7.2-18.5 17.5s7.6 17.5 18.5 17.5c6.9 0 12.6-2.8 15.8-7.8l-6.8-3.9c-1.8 3-5 4.7-9 4.7-6.3 0-10.5-4.2-10.5-10.5s4.2-10.5 10.5-10.5c3.9 0 7.2 1.7 9 4.7zM282.3 5.6h-8v45h8v-45zM128.5 5.6h-9.2L101.7 36 84.1 5.6h-9.3L101.7 52l26.8-46.4zM185.1 25.8c.9 0 1.8.1 2.7.3v-8.5c-6.8.2-13.2 4-13.2 8.7v-8.7h-8v33h8V36.3c0-6.2 4.3-10.5 10.5-10.5z"></path></svg>

<br/>

## 核心特色

<br/>

- 产品定位和产品功能极简，官方定义：Develop. Preview. Ship.
- 部署过程极简，连接 Github 账号、导入 Github 项目、Deploy、Preview，最小步骤完成。
- 在 vercel 里部署应用的各种过程都不需要刷新页面，所有状态都会 <span style="color:#ff0000;">自动推进</span> 和 <span style="color:#ff0000;">实时生效</span>，触发往往只需一个点击

---

# <svg role="img" aria-label="Vercel Inc." height="40" viewBox="0 0 283 64" fill="var(--geist-foreground)"><path d="M37 0l37 64H0L37 0zM159.6 34c0-10.3-7.6-17.5-18.5-17.5s-18.5 7.2-18.5 17.5c0 10.1 8.2 17.5 19.5 17.5 6.2 0 11.8-2.3 15.4-6.5l-6.8-3.9c-2.1 2.1-5.2 3.4-8.6 3.4-5 0-9.3-2.7-10.8-6.8l-.3-.7h28.3c.2-1 .3-2 .3-3zm-28.7-3l.2-.6c1.3-4.3 5.1-6.9 9.9-6.9 4.9 0 8.6 2.6 9.9 6.9l.2.6h-20.2zM267.3 34c0-10.3-7.6-17.5-18.5-17.5s-18.5 7.2-18.5 17.5c0 10.1 8.2 17.5 19.5 17.5 6.2 0 11.8-2.3 15.4-6.5l-6.8-3.9c-2.1 2.1-5.2 3.4-8.6 3.4-5 0-9.3-2.7-10.8-6.8l-.3-.7H267c.2-1 .3-2 .3-3zm-28.7-3l.2-.6c1.3-4.3 5.1-6.9 9.9-6.9 4.9 0 8.6 2.6 9.9 6.9l.2.6h-20.2zM219.3 28.3l6.8-3.9c-3.2-5-8.9-7.8-15.8-7.8-10.9 0-18.5 7.2-18.5 17.5s7.6 17.5 18.5 17.5c6.9 0 12.6-2.8 15.8-7.8l-6.8-3.9c-1.8 3-5 4.7-9 4.7-6.3 0-10.5-4.2-10.5-10.5s4.2-10.5 10.5-10.5c3.9 0 7.2 1.7 9 4.7zM282.3 5.6h-8v45h8v-45zM128.5 5.6h-9.2L101.7 36 84.1 5.6h-9.3L101.7 52l26.8-46.4zM185.1 25.8c.9 0 1.8.1 2.7.3v-8.5c-6.8.2-13.2 4-13.2 8.7v-8.7h-8v33h8V36.3c0-6.2 4.3-10.5 10.5-10.5z"></path></svg>

<br/>

 <video src="/1.mp4" controls style="height:70%;border-radius:5px;" autoplay />

---

# 背后技术

<br/>

## Next.js

- The React Framework for Production
- hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more

## SWR

![](/swr.vercel.app_zh-CN.png)

## Hyper

- https://hyper.is/
- a beautiful and extensible experience for command-line interface

---

# 二 在线协作

---

## 1. figma cursor chat

<br/>

<img src="/3.gif" style="height:60%">

<br/>

[https://github.com/yomorun/react-cursor-chat](https://github.com/yomorun/react-cursor-chat)

---

## 2. figma comments

<br/>

<img src="/4.gif" style="height:60%">

---

## 3. figma voice

<br/>

<img src="/5.png" style="width:60%">

---

## 3. figma voice

<br/>

<img src="/5.png" style="width:60%">

---

## 4. FigJam

<br/>

<img src="/6.png" style="height:60%">

---

## 5. Miro

<br/>

cursor chat & live chat & video chat & screen share & comments & collaborative editing

<video src="/7.mp4" controls style="height:70%;border-radius:5px;" autoplay />

---

# Figma

### 2021 年 6 月融资 2 亿美金，市值 100 亿美金

<br/>

# Miro

### 2022 年 1 月融资 4 亿美金，市值 175 亿美金

<br/>

有意思的是这些专业工具的一大核心初始卖点就是协同。

只是随着疫情格局变化，这种协同一直在被强化、扩展、创新（cursor chat）。

除了核心功能的协同，这些工具反向把 chat、meet、voice 搬到了工具内。

这么大的市值中，在线办公、在线会议的价值占比不会低，而不是单纯的设计工具或者白板工具。

---

## 6. Next.js live (vercel)

<br/>

https://vercel.com/live

Join/Draw/Chat/Code，这里不难理解为什么 vercel 要做 Next.js live，借鉴的是以上几个工具的颠覆思路

<img src="/8.png" style="width:58%">

---

# 技术框架

<img src="/9.png" style="width:50px;display:block; ">

<br/>

https://replicache.dev/

Replicache makes it easy to add realtime collaboration, lag-free UI, and offline support to web apps.

<img src="/10.png" style="width:50%">

---

# 三 体验应用快速开发

## Jamstack

[https://jamstack.wtf/](https://jamstack.wtf/)

#### DEFINITION

"JAM" stood for JavaScript / API / Markup。

可以认为 Jamstack 是一组开发网站的最佳实践，包括目标定义、最佳实践、工作流、实用工具等。一些云产品或者框架，遵循类似的理念实现。

#### MEANING

Decoupled 前后端解耦 / Static-first 静态内容优先 / Progressively enhanced 渐进增强

#### BEST PRACTICES

CDN 网络分发 / 原子化部署 / 缓存自动失效 / 版本管理 / 自动化构建

#### WORKFLOW

Develop / Version Control / Automated build( assets. pre render. deploy.) / Update CDN.

---

# DEVELOPMENT

### The Fullstack React Framework

- 基本、纯粹、场景无关的底层框架。
- Next.js。可能是使用最广泛的 Fullstack 框架，主要是其 SSR&SSG 能力，0 配置，及 Vercel 的无缝官方支持。
- Remix.js。知名团队最新出品的框架，主要是更强的前后端代码融合能力（同一个组件文件中），更好的加载体验（组件级别的 SSG）。

### Web Application Framework

- 通常是一系列基础工具的整合，例如 GraphQL、Prisma 等，将数据定义和服务开发等部分 less 掉。
- Redwood.js。an opinionated, full-stack, serverless-ready web application framework。
- Blitz.js。a batteries-included framework that features a "Zero-API" data layer abstraction that eliminates the need for REST/GraphQL

### Static Site Generators

- 主要用来建站、博客的一些工具框架，例如管理文章、主题、构建等，通常用来写博客、写文档等。
- Gatsby / Hugo / Jekyll / VuePress / Docsify / GitBook 等

### Site Builders

- 低代码搭建工具，如 Stackbit / Builder.io / CloudCannon

---

# DYNAMIC PARTS

### 函数服务

- AWS lambda functions / Netlify Functions / Vercel Functions

### 数据管理

- Prisma / AirTable / Fauna / Hasura / MongoDB Atlas / AWS DynamoDB

### 表单工具

- AirTable / Netlify Forms / Getform / FormKeep

### 评论工具

- walinejs / Staticman / Disqus

### 商品交易

- Shopify / Snipcart / Commerce Layer

### 搜索服务

- Algolia / fuse.js / Lunr.js

---

# 简单总结

- 利用一系列工具组合，快速构建和部署自己的网站
- 在国外是一个很大的市场，在国内基本不存在这些场景，国内同样的场景是给每个小程序平台写小程序，各平台有自己的部署、函数、存储。。
- 国外社区这种整体架构分解、细分领域发力、灵活重组、生态上互相支持，共赢且推动社区向同一个方向发展的做法值得深思。
- 每个部分都可以产生百亿美金市值的公司。

---

---

# Learn More

欢迎 PR 补充内容

[GitHub 链接](https://github.com/yu-tou/web-front-end-technology-forward-share-slide)
