# Shinhan Vercel 프로젝트

Vercel을 통해 배포되는 간단한 HTML 프로젝트입니다.

## 배포 방법

### 방법 1: Vercel CLI 사용

1. Vercel CLI 설치:
```bash
npm i -g vercel
```

2. 프로젝트 디렉토리에서 배포:
```bash
vercel
```

3. 처음 배포 시 Vercel 계정 로그인 및 프로젝트 설정을 진행합니다.

### 방법 2: Vercel 웹 대시보드 사용

1. [Vercel](https://vercel.com)에 로그인
2. "New Project" 클릭
3. GitHub 저장소를 연결하거나 파일을 직접 업로드
4. 자동으로 배포됩니다

### 방법 3: GitHub 연동

1. 이 프로젝트를 GitHub 저장소에 푸시
2. Vercel 대시보드에서 GitHub 저장소를 연결
3. 자동 배포가 설정됩니다

## 파일 구조

- `index.html` - 메인 HTML 파일
- `vercel.json` - Vercel 배포 설정 파일

## 참고사항

- Vercel은 정적 HTML 파일을 자동으로 인식합니다
- `vercel.json` 파일은 선택사항이지만, 라우팅 설정에 유용합니다
- 변경사항을 푸시하면 자동으로 재배포됩니다
