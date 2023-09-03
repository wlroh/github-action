# github-action

### Main 브랜치가 아닌데 과연 푸시 시 별도의 브랜치 설정을 안하면 어떤 브랜치를 체크아웃받을까?

- Triggerd 된 브랜치를 체크아웃 받고 있음.
- 테스트 브랜치: test/workflow-ex2

### Triggerd 조건에서 push 일 때 특정 브랜치일때만 Trigger가 가능할까?

```
on: 
  push:
    branches:
      - main
```
위의 설정을 통해 특정 브랜치에만 트리거 조건을 걸 수 있음.
