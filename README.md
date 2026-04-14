# Friend Search UI Test - 프로토타입 비교

친구 추가 화면의 다양한 UI 프로토타입을 비교하고, 레퍼런스를 확인할 수 있는 웹 페이지입니다.

## 🌐 온라인 URL

**https://miraekim-ctrl.github.io/TEST_friendsadd/**

위 링크로 바로 접속하여 확인하실 수 있습니다.

## 📁 다른 컴퓨터에서 사용하기

### 방법 1: GitHub에서 다운로드

1. 이 저장소를 다운로드합니다:
   ```bash
   git clone https://github.com/miraekim-ctrl/TEST_friendsadd.git
   ```

2. 폴더로 이동:
   ```bash
   cd TEST_friendsadd
   ```

3. `index.html` 파일을 브라우저에서 열기

### 방법 2: ZIP 파일 다운로드

1. GitHub 페이지에서 `Code` → `Download ZIP` 클릭
2. 압축 해제 후 `index.html` 파일을 브라우저에서 열기

## 📂 프로젝트 구조

```
TEST_friendsadd/
├── index.html              # 메인 페이지
├── A-1.png ~ A-6.png      # Type A 프로토타입 이미지
├── B-1.png ~ B-6.png      # Type B 프로토타입 이미지
├── C-1.png ~ C-6.png      # Type C 프로토타입 이미지
├── D-1.png ~ D-6.png      # Type D 프로토타입 이미지
├── E-1.png ~ E-6.png      # Type E 프로토타입 이미지
├── E-2-1.png ~ E-2-6.png  # Type E-2 프로토타입 이미지
├── F-1.png ~ F-16.png     # 최종안 프로토타입 이미지
├── 레퍼런스/               # Type별 레퍼런스 이미지
│   ├── Type A/
│   ├── Type C/
│   ├── Type D/
│   ├── Type E/
│   └── Type E-2/
└── 앱별_레퍼런스/          # 앱별 레퍼런스 이미지
    ├── Discord/
    ├── Lapse/
    ├── Locket/
    ├── Wechat/
    ├── X/
    ├── 듀오링고/
    └── 카카오톡/
```

## ✨ 주요 기능

### 1. 프로토타입 비교
- Type A ~ E-2: 6가지 다른 UI 스타일 비교
- 각 타입별 장단점 분석
- 클릭하여 상세 화면 확인

### 2. 레퍼런스 모음
- **Type별 레퍼런스**: 각 UI 타입에 해당하는 실제 앱 사례
- **앱별 레퍼런스**: 특정 앱의 다양한 화면 모음

### 3. 최종안 (Type E)
- LINE ID 화면 8개 (F-1 ~ F-8)
- Phone number 화면 8개 (F-9 ~ F-16)
- 총 16개 화면으로 전체 사용자 플로우 표시

## 🎨 디자인 스타일

- **Notion + Apple Keynote 스타일** 적용
- 깔끔한 타이포그래피와 여백
- 부드러운 애니메이션 효과
- 반응형 레이아웃

## 🔄 업데이트 방법

변경사항을 반영하려면:

```bash
# 변경사항 스테이징
git add .

# 커밋
git commit -m "변경 내용 설명"

# GitHub에 푸시
git push
```

푸시 후 1-2분 내에 GitHub Pages에 자동으로 반영됩니다.

## 💡 팁

- **캐시 문제**: 변경사항이 바로 안 보이면 `Cmd+Shift+R` (강력 새로고침)
- **로컬 테스트**: `index.html` 파일을 브라우저에서 바로 열어서 확인 가능
- **이미지 추가**: 파일명 규칙을 지켜서 추가 (예: F-17.png)

## 📝 작업 이력

- Notion + Keynote 스타일 디자인 적용
- 최종안 탭 추가 (LINE ID + Phone number 플로우)
- 세그먼트 컨트롤 스타일 탭 네비게이션
- 카드 높이 정렬 및 배경 개선
- 타이포그래피 및 여백 최적화
