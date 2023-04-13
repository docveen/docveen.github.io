---
layout: post
title:  "jekyll post 작성법"
date:   2023-04-13 16:16:01 +0900
categories: 개발
---
## 로컬서버 실행법
```
bundle exec jekyll serve
```

## post 작성법
_posts 디렉토리 아래에 다음 형식으로 파일생성
```
YYYY-MM-DD-파일이름.md
```

파일 내용 처음에 다음 내용을 추가, 이후 내용 작성
```
---
layout: post
title:  "테스트 페이지 1"
date:   2023-04-13 16:16:01 +0900
categories: dev
---
```

markdown 링크걸기 샘플
```
[first_post]({{ site.baseurl }}{% link _posts/2021-01-17-first_post.md %})
```

root 디렉토리에 md 파일을 생성하면 메뉴에 표시된다.
