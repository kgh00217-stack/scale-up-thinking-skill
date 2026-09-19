# Scale-Up Thinking Skill (스케일업 스킬)

저장소: https://github.com/kgh00217-stack/scale-up-thinking-skill

업무를 요청할 때마다 "이 요청을 AI 사이즈로 키우면 어떻게 될까?"를 먼저 물어보는 Claude Code 스킬입니다.

원래 요청(1배)에 더해, 범위·깊이·비교 대상을 넓힌 10배 버전과 조직/산업 수준으로 확장한 100배 버전을 함께 제안합니다. 사람이 고른 스케일로 작업을 실행합니다.

## 예시

**요청**: "대만 HR SaaS 시장 조사해줘"

- **1배**: 대만 HR SaaS 시장 현황과 주요 플레이어 정리
- **10배**: 시장 규모·성장률·주요 5사 비교 + 한국 시장과의 차이점 분석 + 진입 기회 평가
- **100배**: 아시아 8개국 HR SaaS 시장 비교 분석 + 시장별 진입 전략 + 포지셔닝 제안서

## 설치 방법

이 저장소의 `scale-up-thinking` 폴더를 그대로 내 컴퓨터의 Claude Code 스킬 폴더에 복사하면 됩니다.

```bash
git clone https://github.com/kgh00217-stack/scale-up-thinking-skill.git
cp -r scale-up-thinking-skill/scale-up-thinking ~/.claude/skills/
```

설치 후 Claude Code를 재시작하면 스킬이 자동으로 적용됩니다. 이 스킬은 "항상 작동"하도록 만들어져 있어서, 업무/분석/조사/콘텐츠 작성 요청을 하면 자동으로 스케일업 제안이 나옵니다.

끄고 싶을 때는 대화 중에 "스케일업 끄기" 또는 "그냥 해줘"라고 말하면 됩니다.

## 라이선스

자유롭게 가져다 쓰고 수정하세요.
