# claude-code-lecture

> **"실리콘밸리 엔지니어의 Claude Code"** 강의 실습 워크북.

이 repo에는 강의 실습 **가이드(exercises.md)** 와 학습자가 채워야 할 **빈 양식(templates/)** 만 들어 있습니다. 슬라이드·웹 페이지 같은 부가 자료는 별도 사이트로 분리되어 있습니다.

## 사용법

1. 우측 상단 **Fork** 버튼으로 본인 계정에 복제.
2. clone 후 첫 챕터로 이동:
   ```bash
   git clone https://github.com/<your-username>/claude-code-lecture.git
   cd claude-code-lecture/Part0-실리콘밸리_엔지니어의_하루/Ch01-강사소개_강의개요
   ```
3. `exercises/exercises.md`를 읽고, `exercises/templates/<양식>.md`를 **직접 열어** 본인 답으로 채워 commit.

## 구조

```
claude-code-lecture/
├── Part0-실리콘밸리_엔지니어의_하루/
│   ├── Ch01-강사소개_강의개요/
│   │   └── exercises/
│   │       ├── exercises.md
│   │       └── templates/my-level.md
│   └── Ch02-AI_Native_엔지니어로_일하기/
│       └── exercises/
│           ├── exercises.md
│           └── templates/
│               ├── my-workflow.md
│               └── habit-tracker.md
└── Part1-Claude_Code_마스터하기/
    ├── Ch01-Claude_Code_딥다이브/
    │   └── exercises/
    │       ├── exercises.md
    │       └── templates/CLAUDE.md
    ├── Ch02-Vibe_Coding의_본질과_한계/
    │   └── exercises/exercises.md          # 90분 챌린지 — templates 없음
    ├── Ch03-Agentic_Engineering_개론/
    │   └── exercises/
    │       ├── exercises.md
    │       └── templates/
    │           ├── CLAUDE.md
    │           └── .agent-rules.md
    ├── Ch04-Harness_Engineering_개론/      # 집필 중
    └── Ch05-실전_바이브코딩_테크닉/         # 집필 중
```

## 챕터 흐름

| 챕터 | 실습 핵심 | 작업 위치 |
|---|---|---|
| Part 0 · Ch01 | 자가진단 (10분) | 이 repo의 templates/my-level.md |
| Part 0 · Ch02 | 하루 워크플로우 매핑 + 1주일 습관 트래커 | 이 repo의 templates/ |
| Part 1 · Ch01 | Claude Code 정착시키기 | [example-vibe-project](https://github.com/jha0313/example-vibe-project) (별도 repo) |
| Part 1 · Ch02 | 90분 Vibe Coding 챌린지 (빈 디렉토리) | 학습자 로컬 `~/projects/vibe-90min/` |
| Part 1 · Ch03 | Ch02 vibe-90min에 Agentic 패턴 입히기 | Ch02 결과물 + 이 repo의 templates/ 참조 |

## 라이선스

학습 목적. 자유롭게 fork·수정 가능.
