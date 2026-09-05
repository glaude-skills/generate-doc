# generate-doc

Claude Code 플러그인 저장소. 스킬 하나만 담는다.

## 범위

`skills/generate-doc/SKILL.md` 가 유일한 산출물이다. 스크립트도 커맨드도 없다.

## 규칙

- 이 저장소의 모든 문서는 스킬 본문의 규칙을 그대로 지킨다. README가 AI 문체로 쓰여 있으면 스킬을 믿을 이유가 없다.
- SKILL.md를 고치면 서브에이전트로 검증한다. 스킬 없이 한 번(RED), 적용해서 한 번(GREEN). 출력이 실제로 달라지는지 눈으로 본다.
- 금지 표현 목록은 임의로 줄이지 않는다. 추가는 실제로 관찰한 출력에서 나온 것만.
- 버전은 `.claude-plugin/plugin.json` 과 `marketplace.json` 두 곳에 있다. 같이 올린다.
