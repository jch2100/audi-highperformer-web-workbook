# Audi High Performer 통합 웹교재

이 저장소는 수강생에게 공개할 완성본 `index.html`과 `downloads/`의 가상 실습 파일을 배포합니다. 원고와 이미지 작업 파일은 교안 폴더에 있습니다.

고객관리 실습은 **환경 설정 → 첫 고객 기록 → 기존 TXT 처리** 순서입니다. 제공 빈 CRM 엑셀을 직접 업로드하고, 가상 고객 C001의 후속 상담 TXT로 같은 고객 기록을 갱신합니다. 이후 선택 실습에서 15명 메모의 모호한 내용을 먼저 확인하고 일괄 반영합니다. 실제 파일 대조와 동일 파일 재처리에서 원본 보존·16행 유지·중복 없음이 확인됐습니다.

## 수정·배포 순서

1. 원고 폴더 `2026-10_audi-highperformer/draft/web_workbook_integrated/content/`의 Markdown을 수정합니다.
2. `build-web-workbook` 검증으로 `dist/index.html`을 다시 만듭니다.
3. `qa/package_crm_downloads.py`로 실습 다운로드 파일을 준비합니다. 검증된 `dist/index.html`과 `dist/downloads/`를 교안 폴더의 `output/Audi_High_Performer_통합_웹교재/`와 이 저장소에 복사합니다.
4. 공개 전 제목, 22개 탭, 35개 이미지, 두 ChatGPT 프로젝트 링크, 세 실습 파일 다운로드, 복사 버튼, 휴대전화 화면을 확인합니다. 고객관리 폴더 생성 전에 ‘3·플러그인 연결’에서 설치·Google 계정 연결·Work 채팅 선택을 준비합니다.
5. `main` 브랜치에 커밋하고 GitHub로 올리면 GitHub Pages가 자동으로 새 버전을 게시합니다.

수강생에게는 GitHub Pages 주소만 전달합니다. ChatGPT 프로젝트 링크의 접근 권한은 별도로 확인해야 합니다.
