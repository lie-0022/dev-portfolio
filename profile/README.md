<!-- TODO: 아래 두 문단은 초안. 본인 말투로 고쳐 쓸 것 -->
안녕하세요, 임예준입니다. AI 에이전트를 팀원처럼 두고 게임과 도구를 만듭니다.
요즘은 Unity로 로그라이크 덱빌더와 협동 멀티플레이 게임을 만들고, 그 과정에서 필요한 자동화 도구도 직접 짭니다.

## 만든 것

<a href="https://github.com/lie-0022/pokemon-battle-room"><img src="https://github.com/lie-0022/pokemon-battle-room/raw/main/promo.gif" width="240" align="right" alt="포켓몬 배틀룸 플레이 화면" /></a>

- **[포켓몬 배틀룸](https://github.com/lie-0022/pokemon-battle-room)** — 바탕화면 구석에서 혼자 굴러가는 방치형 포켓몬 오토배틀러. 151마리, 레이드, 온라인 랭킹까지. [Win/Mac 릴리스](https://github.com/lie-0022/pokemon-battle-room/releases/latest) · Electron
- **[A+ Mate](https://github.com/lie-0022/aplus-mate)** — 대학생 팀플 팀원 매칭 플랫폼. [라이브](https://aplus-mate-ten.vercel.app) · Next.js 14, Supabase
- **[Bonk](https://github.com/lie-0022/project-bonk)** — 3D 뱀파이어 서바이벌라이크. 학교 프로젝트, Claude Code 게임 스튜디오 워크플로우로 개발 · Unity 6
- **[My Butler](https://github.com/lie-0022/My_butler_FE)** — 개인 비서 앱. 백엔드 연동과 라벨 OCR 스캔 · React Native, Expo
- **화투 로그라이크** <sub>(비공개)</sub> — 화투로 만든 Slay the Spire식 덱빌더. 게임 로직을 엔진과 분리해서 헤드리스 시뮬로 밸런스를 검증 · Unity 6
- **쥐도 새도 모르게** <sub>(비공개)</sub> — 1~4인 협동 은신 약탈 게임 · Unity 6, Netcode for GameObjects
- **Fable 탐방** <sub>(비공개)</sub> — 사람들이 공유한 Claude Code 스킬·플러그인을 수집하고 안전등급을 매겨 설치까지 해주는 파이프라인. 393개 저장소 스캔 · Python

## AI랑 일하는 방식

- 프로젝트마다 `CLAUDE.md`로 에이전트 작업 규칙을 먼저 정해 둡니다
- Unity 에디터는 MCP로 연결해서 에이전트가 씬과 에셋을 직접 다루게 합니다
- 사람이 손으로 확인하기 어려운 건 시뮬레이션으로 확인합니다 (예: 덱빌더 런 완주율 측정)
- 외부에서 가져온 에이전트 자산은 실행 전에 정적 검사로 걸러냅니다

## 연락

<!-- TODO: 공개할 연락처로 교체 -->
[Email](mailto:EMAIL)
