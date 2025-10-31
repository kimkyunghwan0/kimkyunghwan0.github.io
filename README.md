
개발환경 : SVN 세팅.
SVN Repositories -> new -> Repository Location

경로 : svn://svn.indisystem.co.kr/indisystem/kict/web-full-kict2025

check out -> 프로젝트 우클릭 -> Configure -> Convert to Maven Project (메이븐 프로젝트로 변환)

프로젝트 우클릭 -> Maven -> Update Project

<img width="193" height="83" alt="image" src="https://github.com/user-attachments/assets/b3350a06-9ac2-4e50-9925-c40ec3464191" />

그후 외부 톰캣(9.0) 설정 후 구동

만약 NPM 오류 발생시 해당 프로젝트 위치

cd frontend
npm install
npm run build

기본 세팅 : 
port : 8000
application.properties로 local, dev 변환. 기본 applcation-local.properties 사용

map.js (npm 사용 js) 수정 시 바로 확인 하고 싶을 때
프로젝트 위치에서 
cd frontend
npm run dev
입력 후 js 수정 확인

