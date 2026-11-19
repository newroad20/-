# 내 LLM 프로젝트

## 구조

```mermaid
flowchart LR
    Start([입력]) --> W1[에이전트 A]
    Start --> W2[에이전트 B]
    W1 --> AG[취합]
    W2 --> AG
    AG --> OUT([출력])
```
