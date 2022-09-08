# Commit-Rule
DAS 프젝에 사용될 커밋규칙입니다



### Commit Type

 > 다음은 커밋타입 형식입니다.

|CommitType|Description|
|------|----------------------|
|🗂 ::|파일 생성 및 구조 변경|
|🌧  ::|기능 업데이트|
|❌ ::|기능 삭제|
|🐛 ::|버그 수정|
|♻️ ::|코드 리펙토링|
|📝 ::|문서 작성 및 수정|
|⚙️ ::|프로젝트 세팅|
|🎮 ::|테스트 코드 추가|
|🛢 ::|새 버전 릴리즈 ( 커밋은 아니지만😏|
|🔀 ::|Merge or PR|

```json
CommitType :: (#issue number) Subject
```

모든 커밋은 위의 커밋 규칙을 지켜 작성한다.

Subject는 되도록이면 한글로 작성한다.

## 예시

```json
🗂 :: 페이지 생성
🌧 :: 댓글 알림 Response 작성
```

