# wanted_pre_onboarding 벡엔드 사전과제

## ⭐프로젝트 소개
**Wanted**같은 기업 채용 웹 서비스 API 구현
- 채용공고 - 생성, 목록, 상세
- 사용자 - 지원

## ⭐기술 Stack
- ``Django``, ``Mysql``, ``Git``, ``Postman``

## ⭐완성도 

### ❗요구사항 구현

- [x] **채용공고 등록**
- [x] **채용공고 수정**
- [x] **채용공고 삭제**
- [x] **채용공고 목록**
- [x] **채용공고 검색기능(선택)**
- [x] **채용 상세 페이지**
- [x] **해당회사가 올린 다른 채용공고(선택)**
- [x] **채용공고 지원**

### ❗기술점수 가산요소
- [ ] **Unit Test구현**
- [x] **README에 구현과정 설명**
- [x] **Git commit 메세지 컨벤션**

---
## ⭐상세 과정

---
### ▶️Modeling
- **Company** , **job**, **user**, **apply** 테이블을 메인으로 구현 진행
- **region**, **country** 는 정규화를 위해 테이블 분리
<img src="https://user-images.githubusercontent.com/95831345/185068698-a03d4ed8-328b-4e68-b98e-e81909e9454c.jpg"  width="800"/>

---
### ▶️채용공고 등록
- **Post로 채용공고 등록 & DB반영 확인** 
<img src="https://user-images.githubusercontent.com/95831345/185069923-112638fd-5757-4edb-bfa2-7507b0c98456.jpg"  width="800"/>
<img src="https://user-images.githubusercontent.com/95831345/185074423-99196f58-6f87-471c-b296-113275d227e1.jpg"  width="800"/>

---
### ▶️채용공고 수정
- **Post로 채용공고 수정 & DB반영 확인**
<img src="https://user-images.githubusercontent.com/95831345/185075100-83223548-2bbb-4ca4-a808-0552f0a372ba.jpg"  width="800"/>
<img src="https://user-images.githubusercontent.com/95831345/185075107-2dc016a3-62ad-47ca-870d-55d31bbdf696.jpg"  width="800"/>
<img src="https://user-images.githubusercontent.com/95831345/185075123-6abf7c9d-edec-4004-839b-d80810d003fd.jpg"  width="800"/>

---
### ▶️채용공고 삭제
- **Delete로 채용공고 삭제 & DB반영 확인**
<img src="https://user-images.githubusercontent.com/95831345/185075579-42a7af18-25d7-4ead-8c20-e187afb514b6.jpg"  width="800"/>
<img src="https://user-images.githubusercontent.com/95831345/185075595-db3f4d2e-af32-48bd-9b06-a6c8715d447f.jpg"  width="800"/>
<img src="https://user-images.githubusercontent.com/95831345/185075610-88015f70-c382-45e0-8997-98335e93dfc3.jpg"  width="800"/>

---
### ▶️채용공고 목록 & 검색기능(선택)
- **Post로 채용공고 목록 & DB반영 확인**
- **회사이름과 포지션 둘중 하나 일치시 겸색결과 출력**
<img src="https://user-images.githubusercontent.com/95831345/185075781-3471008c-4bc0-4286-ae11-3b5a8d2718f1.jpg"  width="800"/>
<img src="https://user-images.githubusercontent.com/95831345/185075790-a40e18e0-2422-4031-a922-f2a5e3e54aca.jpg"  width="800"/>
<img src="https://user-images.githubusercontent.com/95831345/185075815-d97bc58b-2582-48ce-8e54-12f585e96720.jpg"  width="800"/>

---
### ▶️채용상세 페이지 + 다른 채용정보(id)
- **채용상세페이지와 그 채용정보를 제외한 나머지 채용 id 출력**
<img src="https://user-images.githubusercontent.com/95831345/185076057-bd2ee0de-16c9-498b-84af-e7f3548cefb3.jpg"  width="800"/>

---
### ▶️채용지원
- **유저가 그 채용정보에 이미 지원을 한 경우 오류메세지 출력 : ALREADY_APPLY**
- **UserID와 JobID가 유효하지않는경우 오류메시지 출력 : USER_NOT_EXIST / JOB_NOT_EXIST**
<img src="https://user-images.githubusercontent.com/95831345/185076266-435c950d-ef22-4527-bc26-d8e62c30a979.jpg"  width="400"/>
<img src="https://user-images.githubusercontent.com/95831345/185076284-6c623492-ecae-413b-9a1b-c854f4dc966a.jpg"  width="400"/>
<img src="https://user-images.githubusercontent.com/95831345/185076299-d9717c37-f435-4573-b69c-837d0e041f11.jpg"  width="400"/>
<img src="https://user-images.githubusercontent.com/95831345/185076317-8d6848de-618f-4b0b-8f52-f1859e44b2d4.jpg"  width="400"/>
<img src="https://user-images.githubusercontent.com/95831345/185076341-c892c855-e4e2-4842-82a4-3b613bd08bbf.jpg"  width="400"/>

---
### ▶️Git Commit 컨벤션
<img src="https://user-images.githubusercontent.com/95831345/185077420-b977c4ba-ebb7-41dd-9b88-3701ced20fed.png"  width="600"/>
