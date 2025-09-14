# 샬롬리그 득점 사이트 (구글시트 연동, 새 레포 전용)

## 1) 새 레포 만들기
- GitHub → New repository → 예: `shalom-league`
- Public, Add a README (선택)

## 2) 파일 업로드
- 이 폴더의 `index.html` 과 `README.md` 를 레포에 업로드

## 3) 구글시트 준비
- A1: `이름`, B1: `득점`
- 예시 데이터 입력 후, **공유** → 링크가 있는 모든 사용자 **보기 가능**

## 4) CSV 주소 만들기
- 시트 URL의 `{시트ID}`와 탭의 `gid` 확인
- CSV 주소 형식
```
https://docs.google.com/spreadsheets/d/시트ID/export?format=csv&gid=시트GID
```
- `index.html`의 `SHEET_CSV_URL`에 위 주소를 넣고 커밋

## 5) GitHub Pages 켜기
- 레포 → **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: **main** / **/(root)** → Save
- 주소: `https://<계정명>.github.io/<레포명>/`

## 6) 사용법
- 모바일 구글시트 앱에서 득점만 수정 → 사이트에서 **새로고침** 버튼
