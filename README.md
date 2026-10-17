# 코스모스 · 우주 탐험 퀴즈

우주에 관한 10개의 문제를 풀며 탐험하는 한국어 퀴즈 앱입니다.
정답마다 10점을 얻고, 해설과 최종 탐험 등급을 확인할 수 있습니다.
결과 복사, 키보드 탐색, 시스템 밝은/어두운 테마와 동작 줄이기를 지원합니다.

## 로컬 실행

저장소를 내려받은 뒤 `index.html`을 브라우저로 직접 열면 됩니다.
Windows PowerShell에서는 저장소 폴더에서 다음 명령을 실행하세요.

```powershell
Start-Process .\index.html
```

HTML, CSS, JavaScript, SVG가 모두 `index.html`에 포함되어 있어
패키지 설치, 빌드, 서버 또는 네트워크 연결이 필요하지 않습니다.
진행 상황은 메모리에만 저장되며 새로고침하면 초기화됩니다.
클립보드 사용이 차단되면 결과 화면의 읽기 전용 영역에서 직접 복사할 수 있습니다.

## GitHub Pages 배포

사이트 주소: <https://hoya3.github.io/space-quiz/>

저장소 **Settings → Pages → Build and deployment → Source**는
**GitHub Actions**로 설정합니다.
`.github/workflows/pages.yml`은 PR에서 정적 사이트 준비와 아티팩트 업로드를 확인하고,
`main` 브랜치에 변경 사항이 반영되면 GitHub Pages에 자동으로 배포합니다.
**Actions → GitHub Pages → Run workflow**에서 `main`을 선택해 수동 배포할 수도 있습니다.

별도 컴파일 과정 없이 `index.html`만 배포 아티팩트에 포함하므로
README나 저장소 설정 파일은 사이트에 게시되지 않습니다.
