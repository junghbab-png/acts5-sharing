# 액오 나눔지 배포 파일

## 들어있는 파일
- index.html : 청년들이 사용하는 나눔지 페이지
- admin.html : 관리자 기도제목 확인 페이지
- cover.jpg : 표지
- theme.jpg : 주제/본문 페이지
- qbg.jpg : 질문/기도제목 배경
- firestore.rules : Firestore 보안 규칙

## 꼭 같이 두어야 하는 폰트 파일
이 폴더에 아래 폰트 파일을 직접 같이 넣어주세요.
- GmarketSansTTFMedium.ttf
- Jalnan2.otf

## Firebase에서 해야 할 것
1. Firestore 생성
2. Authentication > Sign-in method 에서 이메일/비밀번호 활성화
3. Authentication > Users 에서 관리자 계정 생성
   - 이메일: acts5.admin@gmail.com
   - 비밀번호: 직접 설정
4. Firestore > Rules 에서 firestore.rules 내용 붙여넣기 후 Publish

## 배포
Vercel에 이 폴더 전체를 업로드하면 됩니다.
- 청년용: /index.html
- 관리자용: /admin.html
