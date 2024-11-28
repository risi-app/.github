# RISI: **Gesture-Controlled SNS Platform**
<br>
<br>

## 📌 프로젝트 소개  
RISI는 AI 기반 손 제스처 인식 기술과 SNS 플랫폼을 결합한 웹 애플리케이션입니다.  
사용자는 손 제스처를 활용해 화면 밝기 조절, 볼륨 조정 등 PC 기능을 제어할 수 있으며, 동시에 SNS 기능을 통해 소통의 공간을 즐길 수 있습니다.  
이 프로젝트는 편의성과 혁신성을 동시에 제공하며, 접근성과 확장성을 고려한 디자인과 기술로 개발되었습니다.

<br>
<br>
<br>

## 💡 주요 기능  

### 1️⃣ **SNS 플랫폼**  
- 사용자, 게시물, 댓글 데이터를 MySQL 데이터베이스에 저장 및 관리.  
- Spring Boot 기반 서버에서 API를 통해 사용자 정보와 게시물 데이터를 처리.  
- 게시물 및 댓글의 생성, 수정, 삭제, 조회 기능을 포함.  

### 2️⃣ **AI 제스처 컨트롤**  
- MediaPipe를 활용해 손 제스처 인식.  
- 손가락 관절 위치 및 거리 데이터를 분석하여 화면 밝기, 볼륨 조절 등 PC 기능 제어.  
- Flask 서버를 통한 AI 서비스 구현 및 API 통신으로 웹과 연결.

<br>
<br>
<br>

## 🚀 프로젝트 목표 및 효과  

### 🎯 **기능적 목표**  
1. **사용자 편의성 제공**  
   - 손을 사용하지 않고도 RISI 웹 페이지를 통해 다양한 작업 수행 가능.  
   - 화면 밝기, 볼륨 조절 등 실시간 제어.  

2. **SNS 활성화 및 경제적 효과**  
   - 제스처 컨트롤 기능 사용 중 자연스럽게 SNS 게시물 확인 가능.  
   - 게시물 노출 증가 → 사용자 소통 활성화 → 광고 및 홍보 효과 극대화.  

### 💡 **주요 효과**  
- 손이 음식으로 더럽거나 마우스를 사용할 수 없는 상황에서 제스처를 활용한 작업 가능.  
- 소셜 플랫폼과 AI 기능의 통합으로 새로운 사용자 경험 제공.  
- 사용자는 별도 프로그램 설치 없이 간단한 웹 접속만으로 제스처 컨트롤 사용.  

<br>
<br>
<br>

## 🔧 기술 스택  

### **Frontend**  
- React: 사용자 인터페이스 구현.  
- HTML5, CSS3, JavaScript: 웹 디자인 및 동적 요소 구성.  

### **Backend**  
- Spring Boot: SNS 플랫폼 서버 개발.  
  - JPA를 활용한 데이터베이스와의 연동.  
  - JWT 및 Spring Security로 보안 강화.  
- Flask: AI 제스처 컨트롤 서버 개발.  
  - MediaPipe로 손 제스처 인식.  

### **Database**  
- MySQL: 사용자, 게시물, 댓글 데이터 저장 및 관리.  

<br>
<br>
<br>

## 🛠️ 기능 개선 및 추가 아이디어  

### 1️⃣ **UI/UX 디자인 개선**  
- Material Design 도입으로 세련되고 일관된 사용자 경험 제공.  
- 다크 모드와 사용자 정의 색상 설정 추가.  
- 애니메이션 효과를 추가해 제스처 기능을 시각적으로 표현.  

### 2️⃣ **AI 제스처 인식 성능 향상**  
- 손 모양 데이터 다양성 확대 및 추가 학습.  
- 복합 제스처 지원: 양손 동작, 특정 시간 정지 동작 등.  
- 맞춤형 제스처 학습 기능: 사용자 고유 제스처 설정.  

### 3️⃣ **배포 및 접근성 강화**  
- Docker 및 AWS를 활용한 서버 배포로 글로벌 접근성 확보.  
- 로드 밸런싱과 CDN 적용으로 성능 최적화.  
- SSL 인증 및 보안 정책 강화.  

<br>
<br>
<br>

## 📷 프로젝트 이미지 및 데모  
### 로그인
![이미지-로그인](https://github.com/user-attachments/assets/7849b0c2-01c3-4979-bbd2-763f1650137b)

### 회원가입
![이미지-회원가입](https://github.com/user-attachments/assets/261827b6-821a-4d49-8577-7d23cc9d619b)

### 홈
![이미지-홈](https://github.com/user-attachments/assets/076c28b9-ac42-4b16-b0b7-6b9858d4d734)

### 홈 - 메뉴
![이미지-홈-메뉴](https://github.com/user-attachments/assets/664608af-b99d-47b1-b074-b84c8ea0c400)

### 게시물 상세
![이미지-게시물상세](https://github.com/user-attachments/assets/50ee6e61-d884-4c6b-952c-fd1472c23947)

### 게시물 추가
![이미지-게시물추가](https://github.com/user-attachments/assets/cc130ffe-35a4-468c-9416-179f97c3904c)

### 프로필
![이미지-프로필](https://github.com/user-attachments/assets/af283076-f62d-425c-b074-b83f64fc822b)

### AI 컨트롤
![이미지-AI제어](https://github.com/user-attachments/assets/4e9dad95-2ac4-41ef-8085-fc463599959b)

### 데모 영상
https://github.com/user-attachments/assets/317cf144-c4bf-425f-9a89-374ae39c3af7

<br>
<br>
<br>

## 📂 프로젝트 구조  

```plaintext
RISI/
├── backend/
│   ├── spring-boot/       # SNS 플랫폼 서버 코드
│   └── flask-ai/          # AI 제스처 컨트롤 서버 코드
├── frontend/
│   ├── react-sns/         # SNS 플랫폼 웹 클라이언트 코드
│   └── react-gesture/     # AI 제스처 컨트롤 웹 클라이언트 코드
├── database/
│   ├── mysql-schema.sql   # MySQL 데이터베이스 스키마
└── docker/
    ├── docker-compose.yml # Docker 설정 파일 (미구현)
```

<br>
<br>
<br>

## 📈 향후 계획  
1. **더 세분화된 AI 인식 기술 구현**  
   - 다양한 환경에서 손 제스처 인식 정확도를 높이는 기술 개발.  
2. **클라우드 인프라 확장**  
   - 글로벌 사용자 기반 확장을 위한 AWS S3 및 CloudFront 통합.  
3. **모바일 지원**  
   - 반응형 디자인 추가 및 모바일 기기 제스처 컨트롤 구현.  

<br>
<br>
<br>

## 🤝 기여 방법  
1. 이 저장소를 포크합니다.  
2. 새 브랜치를 생성합니다. (`git checkout -b feature/AmazingFeature`)  
3. 변경 사항을 커밋합니다. (`git commit -m 'Add some AmazingFeature'`)  
4. 브랜치에 푸시합니다. (`git push origin feature/AmazingFeature`)  
5. 풀 리퀘스트를 엽니다.  

<br>
<br>
<br>

## Thank you!
RISI 페이지를 방문해주셔서 감사합니다! 궁금한 사항 있으시면 말씀해 주세요!
