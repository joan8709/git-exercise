# Git 워크플로우 실습

VSCode에서 Git을 사용하여 코드를 수정하고 커밋하는 실습입니다.

## 실습 목표

1. VSCode Source Control 사용법 익히기
2. Git add, commit, push 워크플로우 실습
3. 변경 사항 확인(diff) 및 스테이징 연습

## 시작하기

### 1. 저장소 Fork하기

1. 제공한 GitHub 저장소 링크 접속
2. 우측 상단 **Fork** 버튼 클릭
3. 본인 계정에 저장소가 복사됩니다

### 2. VSCode에서 Clone하기

```
1. VSCode 열기
2. Ctrl+Shift+P (Mac: Cmd+Shift+P) → "Git: Clone" 입력
3. Fork한 저장소 URL 붙여넣기
4. 저장할 폴더 선택
5. "Open" 클릭하여 프로젝트 열기
```

## 실습 과제

### Task 1: calculate_sum 함수 구현

`exercise.py` 파일을 열고 `calculate_sum` 함수를 완성하세요.

```python
def calculate_sum(a: int, b: int) -> int:
    # TODO: 두 수의 합을 반환하는 코드를 작성하세요
    pass
```

완성 후:
1. 파일 저장 (Ctrl+S)
2. Source Control 패널 열기 (Ctrl+Shift+G)
3. 변경된 파일 옆 [+] 클릭 (스테이징)
4. 커밋 메시지 입력: `feat: calculate_sum 함수 구현`
5. Commit 버튼 클릭

### Task 2: calculate_average 함수 구현

같은 방식으로 `calculate_average` 함수를 완성하고 커밋하세요.

커밋 메시지: `feat: calculate_average 함수 구현`

### Task 3: find_max 함수 구현

`find_max` 함수를 완성하고 커밋하세요.

커밋 메시지: `feat: find_max 함수 구현`

### Task 4: Push하기

모든 커밋을 GitHub에 Push합니다.

```
1. 하단 상태바에서 🔄 Sync 버튼 클릭
   또는 Source Control → ... → Push
```

## 완료 확인

- [ ] calculate_sum 함수 구현 및 커밋
- [ ] calculate_average 함수 구현 및 커밋
- [ ] find_max 함수 구현 및 커밋
- [ ] GitHub에 Push 완료
- [ ] 모든 테스트 통과

## 도움말

### 커밋 메시지 형식

```
feat: 새 기능 추가
fix: 버그 수정
docs: 문서 수정
refactor: 코드 리팩토링
test: 테스트 추가/수정
```
