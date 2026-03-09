# study_react_ts Setting

This template should help get you started developing with react and type script in Vite.

## version
- node : 22
- react : 19
- typescript


## Server
- [springboot](https://github.com/blueclover22/study_springboot)

## vue
- [vue.js](https://github.com/blueclover22/study_vue)


## Project Setup

```sh
pnpm install
```

### Compile and Hot-Reload for Development

```sh
pnpm run dev
```

### Compile and Minify for Production

```sh
pnpm run build
```

---
---

# New react project setting

- 프로젝트를 생성 할 위치에서 터미널 실행

- my-project라는 react 프로젝트 생성

```sh
pnpm create vite study_react_ts --template react-ts

or

cd study_react_ts
pnpm create vite . --template react-ts
. 사용시 root 위치에 프로젝트 생성됨
```

- 프로젝트 내부에 파일이 존재할 경우
```sh
◆  Current directory is not empty. Please choose how to proceed:
│  ○ Cancel operation -- 취소
│  ○ Remove existing files and continue -- 기존 파일 전부 삭제 후 진행
│  ● Ignore files and continue -- 기존 파일 유지하고 덮어쓰며 진행 / 깃 레포지토리에 생성할 경우 readme.md나 .gitignore 파일이 있는 경우 선택
``` 

- vite 베타 버전을 사용할지 선택
```sh
◆  Use Vite 8 beta (Experimental)?:
│  ○ Yes
│  ● No
``` 

- pnpm install 까지 자동으로 할 지 선택
```sh
◆  Install with pnpm and start now?
│  ● Yes / ○ No
``` 