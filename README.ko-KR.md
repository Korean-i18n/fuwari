# 🍥Fuwari

[Astro](https://astro.build)로 구축된 정적 블로그 템플릿입니다.

[**🖥️미리보기 (Vercel)**](https://fuwari.vercel.app)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;[**🌏中文 README**](https://github.com/saicaca/fuwari/blob/main/README.zh-CN.md)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;[**🌏日本語 README**](https://github.com/saicaca/fuwari/blob/main/README.ja-JP.md)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;[**🌏한국어 README**](https://github.com/saicaca/fuwari/blob/main/README.ko-KR.md)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;[**📦Old Hexo Version**](https://github.com/saicaca/hexo-theme-vivia)

![Preview Image](https://raw.githubusercontent.com/saicaca/resource/main/fuwari/home.png)

## ✨ 특징

- [x] [Astro](https://astro.build) 및 [Tailwind CSS](https://tailwindcss.com)로 구축됨
- [x] 부드러운 애니메이션 및 페이지 전환
- [x] 라이트 모드 / 다크 모드
- [x] 사용자 정의 가능한 테마 색상 및 배너
- [x] 반응형 디자인
- [ ] 댓글
- [x] 검색
- [ ] 목차
## 🚀 사용하는 방법

1. 이 템플릿에서 [새 저장소를 생성](https://github.com/saicaca/fuwari/generate)하거나 이 저장소를 포크하세요.
2. 블로그를 로컬에서 편집하려면 저장소를 복제하고 `pnpm install` 및 `pnpm add sharp`를 실행하여 종속성을 설치하세요.  
   - 아직 [pnpm](https://pnpm.io)을 설치하지 않았다면 `npm install -g pnpm`을 실행하여 [pnpm](https://pnpm.io)을 설치하세요.
3. 블로그를 사용자 정의하려면 `src/config.ts` 구성 파일을 편집하세요.
4. `pnpm new-post <filename>`을 실행하여 새 게시물을 만들고 `src/content/posts/`에서 편집하세요.
5. [가이드](https://docs.astro.build/en/guides/deploy/)에 따라 블로그를 Vercel, Netlify, GitHub 페이지 등에 배포하세요. 배포하기 전에 `astro.config.mjs`에서 사이트 구성을 편집해야 합니다.

## ⚙️ Frontmatter of Posts

```yaml
---
title: My First Blog Post
published: 2023-09-09
description: This is the first post of my new Astro blog.
image: /images/cover.jpg
tags: [Foo, Bar]
category: Front-end
draft: false
---
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                             | Action                                           |
|:------------------------------------|:-------------------------------------------------|
| `pnpm install` AND `pnpm add sharp` | Installs dependencies                            |
| `pnpm dev`                          | Starts local dev server at `localhost:4321`      |
| `pnpm build`                        | Build your production site to `./dist/`          |
| `pnpm preview`                      | Preview your build locally, before deploying     |
| `pnpm new-post <filename>`          | Create a new post                                |
| `pnpm astro ...`                    | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro --help`                 | Get help using the Astro CLI                     |
