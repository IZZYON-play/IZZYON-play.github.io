# IZZYON 공식 홈페이지 · SEO v1.7

기존 v1.6 사이트를 유지하면서 정적 HTML 독립 주소 30개(홈 1개 + 안내/목록 6개 + 상품 23개)로 전환한 배포본입니다.

- 5일 프로젝트: `/projects/dino/` 등 8개
- 간편/테마 활동지: `/worksheets/kimjang/` 등 13개(12종 + 가을 활동지)
- 무료 DAY1 체험판: `/free/dino-day1/`
- 5종 묶음: `/sets/best5/`
- 나머지 독립 목록/소개: `/projects/`, `/worksheets/`, `/free/`, `/playground/`, `/about/`, `/teachers/`

사이트맵에 30개의 URL을 넣고 페이지마다 고유한 제목·설명·canonical·OG·JSON-LD 기본 정보를 적용했습니다. 정적 HTML에 실제 상세페이지 콘텐츠가 포함되어 있으며, JavaScript는 기존 상호작용을 유지합니다.

## 기존 GitHub Desktop 저장소에 덮어쓰기
1. 현재 `IZZYON-play.github.io` 저장소 폴더를 백업하세요.
2. 이 배포본 ZIP의 **내용물**을 저장소 최상위에 복사하고 중복 파일을 덮어쓰세요. ZIP 자체나 상위 폴더를 복사하면 안 됩니다.
3. **이미 업로드한 `naver...html` 및 `google...html` 인증 파일과 `.git` 폴더는 삭제하면 안 됩니다.** 이 ZIP에 인증 파일이 없어도 기존 파일을 그대로 유지하면 됩니다.
4. GitHub Desktop에서 변경 파일을 확인한 뒤 `Commit to main` → `Push origin`을 누르세요.
5. 배포 후 `/projects/dino/`, `/worksheets/kimjang/`, `/sitemap.xml` 주소를 직접 확인하세요.
6. 네이버·구글 서치콘솔에 **기존 sitemap.xml 주소를 다시 제출하거나 재검사**하세요. 새 상품 URL은 색인·노출이 보장되지 않습니다.

## 주의
- 기존 해시 링크 `/#/projects/dino`는 가능하면 정규 경로로 변경해 주세요. 초기 접근용 호환 처리를 넣었습니다.
- 향후 상품 정보 업데이트 시 새 폴더의 index.html과 공통 app.js 내용이 서로 맞아야 합니다.
- 실제 브라우저 렌더링은 일부 실행 환경에서 제한될 수 있습니다. 배포 후 본인 PC와 휴대폰에서 확인하세요.
