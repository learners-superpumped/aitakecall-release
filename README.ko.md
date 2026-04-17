# AI Take Call

> 당신의 전화기, 이제 프로그래밍 가능합니다. AI가 당신의 iPhone 번호로 Mac에서 전화를 걸고 받습니다.

**[웹사이트](https://aitakecall.com)** · **[최신 릴리스](https://github.com/learners-superpumped/aitakecall-release/releases/latest)** · **[English README](README.md)**

---

## AI Take Call이란?

iPhone 번호 그대로 AI가 전화를 걸고 받게 해주는 macOS 앱입니다. OpenAI, Gemini, ElevenLabs 중 원하는 AI에 본인 API 키를 연결해 쓰세요. 걸려오는 전화는 AI가 받고 실시간 transcript가 Mac에 표시되며, 필요할 땐 AI에게 시켜 iPhone 번호로 전화를 걸게 할 수도 있습니다.

- **기존 iPhone 번호 그대로.** USIM 교체, 번호이동, 추가 번호 발급 없습니다.
- **본인 API 키 사용(BYOK).** 앱은 무료이고 AI 비용은 공급자에게 직접 지불합니다.
- **연락처별 prompt·음성·기억.** 번호마다 다른 동작을 설정할 수 있습니다.
- **통화 중 MCP tool 호출.** Claude Desktop, Cursor처럼 MCP 도구를 전화 중에도 그대로 사용합니다.

제품 소개 전체는 **[aitakecall.com](https://aitakecall.com)** 에서 확인하세요.

## 요구 사항

- macOS 13 Ventura 이상
- 동일한 Apple ID로 로그인된 iPhone
- OpenAI, Google(Gemini), 또는 ElevenLabs API 키

## 다운로드

- **최신 릴리스:** [github.com/learners-superpumped/aitakecall-release/releases/latest](https://github.com/learners-superpumped/aitakecall-release/releases/latest)
- 설치 후에는 이 저장소의 `appcast.xml` 을 사용한 Sparkle 자동 업데이트로 앱이 스스로 업데이트됩니다.

## 이 저장소에 대하여

이 저장소는 앱 소스 코드가 **아닙니다**. AI Take Call 앱의 공개 배포 자산을 호스팅합니다.

| 파일 / 기능 | 용도 |
| --- | --- |
| `appcast.xml` | Mac 앱이 확인하는 Sparkle 자동 업데이트 피드 |
| `force-update.json` | 앱이 실행 시 확인하는 강제 업데이트 스위치 |
| GitHub Releases | 버전별 서명된 DMG 다운로드 |
| Issues 탭 | 공개 버그 제보 및 기능 요청 |

제품 자체는 **[aitakecall.com](https://aitakecall.com)** 을 확인해 주세요.

## 버그 제보 · 기능 요청

[GitHub Issues](https://github.com/learners-superpumped/aitakecall-release/issues) 를 공개 트래커로 사용하고 있습니다.

- **버그 제보** — macOS 버전, 앱 버전, 사용 중인 AI provider(OpenAI / Gemini / ElevenLabs), 재현 단계를 포함해 주세요. 로그·스크린샷이 있으면 큰 도움이 됩니다.
- **기능 요청** — 어떤 상황에서 필요한지, 현재 동작의 어떤 부분이 부족한지 설명해 주세요.
- **보안 이슈** — 공개 이슈로 등록하지 **말아** 주세요. Issue template의 보안 안내를 참고해 비공개 채널로 연락 부탁드립니다.

> [!WARNING]
> 공개 이슈에 API 키, 녹음 파일, 개인정보가 담긴 통화 transcript를 절대 붙이지 마세요. 로그를 첨부하기 전에 전화번호, 이름, 비밀 정보는 반드시 마스킹하세요.

## 링크

- 홈페이지 — [aitakecall.com](https://aitakecall.com)
- Releases — [github.com/learners-superpumped/aitakecall-release/releases](https://github.com/learners-superpumped/aitakecall-release/releases)
- Issues — [github.com/learners-superpumped/aitakecall-release/issues](https://github.com/learners-superpumped/aitakecall-release/issues)
- English README — [README.md](README.md)

## 라이선스

이 저장소의 릴리스 자산 및 피드 파일은 AI Take Call 애플리케이션과 함께 사용하기 위해 배포됩니다. All rights reserved.
