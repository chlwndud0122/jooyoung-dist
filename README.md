# 주영서버 배포

주영런처가 읽는 설정과 배포 파일을 두는 곳입니다.

- `config.json`: 서버 주소와 모드 목록. 런처가 실행될 때마다 읽어 갑니다.
- Releases: 주영런처 설치 파일, 주영RPG 모드 jar

## 모드 추가 방법
- Modrinth 모드: `{ "modrinth": "슬러그" }`
- 직접 올린 jar: `{ "url": "Releases 파일 주소", "file": "파일이름.jar", "sha1": "해시" }`
