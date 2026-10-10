# Novel-Sharing-Platform_Nodejs

Node.js로 만든 웹 소설 공유 플랫폼 **Your_Fantasy**의 개인 프로젝트 기록입니다. Express·EJS·MySQL을 사용하며 기존 개발 기간과 설계 자료를 함께 보관합니다.

- [애플리케이션](dev/yfantasy): 서버·라우터·화면
- [DB 정의](DB.md) · [페이지 정의](page.md)
- [개발 진행 기록](진행.md)

## 사용 스택
- front-end : ejs, bootstrap
- back-end : node.js, express
- db : mysql

## 일정 
- 2022.05.27 ~ 2022.06.04 : 기획 및 db 구조생성, express 프로젝트 생성, 일부 모듈 및 라우터 작성
- 2022.06.05 ~ 2022.06.06 : 템플릿 수정 및 라우터 작성
- 2022.06.06 : 세션 인증 추가
- 2022.06.06 ~ 2022.06.10 : 종료

## DB 정의
[DB.md](DB.md)

## 페이지(사용자 인터페이스) 정의
[page.md](page.md)

## 로컬 실행

Node.js와 npm을 준비한 뒤 앱 디렉터리에서 의존성을 설치합니다.

```bash
cd dev/yfantasy
npm install
```

- 연결한 mysql 접속정보를 db_info와 app.js의  option에 넣고 mysql db에 noveldb데이터베이스를 만들어 테이블을 만들어준다.

설정 후 아래 명령으로 실행합니다.

```bash
npm start
```

기본 주소는 `http://localhost:3000`이며 `PORT` 환경변수로 포트를 바꿀 수 있습니다.
