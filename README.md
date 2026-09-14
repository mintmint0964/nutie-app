# Nutie Android Apps

누티와 누티스쿨의 Android 네이티브 셸 프로젝트입니다.

## 앱
- `nutie` — 누티 / `kr.nutie.app` / https://nutie.kr
- `nutieschool` — 누티스쿨 / `kr.nutieschool.app` / https://nutieschool.kr

두 앱 모두 기존 웹 서비스를 WebView로 유지하면서 HTML 이미지 파일 선택 요청을 Android 네이티브 Photo Picker로 연결합니다. 이미지 외 파일은 시스템 파일 선택기를 사용합니다.

## 급식사진 테스트
1. Android Studio에서 프로젝트를 엽니다.
2. 실제 Android 휴대폰을 연결합니다.
3. `nutie` 또는 `nutieschool` 실행 구성을 선택해 실행합니다.
4. 로그인 후 급식사진 자동업로드 화면으로 이동합니다.
5. `사진 선택`을 누릅니다.
6. Android Photo Picker에서 삼성 갤러리에서 편집한 최신 사진이 표시되는지 확인합니다.
7. 선택 후 웹 미리보기와 실제 업로드 파일이 동일한지 확인합니다.

## Play Console
릴리스 AAB는 각 모듈별로 따로 생성합니다.
- 누티: `nutie` 모듈의 signed Android App Bundle
- 누티스쿨: `nutieschool` 모듈의 signed Android App Bundle

처음 생성하는 업로드 키(keystore)는 이후 업데이트에도 필요하므로 반드시 안전하게 보관하세요.
