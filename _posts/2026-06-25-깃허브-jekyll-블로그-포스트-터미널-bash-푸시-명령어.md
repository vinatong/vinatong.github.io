---
layout: post
title: "깃허브 Jekyll 블로그 포스트 터미널 Bash 푸시 명령어"
date: 2026-06-25 08:43:28 +0900
image: "https://images.unsplash.com/photo-1654277041218-84424c78f0ae?fm=jpg&q=60&w=3000&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8JUVBJUI5JTgzJUVEJTk3JTg4JUVCJUI4JThDfGVufDB8fDB8fHww"
description: "GitHub Pages(github.io) 블로그에 새로운 포스트를 작성한 후, 이를 반영(배포)하기 위해 터미널(Git Bash, cmd 등)에서 입력해야 하는 기본 Git 명령어 순서입니다. 블로그가 있는 로컬 ..."
---

![깃허브 Jekyll 블로그](https://images.unsplash.com/photo-1654277041218-84424c78f0ae?fm=jpg&q=60&w=3000&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8JUVBJUI5JTgzJUVEJTk3JTg4JUVCJUI4JThDfGVufDB8fDB8fHww)

GitHub Pages(github.io) 블로그에 새로운 포스트를 작성한 후, 이를 반영(배포)하기 위해 터미널(Git Bash, cmd 등)에서 입력해야 하는 기본 Git 명령어 순서입니다.

블로그가 있는 로컬 폴더로 이동한 후 아래 명령어들을 차례대로 입력하시면 됩니다.

1. 가장 많이 쓰는 기본 3단계 명령어
- 모두 복사해서 터미널(windows powershell)에 넣고 실행(엔터).
- 실행파일(서버파일) 폴더에서 실행해야죠.
- 팁:해당 폴더에 우측마우스 클릭하면 터미널열기 메뉴로 쉽게 접속
```
# 1. 변경된 모든 파일(새 포스트 포함)을 스테이징 영역에 추가
git add .

# 2. 저장 메시지(커밋 메시지) 작성
git commit -m "Add new blog post"

# 3. GitHub 원격 저장소로 업로드 (블로그 반영)
git push origin main
```
참고: 사용하는 블로그 테마나 설정에 따라 기본 브랜치 이름이 main이 아니라 master일 수도 있습니다. 만약 위 명령어가 에러가 난다면 git push origin master로 입력해 보세요.

---

### 🔗 비나통 링크 안내
* **비나통 공식홈페이지** : [www.vinatong.store](https://www.vinatong.store)
* **비나통 공식블로그** : [vn.coupong.online](https://vn.coupong.online)
