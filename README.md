# gongsitrack-packs

공시트랙 앱이 내려받는 콘텐츠 팩 배포 폴더입니다 (GitHub Pages).

- `manifest.json`: 팩 목록(id, version, file, sha256). 앱은 설치본보다 새 버전만 받고 sha256 을 검사합니다.
- 팩 파일과 `images/` 는 파이프라인의 `pipeline/data/packs` 를 그대로 올립니다.

현재는 업데이트 경로 시험용 빈 팩만 있습니다. 문제 팩은 기출 이용 조건을 확인한 뒤 올립니다.
