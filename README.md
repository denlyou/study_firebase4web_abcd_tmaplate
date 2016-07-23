# Firebase for Web Study

> 2016/07 장승빈 with ABCD(ABout CoDing)

## Firebase의 Hosting 실습용 템플릿 소스 입니다.

실습용 소스입니다.

### 관련 링크
 - [ABCD 페이스북](https://www.facebook.com/groups/aboutCoding/)
 - [작성자 홈페이지](http://sbsoft.kr)

---

## Firebase의 소개
- [공식 소개 동영상](https://www.youtube.com/watch?v=O17OWyx08Cg&feature=youtu.be)
- [공식 소개 동영상-개발자용](https://www.youtube.com/watch?v=ySmWlU9j3j4&feature=youtu.be)
- [Google Developers Korea blog](http://googledevkr.blogspot.kr/2016/05/firebase-8-firebase-google43.html)
- [2016 I/O Seoul firebase 발표자료 (SlideShare)](http://www.slideshare.net/ChiungChoi/google-firebase-io-extended-2016)

- 웹을 중심으로 활용 가능한 서비스
> 웹 개발과 관련된 Database, Hosting, Storage, Authentication 서비스

### Hosting
> Web App를 개발하기에 최적화된 서비스

- [Introducing Firebase Hosting (youtube)](https://youtu.be/jsRVHeQd5kU)
- 안전한 연결 : HTTPS 프로토콜을 기본으로 사용
- 빠른 컨텐츠 전달 : 사이트 배포(deploy)시 전세계 서버(SSD)에 Ceche되어 제공됨
- 쉽고 빠른 개발이 가능
- 한번의 클릭으로 홈페이지 Roll-Back

### Firebase CLI
> CLI : Command Line Interface

- Firebase의 호스팅을 사용하기 위해 필수
- 주요 명령어
  - `firebase login` : firebase의 사용자 로그인
  - `firebase init` : 디렉토리를 firebase 프로젝트 용도로 만들어 줌
  - `firebase deploy` : 현재 프로젝트를 호스팅 서버로 배포
  - `firebase serve` : 현재 프로젝트를 로컬 웹 서버로 만들어 줌
- [Firebase CLI Reference DOC](https://firebase.google.com/docs/cli/)

>### Firebase CLI 설치하기
> npm을 이용해 설치해야 하기에 먼저 nodejs와 npm 설치가 되어 있어야 합니다.
>```
>npm install –g firebase-tools
>```
> - npm (Nodejs Package Manager) : nodejs로된 응용 프로그램 설치/삭제 관리자
