# homepage

## API Key 관리
- 외부 API 키는 `.env` 파일에 보관하세요.
- `.env` 파일은 이미 `.gitignore`에 추가되어 있으므로 깃허브에 노출되지 않습니다.
- 예시:
  ```env
  GEMINI_API_KEY=여기에_발급받은_API_KEY_입력
  ```

## Gemini API 연동 예시
- 사용 모델: Gemini 1.5 flash
- 모바일 중심의 웹앱으로 개발되어 있습니다.
- API 연동 시, 환경 변수에서 키를 불러와 사용하세요.

