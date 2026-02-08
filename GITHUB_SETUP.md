# GitHub 업로드 및 배포 가이드

## 1. GitHub 저장소 생성 후 아래 명령어 실행

```bash
cd "C:\Users\USER\Desktop\BNBC"
git remote add origin https://github.com/YOUR_USERNAME/BNBC.git
git branch -M main
git push -u origin main
```

**주의**: `YOUR_USERNAME`을 본인의 GitHub 사용자명으로 바꿔주세요!

## 2. GitHub Pages 활성화

1. GitHub 저장소 페이지로 이동
2. 상단 메뉴에서 **Settings** 클릭
3. 왼쪽 사이드바에서 **Pages** 클릭
4. **Source** 섹션에서:
   - Branch: `main` 선택
   - Folder: `/ (root)` 선택
5. **Save** 클릭

## 3. 웹사이트 접속

몇 분 후 다음 URL로 접속 가능:
`https://YOUR_USERNAME.github.io/BNBC/`

## 문제 해결

- 이미지가 안 보이면: `assets/` 폴더 경로 확인
- CSS가 적용 안 되면: 파일 경로가 상대 경로인지 확인
- 404 에러가 나면: GitHub Pages가 활성화될 때까지 몇 분 기다리기
