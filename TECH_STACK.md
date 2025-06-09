# 📚 기술 스택 및 사용 라이브러리 정리

이 문서는 본 레포지토리(`haeun-boilerplate`)에서 사용된 주요 라이브러리와 기술 스택을 정리한 자료입니다.

---

## 📦 주요 라이브러리 및 프레임워크

- **Nuxt 3** (`nuxt`): Vue 기반의 SSR/SSG 프레임워크
- **Vue 3** (`vue`): 프론트엔드 UI 프레임워크
- **TypeScript**: 타입 안정성을 위한 자바스크립트 상위 언어 (프론트/백엔드 모두 사용)
- **Pinia** (`pinia`, `@pinia/nuxt`, `pinia-plugin-persistedstate`): 상태 관리 라이브러리
- **Vue Router** (`vue-router`): 라우팅 관리
- **Tailwind CSS** (`tailwindcss`, `@tailwindcss/vite`, `tailwind-merge`): 유틸리티 기반 CSS 프레임워크
- **shadcn-vue** (`shadcn-nuxt`): shadcn UI 컴포넌트 라이브러리
- **@nuxtjs/i18n**: 다국어(국제화) 지원
- **@nuxtjs/mdc**: Markdown/MDX 지원
- **@nuxtjs/sitemap**: 사이트맵 자동 생성
- **@vueuse/nuxt**: VueUse 유틸리티 함수 모음
- **lucide-vue-next**: 아이콘 라이브러리
- **tw-animate-css**: Tailwind 기반 애니메이션 유틸리티
- **class-variance-authority, clsx**: CSS 클래스 관리 유틸리티

---

## ⚙️ 빌드 및 개발 도구

- **Vite**: 빠른 번들러 및 개발 서버 (Nuxt 내부적으로 사용)
- **Node.js**: 런타임 환경
- **npm, pnpm, yarn, bun**: 패키지 매니저 지원

---

## 🗂️ 프로젝트 구조 및 설정

- **TypeScript**: `tsconfig.json` 및 `server/tsconfig.json`을 통해 프론트/백엔드 모두 타입스크립트 기반
- **Tailwind CSS 설정**: `components.json`에서 Tailwind, shadcn, 아이콘 설정 등 관리
- **컴포넌트 자동 등록 및 별칭(alias)**: `components.json`에서 경로 별칭 지정
- **Nuxt 모듈 시스템**: `nuxt.config.ts`에서 다양한 모듈 및 플러그인 활성화

---

## 📝 기타

- **README.md**: Nuxt 공식 문서 및 기본적인 개발/배포 방법 안내
- **SSR/SSG 지원**: Nuxt 3의 기본 기능
- **다국어, SEO, 마크다운 등 확장성**: 다양한 Nuxt 모듈로 지원

---

## 🏷️ 요약

이 프로젝트는 **Nuxt 3 + Vue 3 + TypeScript + Tailwind CSS + Pinia + shadcn-vue** 조합을 기반으로, 최신 프론트엔드 개발 트렌드와 생산성을 모두 고려한 보일러플레이트입니다.
추가적으로, 다국어(i18n), SEO(사이트맵), 마크다운, 아이콘, 상태관리, 컴포넌트 자동화 등 실무에 필요한 다양한 기능이 내장되어 있습니다.