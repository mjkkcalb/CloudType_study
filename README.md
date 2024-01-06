# CloudType_study

- 작업 진행 후 front 파일에 npm run build
- front 파일에 생성된 build 파일 ctrl + c
- back 파일에 ctrl + v
- 깃 허브 레파지토리 생성 후 back파일 업로드
    - 업로드시 .env 파일과 node_modules 파일 제외
    - (분홍 형광펜 표시만 올리기)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/a669081c-5776-46fa-897c-e787e4b50139/01a45020-894c-4b34-89b7-9ff5bbed6f7f/Untitled.png)

- 클라우드 타입 카드 등록
- 프로젝트 추가 선택 후 내 깃 저장소 배포하기 클릭
- 저장소 선택
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/a669081c-5776-46fa-897c-e787e4b50139/3e470c76-c992-48d2-a11b-5938cc64b286/Untitled.png)
    
- 언어/ 프레임웍 선택 - node.js
- 버전 설정 → 제일 높은 버전 (현재 v20

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/a669081c-5776-46fa-897c-e787e4b50139/a017c0a3-43b2-4b9e-9b2a-4574b64a3201/Untitled.png)

- **Environment variables** 옆 (+)버튼 3개 추가
- 추가된 칸에 back 폴더 .evn 파일 내용 추가

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/a669081c-5776-46fa-897c-e787e4b50139/ea521af6-b023-47d5-9d7d-cc021e5742e5/Untitled.png)

- port 번호 8080 (설정해둔 서버 번호로 변경 기본 3000 → 수정 8080)
- install command → npm ci 입력
- Start command → node index.js (내가 만든 폴더명)
- 비어있는 곳은 작성 필요 x (이미지 참고)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/a669081c-5776-46fa-897c-e787e4b50139/b8958eae-57d7-4a01-8cc2-a6c78c771918/Untitled.png)

- 배포하기 선택
- 도메인 들어가면 1~3분 뒤에 배포 나옴!!
- 너무 빨리 들어가면 404에러 나옵니다
