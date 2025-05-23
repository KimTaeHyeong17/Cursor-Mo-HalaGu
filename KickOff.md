생성형 AI 스터디 10주 커리큘럼

# 📚 생성형 AI x 개발자 스터디 커리큘럼 목차 (10주)

1. **1주차: 생성형 AI 개요 및 최신 동향**
2. **2주차: OpenAI의 GPT 모델과 API 활용**
3. **3주차: Anthropic Claude 이해 및 활용**
4. **4주차: AI 코딩 도구 (Cursor) 실습**
5. **5주차: 프롬프트 엔지니어링과 LLM 애플리케이션 개발**
6. **6주차: MCP (Model Context Protocol) 이해 (1부)**
7. **7주차: MCP 실습 및 사이드 프로젝트 적용 (2부)**
8. **8주차: 개인 사이드 프로젝트 기획 및 설계**
9. **9주차: 개인 프로젝트 개발 및 중간 점검**
10. **10주차: 최종 발표 및 쇼케이스 + 스터디 회고**

## 📌 부록
- 추천 학습 자료 정리
- 사이드 프로젝트 아이디어 참고 링크
- MCP 관련 예제 및 구현 참고 리포지토리 목록

1주차: 생성형 AI 개요 및 최신 동향

왜 이걸 공부해야 하는가? 최근 ChatGPT를 비롯한 생성형 AI의 등장으로 개발 생산성과 서비스 혁신에 큰 변화가 나타나고 있습니다. 2024년 개발자 설문에 따르면 76%의 응답자가 이미 개발 과정에서 AI 도구를 사용 중이거나 사용할 계획이라고 할 정도로 보편화되고 있습니다 ￼. 생성형 AI는 텍스트, 코드, 이미지 등 새로운 콘텐츠를 만들어내는 기술로 정의되며 ￼, 이를 이해하는 것은 향후 개발자의 핵심 역량이 될 것입니다. 따라서 첫 주에는 생성형 AI의 전반적인 개념과 트렌드를 파악하여, 앞으로 무엇을 배우게 될지 큰 그림을 얻습니다.

학습 주제 및 목표:
	•	생성형 AI의 개념과 유형 이해 (텍스트 생성, 이미지 생성 등)
	•	대규모 언어 모델(LLM)의 기본 원리와 한계 점검 (예: 학습 데이터 기반 확률적 생성, 환각 현상 등)
	•	ChatGPT(OpenAI), Claude(Anthropic) 등 대표적인 생성형 AI 도구 소개 및 비교
	•	스터디 전체 커리큘럼 개요 파악 및 향후 학습에 대한 기대 설정

실습 과제:
	•	ChatGPT 또는 Bing Chat 등의 공개된 챗봇을 직접 사용해보기: 간단한 질문을 입력하고 생성형 AI의 응답 체험
	•	OpenAI의 ChatGPT와 Anthropic Claude 같은 서로 다른 모델에 동일한 질문을 해보고 응답 비교
	•	(선택) 간단한 프롬프트를 통해 코드 또는 문서 요약 생성해보기 – 생성형 AI의 가능성과 한계를 직접 느껴보기

논의할 질문:
	•	생성형 AI를 처음 사용해본 소감은 어떤가요? 기대했던 대로 동작했나요?
	•	이러한 도구들이 개발자의 업무 방식에 어떠한 변화를 가져올 것으로 예상하나요?
	•	생성형 AI의 한계나 우려 사항(예: 잘못된 정보 생성, 윤리적 문제)에 대해 자유롭게 의견을 나눠보세요.

참고 자료:
	•	McKinsey: What is generative AI? – 생성형 AI의 정의와 영향 ￼
	•	Stack Overflow 개발자 설문 2024 – AI tools in the dev process (76% 사용/계획) ￼
	•	위키피디아: Generative artificial intelligence – 생성형 AI 개요 ￼
	•	OpenAI 블로그: ChatGPT 발표 (2022) – ChatGPT 등장으로 본 생성형 AI 트렌드 (읽어보고 토론)

⸻

2주차: OpenAI의 GPT 모델과 API 활용

왜 이걸 공부해야 하는가? OpenAI의 GPT 시리즈(예: GPT-3.5, GPT-4)는 현재 가장 널리 활용되는 생성형 AI 모델로, 다양한 애플리케이션에서 활용되고 있습니다. 이미 전 세계적으로 300개 이상의 애플리케이션이 OpenAI API를 통해 GPT-3 모델을 통합했고 ￼, 많은 기업들이 이 기술을 서비스에 접목하고 있습니다. OpenAI API를 배우면 최첨단 언어 모델을 내 프로젝트에 쉽게 연결할 수 있으며 ￼, 이를 통해 챗봇, 자동 문서 요약, 코드 생성 등 다양한 기능을 구현할 수 있습니다. 이번 주에는 OpenAI의 플랫폼과 API 사용법을 익혀서 향후 실습과 프로젝트의 기반을 다집니다.

학습 주제 및 목표:
	•	OpenAI 플랫폼 소개 및 회원가입, API 키 발급 방법 익히기
	•	GPT-3.5 vs GPT-4 모델 특성 비교 및 활용 사례 이해 (예: GPT-4는 더 높은 응답 품질 제공 등)
	•	OpenAI API를 통한 기본적인 프롬프트-응답 흐름 이해: Prompt/Completion, Chat Completion 엔드포인트 사용법
	•	간단한 파이썬 예제를 통해 OpenAI API 호출 실습 (예: 질문에 대한 답변 생성, 간단한 요약 만들기)
	•	(심화) OpenAI의 기능 호출(Function Calling) 기능 개념 알아보기 – 모델이 외부 함수를 호출하도록 하는 방법 개괄
	•	OpenAI 사용상의 유의사항: 토큰 비용 개념, 요청 제한, 컨텐츠 필터 정책 소개

실습 과제:
	•	OpenAI API 가입: OpenAI 개발자 계정을 만들고 API 키를 발급받습니다 (무료 크레딧 활용).
	•	Playground 활용: OpenAI 웹 Playground에서 GPT-3.5 모델로 간단한 프롬프트 실험 – 예를 들어 한 문단의 글을 요약시키거나 번역시키기. 결과를 팀과 공유.
	•	API 호출 코드 작성: 선택한 언어(Python 권장)에서 OpenAI API를 호출하는 간단한 스クリپ트 작성. 예를 들어 사용자의 질문을 받아 GPT-3.5의 답변을 출력하는 콘솔 프로그램.
	•	응답 비교: 같은 질문을 GPT-3.5와 GPT-4에 호출(가능하다면)하여 응답 시간과 내용 비교. 차이점을 기록.
	•	(선택 과제) OpenAI 튜토리얼 따라하기: OpenAI에서 제공하는 예제 코드를 따라 챗봇 또는 간단한 애플리케이션 만들어보기 ￼.

논의할 질문:
	•	OpenAI API를 직접 사용해보니 어떤가요? 구현상의 어려움은 없었나요?
	•	GPT-3.5와 GPT-4의 응답을 비교했다면, 품질이나 스타일 면에서 어떤 차이가 있었나요? 비용 대비 어느 쪽을 프로젝트에 활용하고 싶은지 이야기해보세요.
	•	OpenAI 모델을 활용하면서 떠오른 서비스 아이디어나 사용 사례가 있나요?
	•	API를 사용하며 생긴 궁금증 (예: 추가로 Fine-tuning을 해보고 싶다거나, 응답이 잘 안될 때 조언 등)을 공유하세요.

참고 자료:
	•	OpenAI 공식 문서: Quickstart Tutorial – OpenAI API를 처음 사용하는 개발자를 위한 빠른 시작 가이드 ￼
	•	OpenAI Cookbook (GitHub) – OpenAI API 사용 예제와 베스트 프랙티스 모음 ￼
	•	DataCamp 튜토리얼: Beginner’s Guide to OpenAI API – OpenAI API로 텍스트 생성 예제 및 모범 사례 ￼ ￼
	•	DeepLearning.AI 단기강좌: ChatGPT Prompt Engineering for Developers – OpenAI API와 프롬프트 기법을 배우는 무료 강의 ￼
	•	OpenAI 기능 호출 가이드 – 함수 호출(Function Calling)을 통해 외부 도구 연동 방법 (OpenAI 블로그, 2023년 6월)

⸻

3주차: Anthropic Claude 이해 및 활용

왜 이걸 공부해야 하는가? Anthropic의 Claude는 OpenAI GPT와 더불어 주목받는 대규모 언어 모델로, GPT에 비해 맥락을 매우 많이 유지할 수 있는 능력으로 유명합니다. Claude 2 모델은 약 100,000 토큰(약 7.5만 단어)의 거대한 컨텍스트 윈도우를 지원하여 아주 긴 문서도 한 번에 처리할 수 있습니다 ￼. 또한 Anthropic은 헬퍼/하armless AI 원칙에 따라 Claude를 설계하여, 안전하고 일관된 응답을 제공하는 것을 목표로 합니다. 다양한 모델을 학습함으로써 우리는 각 모델의 강점과 약점을 이해하고, 향후 프로젝트에 가장 적합한 도구를 선택할 수 있습니다. 이번 주에는 Claude의 특징과 API 활용법을 익혀 OpenAI 모델과 비교해봅니다.

학습 주제 및 목표:
	•	Anthropic 및 Claude 소개: Anthropic의 배경, 헌법 기반 AI(Constitutional AI) 개념 간략 소개
	•	Claude 2의 주요 특징: 100k 토큰 컨텍스트 지원, 높은 추론 능력, 긴 답변 작성 등에 강점 ￼
	•	Claude 접근 방법: claude.ai 웹 인터페이스를 통한 사용과 Anthropic API 활용 방법
	•	Claude API 키 발급 및 무료 등급 안내: 개발자 콘솔 가입 및 월 $10 상당 무료 사용 한도 설명 ￼
	•	Claude API 호출 기본 실습: OpenAI API와의 유사점 및 차이점 (엔드포인트, 프롬프트 포맷 등)
	•	OpenAI GPT 모델과 Claude 모델의 응답 비교: 같은 질문에 대한 응답 스타일, 세부사항, 오류 경향 비교 분석

실습 과제:
	•	Claude 웹 체험: claude.ai 웹사이트에 가입하여 Claude와 대화해보기. 예를 들어 지난주 GPT에 했던 동일한 질문들을 Claude 2에게 물어보고 답변 수집.
	•	응답 비교 노트: Claude와 GPT의 답변을 내용, 길이, 친절도 측면에서 비교하여 느낀 점 기록. 어떤 점에서 Claude가 더 나았는지 혹은 부족했는지 정리하세요.
	•	Claude API 사용: Anthropic 개발자 계정을 만들고 API 키를 받아본 후(무료 티어 이용), 간단한 Python 스크립트로 Claude API 호출 실습. (힌트: OpenAI API와 유사한 REST 방식, 차이점은 헤더와 엔드포인트임 ￼)
	•	예를 들어 사용자 질문을 보내 Claude의 답변을 출력하는 코드 작성.
	•	Claude의 모델 버전(Instant vs. Standard) 선택 옵션과 최대 토큰 파라미터 등을 실험해보기.
	•	Slack 통합 (선택): Claude를 Slack 봇으로 초대하여 팀 채널에서 활용해보기 (Anthropic이 제공하는 Slack 연동 이용). Slack을 통해 Claude를 사용할 때의 편의성 경험.

논의할 질문:
	•	Claude를 사용해본 첫인상은 어떠했나요? OpenAI GPT와 비교하여 응답 어조나 형식에서 차이가 있었나요?
	•	Claude의 장점으로 느낀 부분(예: 긴 문맥 유지 능력, 응답의 논리 전개 등)은 무엇이고, 단점이나 아쉬운 부분은 무엇인가요?
	•	실제 프로젝트에서 어떤 경우 Claude를 선택하고자 하나요? (예: 매우 긴 입력이 필요한 경우 Claude가 유리 등)
	•	Claude API를 쓰면서 기술적인 어려움은 없었나요? (예: 문서 부족, 응답 속도 등) 이에 대한 대응 방법이나 팁을 함께 논의해봐요.

참고 자료:
	•	Ian Wootten 블로그: Claude 2 vs ChatGPT 비교 – Claude 2의 100K 토큰 맥락 크기와 특징 소개 ￼
	•	Anthropic 공식 발표: Claude 2 공개 – Claude의 성능과 용도 소개 (컨텍스트 윈도우, 응답 예시 등) ￼
	•	Anthropic 개발자 문서: Getting Started – Claude API 키 생성 및 콘솔 사용법 ￼
	•	Nightfall AI 블로그: Claude API Key 사용 가이드 – API 호출 방법과 헤더 설정 등 실용 정보 ￼
	•	Anthropic 가격정책(Acorn 설명): Claude 무료 티어 및 사용 한도 소개 ￼
	•	Reddit 토론: Claude vs ChatGPT 사용자 비교 경험 (모델 활용 팁 및 한계에 대한 커뮤니티 논의)

⸻

4주차: AI 코딩 도구 (Cursor) 활용

왜 이걸 공부해야 하는가? 생성형 AI는 자연어 처리뿐만 아니라 프로그래밍 생산성 향상에도 큰 기여를 하고 있습니다. AI 코딩 도구를 사용하면 개발자가 코드 작성 및 이해에 들이는 시간을 크게 줄일 수 있으며, 실제 연구에 따르면 GitHub Copilot과 같은 AI 페어 프로그래밍 도구 사용 시 코딩 작업이 최대 55% 빨라지는 효과가 있었습니다 ￼. 이번 주에는 VS Code 기반의 AI 코딩 도구인 Cursor를 중심으로, 코드 자동완성 및 생성 기능을 익혀봅니다. Cursor를 사용함으로써 반복적인 코딩 작업을 줄이고, 더 높은 수준의 설계와 로직에 집중하는 개발 습관을 기르는 것이 목표입니다.

학습 주제 및 목표:
	•	Cursor AI 코드 에디터 소개: VS Code를 기반으로 한 AI 통합 개발환경 소개 (설치 및 기본 사용법)
	•	Cursor의 주요 기능: AI 코드 자동완성, 자연어로 코드 명령, 오류 감지 및 수정 제안, 주석/문서 생성 ￼ ￼
	•	Cursor에 통합된 모델: 기본 무료 버전의 모델 (GPT-3.5 기반) vs Pro 버전 (GPT-4 또는 Claude-3.5 Sonnet 활용) ￼ ￼
	•	실습을 통한 Cursor 사용 방법 습득: 코드 작성 중 자동 완성 사용해보기, 함수를 자연어로 설명시켜보기, 리팩토링 제안 받아보기 등
	•	다른 AI 코딩 도구와의 비교: GitHub Copilot 등과 Cursor의 기능 비교표 살펴보기 (필요 시)
	•	AI 코드 도구 사용 시 모범 사례: 무분별한 수용보다는 코드 검토 습관, 보안 민감한 코드 업로드 주의 등 토의

실습 과제:
	•	Cursor 설치: 본인 PC에 Cursor 에디터를 설치하고 기존에 작성하던 작은 프로젝트 또는 연습용 코드를 불러오기. (VS Code와 유사한 UI이므로 친숙한지 확인)
	•	코드 자동완성 체험: 몇 가지 함수 구현을 Cursor의 자동완성에 의존해 구현해보기. 예를 들어 “문자열이 회문인지 확인하는 함수”를 주석으로 설명 입력하고 코드 완성 제안을 받기. Cursor가 제안한 코드를 실행하여 제대로 동작하는지 검증.
	•	자연어 코드 명령: Cursor에 내장된 자연어 명령으로 리팩토링 시도 – 예: “이 함수의 복잡도를 줄여줘” 또는 “이 코드에 대한 단위 테스트 작성해줘” 등의 명령을 영어로 입력하고 Cursor의 행동 관찰. 결과물을 코드 리뷰 관점에서 평가.
	•	버그 수정 도움: 의도적으로 간단한 버그가 있는 코드를 작성한 뒤 Cursor에게 문제를 설명하고 수정안을 받아보기. 얼마나 정확히 이슈를 찾아주는지 확인.
	•	결과 정리: Cursor를 사용하면서 생성된 코드와 직접 작성한 코드의 품질을 비교하거나, Cursor의 제안 중 개선된 점/잘못된 점을 정리하여 다음 모임 때 공유할 준비.

논의할 질문:
	•	Cursor를 실제 코딩에 활용해보니 개발 흐름에 어떤 변화가 있었나요? 생산성이 향상되었다고 느끼는지, 아니면 방해가 되는 부분도 있었나요?
	•	Cursor가 잘하는 작업과 부족한 작업은 무엇이었나요? (예: 단순 반복 코드 생성은 잘하지만, 복잡한 알고리즘 구현은 미흡했다 등)
	•	AI가 제안한 코드에서 오류나 버그를 발견했다면 어떻게 대응했나요? 이러한 경험을 토대로 AI 코딩 보조를 사용할 때 개발자가 주의해야 할 점은 무엇일까요?
	•	회사나 팀 프로젝트에서 이러한 AI 코딩 도구를 도입한다면 고려해야 할 점은 무엇일까요? (예: 보안, 라이선스, 개발자 역량 향상/저하 문제 등)

참고 자료:
	•	Daily.dev 블로그: Cursor AI 소개 – Cursor의 기능과 혜택 (VS Code 기반, GPT-4/Claude 사용, 페어 프로그래머 역할) ￼ ￼
	•	Cursor 공식 사이트/문서 – 설치 방법 및 기본 사용법 가이드
	•	GitHub Copilot 연구 (2022): 개발자 생산성 향상 55% – AI 코드완성 효과에 대한 GitHub 연구 결과 ￼
	•	Reddit: Cursor AI 사용자 후기 – Cursor를 활용한 실제 코딩 경험과 팁 (한글 후기 찾아볼 것)
	•	YouTube: Cursor AI 튜토리얼 – 주요 기능 시연 영상 (Cursor의 자연어 명령 시연 등)

⸻

5주차: 프롬프트 엔지니어링과 LLM 애플리케이션 개발

왜 이걸 공부해야 하는가? 효과적으로 프롬프트를 설계하는 능력은 생성형 AI 활용의 성패를 좌우할 정도로 중요합니다. 같은 모델이라도 어떻게 질문이나 지시를 하는지에 따라 결과 품질이 크게 달라지며, 이를 다루는 기술을 프롬프트 엔지니어링이라고 부릅니다. 또한 개별 API 사용 경험을 바탕으로 이제는 실제 애플리케이션에 생성형 AI를 통합하는 방법을 알아야 합니다. 이번 주에는 그동안 익힌 OpenAI/Claude 등의 모델을 활용해 작은 통합 프로젝트를 만들어 보면서, 프롬프트 디자인, 시스템 아키텍처, 그리고 외부 도구 연계에 대한 이해를 높입니다. 이를 통해 최종 프로젝트를 구현할 준비를 갖추는 것이 목표입니다.

학습 주제 및 목표:
	•	프롬프트 엔지니어링 기본 원칙: 명확성과 구체성, 맥락 제공 등 좋은 프롬프트 작성법 배우기 (예: 모델에게 단계별로 생각하도록 지시하기, 원하는 답 형식 명시하기 등)
	•	프롬프트 튜닝 기법: Few-shot 예시 제공을 통한 모델 성능 향상, 시스템 메시지를 활용한 역할 부여 등 실전 팁 공유
	•	LLM 응답의 한계 다루기: 모델 환각 대응법 (답변 검증하기, 중요한 정보는 반복 확인 등), 민감한 요청에 대한 정책 설정
	•	간단한 LLM 애플리케이션 설계: 사용자 입력을 받아 LLM이 처리하고 결과를 제공하는 파이프라인 구상
	•	외부 지식 연계 방법: 프롬프트 내에 예측에 필요한 지식 넣기 vs. 도구 활용하기 (예: OpenAI 함수 호출로 계산 기능 연결, 웹 검색 API와 연계 등 개념 소개)
	•	(선택 심화) LangChain 등 LLM 프레임워크 소개: 복잡한 멀티스텝 대화나 추론 체인을 구현하는 도구 개괄 (필요시 간단 데모)

실습 과제:
	•	프롬프트 실험: 지난 주까지 활용한 OpenAI 또는 Claude API를 통해, 동일한 문제에 대해 프롬프트를 여러 방식으로 작성해보기. 예를 들어 “주어진 텍스트 요약” 작업을 할 때:
	•	자세한 지시 없이 요약 요청 → 결과 확인
	•	원하는 요약 형식과 단계별 출력 지시 포함 → 결과 비교
	•	요약 전에 중요한 키워드 목록을 추출하도록 두 단계로 프롬프트 작성 (체인 구성)
각 실험별로 결과 품질을 비교하고 어떤 프롬프트가 가장 효과적이었는지 논의 준비.
	•	간단한 챗봇 구축: 선택한 언어(Python 등)로 콘솔 기반 챗봇 프로그램 작성. 사용자의 질문을 받아, OpenAI 또는 Claude API로 답변을 얻어 출력. 지속적인 대화를 위해 이전 문맥을 저장하여 프롬프트에 포함시키는 로직 추가. (예: 최근 3회의 Q&A를 프롬프트 맨 앞에 포함)
	•	함수 호출 활용(선택): OpenAI API의 함수 호출 기능을 지원한다면, 간단한 계산기 함수를 정의하고 모델이 산술 질문 시 함수 호출을 통해 답하도록 시도. (예: “10분 후 시간은?” 질문 -> 함수가 시간 계산)
	•	응용 미니 프로젝트: 각자 작은 아이디어를 하나 선택하여 LLM을 활용한 미니 애플리케이션 제작해보기. 예시 아이디어:
	•	영화 추천 봇: 사용자 선호를 입력받아 영화를 추천 (사전에 준비한 영화 데이터 일부를 프롬프트에 포함)
	•	코드 리뷰 어시스턴트: 사용자가 입력한 코드 조각에 대한 개선점 피드백 생성
	•	문서 요약 웹앱: 간단한 웹 인터페이스에서 텍스트를 업로드하면 요약해주는 서비스 (streamlit 등 사용 가능)
완성도는 높지 않아도 되므로 프로토타입을 빠르게 만들어보고, 동작 과정을 이해하는 데 중점.

논의할 질문:
	•	동일한 작업에 대해 프롬프트를 다르게 줘본 실험에서 어떤 방식이 가장 좋았나요? 모델의 응답 품질이 프롬프트 설계에 따라 어떻게 달라졌는지 구체적 사례를 들어보세요.
	•	애플리케이션을 만들면서, API 응답 시간을 다루거나 오류를 처리하는 등 통합 측면에서 어려운 점은 무엇이었나요?
	•	LLM을 실제 사용자-facing 어플리케이션에 넣으려 할 때 고려해야 할 추가 사항은 무엇이 있을까요? (예: 응답 검열/필터링, 비용 모니터링, 캐싱 등)
	•	(심화) LangChain 같은 프레임워크를 사용해본 분이 있다면 경험을 공유해주세요. 이런 도구가 없다면 직접 구현해야 할 부분은 어떤 것들이 있을지 토의해봅니다.
	•	각자 만들어본 간이 프로젝트를 시연하면서 피드백: 아이디어를 더 발전시키려면 어떤 데이터를 추가하거나 어떤 프롬프트를 보강하면 좋을까요?

참고 자료:
	•	DeepLearning.AI 강의 노트: 프롬프트 엔지니어링 모범 사례 2가지 원칙 – 효과적인 프롬프트 작성의 핵심 원칙 정리 ￼
	•	OpenAI 문서: Best Practices for Prompting – GPT 활용을 위한 프롬프트 가이드 (OpenAI Cookbook 중 해당 장)
	•	Learn Prompting (무료 공개 자료) – 다양한 프롬프트 기법을 단계별로 배우는 커리큘럼
	•	DataCamp 블로그: 5 Generative AI Projects (예제) – 이미지 편집, 챗봇 등 간단한 생성형 AI 프로젝트 아이디어 소개 ￼
	•	LangChain 공식 문서 – LLM 체인을 구성하는 방법과 예제 (챗봇, QA시스템 구현 등)
	•	Microsoft Guidance 등 프롬프트 흐름 제어 라이브러리 – 고급 프롬프트 엔지니어링 도구 참고

⸻

6주차: Model Context Protocol (MCP) 이해 (1부)

왜 이걸 공부해야 하는가? 지금까지 우리는 개별 AI 모델을 프롬프트로 제어하고, 코드나 API로 통합하는 방법을 배웠습니다. 그러나 모델 자체의 한계 중 하나는 사전에 학습된 정보 외의 최신 데이터나 사내 데이터베이스 등에 직접 접근하지 못한다는 점입니다. 예를 들어 우리의 AI 챗봇이 회사의 최신 문서를 참고하거나 사용자의 파일을 열람하도록 만들려면 어떻게 해야 할까요? 이를 해결하기 위한 표준 솔루션이 바로 Anthropic이 주도하는 **MCP (Model Context Protocol)**입니다. MCP(모델 컨텍스트 프로토콜, 일명 모델 기능 프로파일)는 AI 보조助手를 콘텐츠 저장소, 비즈니스 도구, 개발환경 등 외부 시스템의 데이터와 연결해주는 개방형 표준입니다 ￼. 마치 AI 분야의 “USB-C 포트”처럼 한 가지 규격으로 다양한 도구를 연결하는 것을 목표로 하고 있습니다 ￼. 이번 주와 다음 주 2주에 걸쳐 MCP의 개념과 활용법을 공부함으로써, 향후 우리 사이드 프로젝트에 모델+툴 통합 기능을 구현할 수 있는 밑바탕을 만들겠습니다.

학습 주제 및 목표:
	•	MCP 등장 배경과 핵심 개념 이해: AI 모델이 외부 데이터에 접근하기 어려운 문제와 MCP가 이를 어떻게 해결하는지 원리 학습 ￼
	•	MCP 아키텍처: MCP 서버(데이터 소스를 표준화된 방식으로 노출)와 MCP 클라이언트(AI 모델 측 인터페이스)의 개념 파악
	•	주요 구성요소: MCP 스펙, SDK(언어별 라이브러리) 소개 – Python, Java 등 공식 SDK 활용 가능 ￼
	•	MCP 활용 사례 개요: 현재 공개된 MCP 서버 예시 살펴보기 (예: 구글 드라이브, Slack, GitHub, Postgres DB 등 인기 시스템에 대한 MCP 서버 구현 제공됨 ￼)
	•	업계 동향: Block, Replit 등 초기 MCP 도입 기업 사례 ￼; Microsoft 등에서의 SDK 협력 현황 (예: C# SDK 개발 참여)
	•	(개념 실습 준비) 간단한 MCP 상호작용 흐름 시뮬레이션: Claude Desktop에서 로컬 파일 시스템 MCP 서버를 사용하는 예시 흐름을 읽어보고 이해하거나, pseudo-code로 MCP 클라이언트-서버 통신 과정 따라가기

실습 과제:
	•	MCP 공식 문서 정독: Anthropic이 공개한 Introducing the Model Context Protocol 블로그 글 읽기 ￼ ￼. 각자 글의 다른 부분을 담당하여 요약: 한 명은 MCP 개념과 목표 부분, 한 명은 MCP 서버/클라이언트 기술 세부, 다른 한 명은 이미 공개된 MCP 서버 예시 부분 등. 다음 모임에서 각자 이해한 내용을 발표.
	•	MCP 용어 정리: 스펙 문서에서 등장하는 주요 용어(예: Resource, Operation, Capabilities 등)가 있다면 조사하여 간단히 정리.
	•	사례 연구: 공개 MCP 서버 목록 중 하나를 골라(예: GitHub MCP 서버), 해당 리포지토리의 README나 코드 스니펫을 살펴보고 어떻게 동작하는지 추론. 가능하면 주요 엔드포인트(API)와 기능을 요약해서 공유. (예: GitHub MCP 서버는 리포지토리 내용을 읽고 검색하는 기능 제공 등)
	•	토의 준비: MCP의 이론을 파악한 후, “우리 프로젝트에 MCP를 도입한다면 어떤 부분에 활용 가능할까?”를 각자 생각해보기. 예를 들어 개인 프로젝트 아이디어가 사내 데이터 활용이라면 MCP로 연결 가능한 후보 데이터 소스 목록 작성.

논의할 질문:
	•	MCP가 등장하게 된 배경(모델 격리 문제)에 대해 정리해봅시다. 왜 개별 기업들이 각자 플러그인이나 툴 체계를 만들지 않고 MCP 같은 표준을 필요로 했을까요?
	•	MCP의 동작 방식에 대해 이해한 바를 공유하세요. (예: “MCP 서버”는 무엇을 하고 “MCP 클라이언트”는 무엇인지, 양쪽이 어떻게 통신하는지 등)
	•	현재 공개된 MCP 서버 예시 중 흥미로운 것이 있었나요? 각자 조사한 MCP 서버 사례를 소개하고, 그것이 어떤 활용 가치를 가지는지 토론합니다.
	•	우리 팀의 사이드 프로젝트 시나리오에서 MCP를 적용해볼 수 있는 아이디어가 있나요? (예: “코딩 튜터” 프로젝트에 MCP를 붙인다면 로컬 파일 시스템 접근을 통해 사용자 코드 파일을 읽어 조언할 수 있을 것이다 등)
	•	MCP를 실제 적용하려면 해결해야 할 과제나 우려 사항은 무엇일까요? (예: 보안/권한 관리, 성능, 표준 채택 여부 등)

참고 자료:
	•	Anthropic 블로그: Introducing MCP – MCP 개념과 목적을 설명한 공식 발표 ￼ ￼
	•	Anthropic Developers Docs: Model Context Protocol (MCP) – “AI용 USB-C 포트”에 비유한 MCP 소개 ￼
	•	Model Context Protocol 공식 사이트 – 스펙 문서 및 예제 (modelcontextprotocol.io)
	•	GitHub 저장소: modelcontextprotocol/servers – 공개 MCP 서버 구현 모음 (Slack, Google Drive 등)
	•	Jowyang 서베이: MCP spec gaining adoption – Anthropic의 MCP 표준에 여러 스타트업이 참여 중이라는 업계 동향 ￼
	•	Humanloop 블로그: MCP Explained – MCP가 무엇이며 어떤 가능성을 여는지 쉽게 풀이한 글
	•	Microsoft DevBlog: C# SDK for MCP – MS가 참여한 MCP .NET SDK 개발 소식 (대기업에서도 주목한다는 점)

⸻

7주차: Model Context Protocol (MCP) 실습 및 적용 (2부)

왜 이걸 공부해야 하는가? 지난 주 이론 학습을 바탕으로, 이번 주에는 MCP를 실제로 다뤄보는 시간을 가집니다. 새로운 기술은 직접 사용해봐야 장단점과 현실적인 난이도를 체감할 수 있습니다. MCP는 현재 개발 중인 표준이긴 하지만, 공개 SDK와 예제들이 존재하므로 작은 규모로나마 실습해볼 수 있습니다. 이를 통해 사이드 프로젝트에 MCP를 적용한다면 어떻게 될지 미리 경험해보고, 현실적인 통합 방안을 모색합니다. 또한 MCP와 유사한 개념의 다른 접근(예: OpenAI 플러그인, Tools + LLM 에이전트 등)과 비교하여 이해를 넓힙니다.

학습 주제 및 목표:
	•	MCP Python SDK 실습: 공식 Python SDK를 사용하여 간단한 MCP 서버/클라이언트 예제 실행 ￼
	•	예제 프로젝트 따라 하기: Datacamp 튜토리얼 등에서 제시하는 Claude와 GitHub/Notion을 연결하는 MCP 데모 프로젝트 분석 ￼
	•	MCP 서버 구현 실습: 아주 간단한 MCP 서버를 만들어보기 – 예: “날씨 정보 제공” MCP 서버 (정적 함수로 현재 날씨 문자열을 리턴) 및 해당 스펙 정의, 이를 호출하는 간단한 MCP 클라이언트 에이전트 구성 (가능한 범위 내에서)
	•	Claude 등 AI 모델과 MCP 연동: Claude Desktop 애플리케이션이 있다면 로컬 파일 MCP 서버를 연결하여 Claude가 내 PC 파일을 읽게 해보는 실험. 또는 Victor Dibia 등의 오픈소스 에이전트(AutoGen 등)를 사용해 OpenAI GPT와 MCP 서버 연계 테스트 ￼ ￼
	•	통합 시큐리티 이해: MCP를 사용해 외부 시스템에 접근시 발생할 수 있는 보안 이슈(권한 부여, 인증) 개념 학습 (예: OAuth 사용 등)
	•	사이드 프로젝트에의 적용 계획 구체화: 각자 자신의 프로젝트 아이디어에 MCP를 어떻게 넣을지 간단한 디자인 초안 작성 (예: 필요한 MCP 서버 종류 식별, 없으면 커스텀 구현해야 할 부분 목록화)

실습 과제:
	•	Python SDK Quickstart: Model Context Protocol Python SDK를 설치하고 제공된 간단 예제를 실행해보기. (SDK README의 “Hello World” 수준 예제가 있다면 활용)
	•	예: pip install mcp 후 문서의 간단한 echo 서버/클라이언트 예제를 실행하고, 클라이언트가 서버에 요청 보내 응답 받는 과정 콘솔에서 확인.
	•	MCP 예제 프로젝트 분석: DataCamp의 MCP: A Guide with Demo Project 튜토리얼을 참고하여 Claude와 GitHub 저장소를 연결하는 MCP 서버 예제를 읽어옵니다 ￼. 코드를 직접 실행해보는 것이 최상이지만, 어려울 경우 코드 흐름을 분석하여 요약: Claude가 어떤 프롬프트로 MCP 서버를 호출하고, 서버는 어떤 형태로 응답을 주는지 등.
	•	간이 MCP 서버 만들어보기: (도전 과제) 팀원들과 함께 간단한 MCP 서버를 직접 구현해봅니다. 예를 들어 “이 서버에 city 이름을 보내면 날씨 정보를 문자열로 돌려준다”는 기능: Python SDK의 예제를 응용하여 get_weather(city) 함수를 갖춘 MCP 서버 작성 ￼ ￼. 그리고 OpenAI GPT를 MCP 클라이언트로 써서 해당 서버로 질의하도록 프롬프트를 구성 (또는 AutoGen 등 툴 사용). 성공하면 AI 모델이 실제 코드 함수(get_weather) 결과를 받아와 응답하는 것을 확인.
	•	개인 프로젝트 MCP 적용 구상: 각자 자신의 최종 프로젝트 구상에 MCP를 적용해본 시나리오를 1개 이상 작성. 예: “내 프로젝트에서 PDF 자료를 읽어 답변하는 기능은 MCP 서버 (예: PDF 파일 리더) + Claude를 활용하면 구현 가능: Claude에게 MCP fetch 서버로 PDF 내용을 가져오도록 시킨다” 등의 아이디어를 짧게 정리.

논의할 질문:
	•	MCP Python SDK를 사용해보니 어떤가요? 문서화나 사용 편의성 측면에서 느낀 점을 공유해주세요.
	•	직접 MCP 서버/클라이언트를 돌려본 경우, 통신이 잘 이루어졌나요? 어려웠다면 어떤 부분에서 어려움이 있었나요 (예: 스펙 작성, 인증, 프롬프트 구성 등)?
	•	MCP를 실제 프로젝트에 넣을 때 가장 큰 실용적 장애는 무엇이라고 생각하나요? (예: 현재 지원하는 모델이 제한적이라던가, 셋업이 복잡하다던가)
	•	AI 모델과 외부 툴 통합의 다른 방식들과 MCP를 비교해봅시다. 예를 들어 OpenAI의 플러그인, LangChain의 도구 호출, AutoGen/Guidance 등의 접근이 있는데, MCP와 어떤 차별점이 있을까요?
	•	최종 프로젝트에 MCP 아이디어를 적용해본 시나리오를 각자 소개하고, 실현 가능성이나 예상되는 난관에 대해 함께 피드백합니다.

참고 자료:
	•	DataCamp 튜토리얼: MCP: A Guide with Demo Project – Claude를 GitHub/Notion과 연결하는 데모 예제 ￼
	•	Victor Dibia 블로그: Using MCP with AutoGen Agents – OpenAI/Claude 에이전트에 MCP 툴을 통합하는 방법 소개 ￼ ￼
	•	Model Context Protocol 공식 Example Servers 페이지 – 다양한 MCP 서버 예제와 사용 가이드 ￼ ￼
	•	YouTube: MCP Hands-On (Python) – MCP 서버/클라이언트 구현을 보여주는 워크스루 영상 (실습시 참고) ￼
	•	Medium: MCP 완전 정복 튜토리얼 – MCP 개념부터 예제 구현까지 상세 설명한 연재 글 (필요 시 참고)
	•	OpenAI Plugins vs Anthropic MCP – 두 접근법 비교한 토론 스레드 (MCP의 표준화 이점 논의)

⸻

8주차: 개인 사이드 프로젝트 기획 및 설계

왜 이걸 공부해야 하는가? 이제 다양한 생성형 AI 도구와 개념을 학습했으므로, 이를 종합하여 개인 사이드 프로젝트를 구체화할 단계입니다. 프로젝트를 수행하면서 실제로 문제를 해결해보는 과정에서 많은 것을 배우게 되며, 산출물은 본인의 포트폴리오가 되어 성취감을 줄 것입니다. 이번 주에는 각자의 프로젝트 아이디어를 명확히 다듬고 실현 가능한 계획을 세웁니다. 무엇보다도 2주 남짓한 개발 기간 내에 완성하려면 범위를 현실적으로 조절하는 것이 중요합니다. 또한 프로젝트를 설계하면서 자연스럽게 지금까지 배운 개념들(프롬프트 엔지니어링, API 활용, MCP 적용 등)을 어떻게 활용할지 결정하게 될 것입니다. 이 과정은 향후 실전에서 AI 프로젝트를 기획·설계하는 연습이 되기도 합니다.

학습 주제 및 목표:
	•	아이디어 구체화: 초기 구상한 생성형 AI 프로젝트 아이디어를 명확한 문제 정의와 해결 방안으로 구체화 (예: “개발자용 SQL 쿼리 자연어 생성기” → 자연어 입력을 받아 SQL 쿼리 추천해주는 웹앱)
	•	기술 스택 결정: 프로젝트에 사용할 생성형 AI 모델 선택(OpenAI GPT, Claude 등) 및 통합 방식 결정 (API 호출, MCP 필요 여부, 기타 프레임워크 사용 여부)
	•	요구 기능 목록화: 프로젝트의 주요 기능을 정리하고 우선순위 지정 – 반드시 구현할 핵심 기능 vs. 시간 남으면 추가할 부가 기능
	•	시스템 아키텍처 설계: 컴포넌트 다이어그램 또는 흐름도 간단히 그려보기 – 프론트엔드/UI, 백엔드 로직, AI API 호출 부분, 데이터베이스나 외부 연동 요소 등 식별
	•	일정 수립: 남은 2주의 개발 일정을 대략 계획 – 1주차(9주차)에 구현할 부분과 2주차(10주차)에 마무리/테스트할 부분 나누기
	•	위험 요소 분석: 구현하면서 문제가 될 수 있는 부분 미리 생각해보기 (예: API 호출 비용, 지연 시간, 모델 출력의 품질 등) 및 대책 준비
	•	협업 및 지원 계획: 4명 스터디 팀 내에서 각자 프로젝트를 하지만, 어려움이 있을 때 서로 코드 리뷰나 문제 해결을 도울 방법 논의

실습 과제:
	•	아이디어 발표 준비: 각자 현재까지 구상한 프로젝트 아이디어를 5분 내외로 발표할 자료 준비 (구두 발표 가능). 포함 내용: 문제 배경, 핵심 기능, 사용할 AI 모델/기술, 기대 효과.
	•	기능 리스트 작성: 자신의 프로젝트에 필요한 기능을 최대한 쪼개어 목록 작성. 그 중 “MVP(최소 기능 제품)” 범위에 해당하는 것을 표시. (예: UI는 대화형 콘솔로 시작 – 웹UI는 옵션으로)
	•	아키텍처 스케치: 종이에 또는 화이트보드에 프로젝트 구조를 그려본 뒤 사진으로 찍거나, 다이어그램 툴을 사용해 그려보기. 컴포넌트 간 데이터 흐름(사용자 입력 -> 처리 -> 모델 호출 -> 응답 -> 출력)을 화살표로 나타낼 것. 이를 스터디원들과 공유하여 피드백 받기.
	•	기술 검증(Spike): 계획 단계에서 불확실한 부분을 미리 짧게 테스트. 예를 들어, “PDF 파일 요약” 기능이 있다면, 작은 PDF를 읽어 요약하는 OpenAI API 호출을 미리 해보고 결과를 확인. 혹은 “음성 입력”이 필요하면 음성을 텍스트로 변환하는 오픈소스 라이브러리를 사전에 테스트. 이러한 스파이크 결과를 토대로 계획을 조정.
	•	작업 일정 만들기: 앞으로 1.5~2주 동안의 작업 일정을 세분화. 예: Day 1-2: 기본 뼈대 세팅, Day 3-4: 핵심 AI 기능 구현, Day 5: UI 개선, Day 6: 버그 수정 및 테스트, 등. 팀에 공유하여 서로 현실적인지 점검.

논의할 질문:
	•	각자 준비한 프로젝트 아이디어 발표를 듣고, 이해가 안 되는 부분이나 개선 아이디어를 자유롭게 제시합니다. 동료들의 피드백을 통해 아이디어를 보완하세요.
	•	기능 목록을 만들면서 느낀 구현상의 난이도는 어떤가요? 너무 방대하다고 느껴지는 부분은 어디이고, 어떤 식으로 범위를 줄일 수 있을까요?
	•	선택한 AI 모델/기술 스택이 적절한지 토론합니다. 예를 들어 “이 기능에는 GPT-4까지는 필요 없을 것 같은데 3.5로도 충분하지 않을까?” 또는 “실시간성이 중요하다면 Claude Instant 모델이 나을 수 있다” 등 상호 의견 교환.
	•	아키텍처 설계를 공유하며, 더 효율적인 방법이나 필요한 수정점에 대해 논의합니다. (특히 MCP 적용 여부, 데이터 저장 방안 등)
	•	위험 요소 및 대비책에 대해: API 비용이 많이 들 것 같은 프로젝트는 어떻게 제한할지, 모델 응답이 부정확할 때 보완 장치는 무엇인지 등 서로 아이디어를 내봅니다.

참고 자료:
	•	GitHub 레포지토리: awesome-generative-ai – 다양한 생성형 AI 프로젝트 모음 리스트 ￼ (프로젝트 아이디어 참고)
	•	Medium 글: 200+ Generative AI Project Ideas in 2025 – 생성형 AI 프로젝트 아이디어 모음 (영감 얻기 용) ￼
	•	템플릿: Software Project One-pager – 프로젝트 개요 정리용 문서 템플릿 (문제, 해결, 성공 기준 등 작성)
	•	Diagrams.net 등 – 아키텍처 다이어그램 그리기 쉬운 무료 도구
	•	이전 주차에 참고했던 모든 자료 – 자신의 프로젝트와 관련된 자료를 재참고 (예: OpenAI 함수 호출 예제가 내 프로젝트에 적용 가능하다면 다시 확인)

⸻

9주차: 개인 프로젝트 개발 및 중간 점검

왜 이걸 공부해야 하는가? 이제 본격적인 개발 단계에 들어갑니다. 제한된 시간 내에 프로토타입을 완성하려면 효율적으로 개발하고, 발생하는 문제를 민첩하게 해결해야 합니다. 이 주에는 각자가 개발에 집중하되, 스터디 동료들과 소통하며 문제를 해결하는 협업을 진행합니다. 또한 중간 결과물을 점검함으로써 방향을 수정하거나 범위를 재조정할 수 있습니다. 실제 현업의 애자일 방식처럼 짧은 주기로 피드백을 받고 개선하는 과정을 연습하는 셈입니다. 이번 주 스터디 모임에서는 각자의 진행 상황을 공유하고, 막힌 부분에 대해 함께 해결 아이디어를 모색합니다.

학습 주제 및 목표:
	•	개발 진행 상황 공유: 각자 구현한 부분과 남은 부분을 점검하고 계획 대비 진척도를 확인
	•	공통 기술 이슈 토론: API 호출 오류나 한계, 프롬프트 튜닝 문제, UI/백엔드 통신 이슈 등 각 프로젝트에서 발생한 문제를 공유하고 해결책 브레인스토밍
	•	성능 및 품질 점검: 모델 응답 속도가 느리거나 품질이 떨어지는 경우, 대안을 논의 (예: 캐싱 도입, 프롬프트 수정, 혹은 모델 교체 등)
	•	범위 조정: 프로젝트 완성도가 위험할 경우, 구현 범위 축소 또는 기능 간소화를 결정 (우선 MVP 완성을 목표로)
	•	테스트 및 피드백 계획: 다음 주 최종 발표 전에 남은 기간 동안 테스트할 시나리오와 피드백 받을 대상(동료, 친구 등) 정하기
	•	문서화 준비: 프로젝트 사용 방법 또는 시연을 위해 필요한 자료(README, 발표 슬라이드 등) 초안 작성 시작

실습 과제:
	•	개발 스프린트: 이번 주 대부분의 시간을 실제 코딩에 투자. 목표는 핵심 기능의 동작하는 프로토타입 완성. 구현 중간중간 버전 관리(Git 활용)하며 진행 상황을 기록.
	•	중간 데모 준비: 스터디 모임에서 보여줄 간단한 데모 또는 화면 캡처 준비. 완전하지 않아도 좋으니 현재까지 동작하는 부분을 시연할 수 있도록 세팅. (예: 챗봇 프로젝트라면 현재까지 가능한 Q&A 한두 가지를 실제로 실행)
	•	이슈 목록 정리: 개발하며 만난 문제/버그/어려움 리스트를 작성. 각 이슈마다 지금까지 시도한 해결방법과 느낀점을 메모. 모임에서 이 리스트를 공유하며 조언을 구함.
	•	테스트 시나리오 작성: 자기 프로젝트의 주요 기능에 대해 테스트해봐야 할 경우들을 정리. 예: “한글 입력도 제대로 처리되는지 테스트”, “엣지 케이스: 아주 긴 문장을 넣으면 어떻게 되는지” 등. 아직 구현 안 된 부분이라도 예상 시나리오 작성.
	•	문서/발표 초안: README 파일 초안을 작성 시작 – 프로젝트 소개, 설치/실행 방법, 사용 예시 등을 채워넣기 시작. 또는 최종 발표 슬라이드에 들어갈 내용 미리 구성.

논의할 질문:
	•	각자 프로젝트 데모를 짧게 수행하고 현재까지의 결과물을 공유합니다. 이를 본 다른 스터디원들이 피드백: 인상적인 점, 개선 필요해 보이는 점, 버그로 보이는 부분 등을 자유롭게 이야기.
	•	개발하면서 가장 어려웠던 문제는 무엇이었나요? (예: “모델이 사용자 의도를 잘못 이해한다”, “API 한도가 낮아 애를 먹었다” 등) 서로의 문제 상황을 듣고 함께 해결책을 생각해봅니다.
	•	모델 선택이나 프롬프트에 변경을 준 사례가 있나요? 왜 그렇게 했고 효과가 어떠했는지 공유해보세요.
	•	남은 작업 중 우선 순위를 재조정해야 할 부분이 있나요? 각자 해야 할 일 중 덜 중요한 것은 과감히 줄이거나 제외하는 것도 완성을 위해 필요합니다. 그룹의 시각에서 각 프로젝트의 “필수 vs 선택” 기능을 다시 한번 점검해봅니다.
	•	최종 테스트와 발표를 어떻게 준비할지 논의합니다. 혹시 최종 발표 때 일반 청중(동료 개발자 외)에 보여줄 계획이라면, 어떤 배경 설명이 필요할지 상의하고, 데모 시연 흐름을 간단히 구상해봅니다.

참고 자료:
	•	Stack Overflow / GitHub Issues 검색 – 개발 중 막힌 부분에 대한 해결책을 찾기 (예: 특정 라이브러리 에러, API 오류 메시지 등)
	•	OpenAI/Anthropic 지원 문서 – API 에러코드 설명, Rate limit 안내 등 참고하여 문제 해결
	•	Debugging Generative AI Tips – LLM 기반 앱 디버깅 모범 사례 정리 블로그 (예: why does my prompt fail?)
	•	“잊지 말아야 할 마감 원칙” – 90% 완성도를 목표로 하기 (완벽을 추구하다 마감 못 지키는 실수 방지에 대한 조언 칼럼)
	•	Previous study notes – 앞서 정리한 프롬프트 팁이나 참고 자료 다시보기 (문제 해결에 실마리가 될 수 있음)

⸻

10주차: 최종 발표 및 쇼케이스

왜 이걸 공부해야 하는가? 드디어 모든 노력을 결실맺는 쇼케이스 주간입니다. 각자가 완성한 (또는 프로토타입한) 생성형 AI 사이드 프로젝트를 팀원들과 공유하고, 가능한 경우 외부에도 공개합니다. 최종 발표를 통해 자신의 아이디어를 정리하고 표현하는 능력을 기르고, 서로의 성과를 축하하며 마무리합니다. 또한 프로젝트를 되돌아보며 무엇을 배웠는지, 생성형 AI에 대한 이해가 어떻게 깊어졌는지를 회고하는 시간을 가집니다. 이 최종 단계는 단순히 끝내는 것이 아니라, 이후로도 계속될 학습과 활용을 다짐하는 의미도 있습니다.

학습 주제 및 목표:
	•	최종 결과물 시연: 각자 프로젝트의 주요 기능을 직접 실행하며 데모
	•	구현 내용 설명: 사용한 생성형 AI 모델과 기술, 프롬프트 설계, MCP나 기타 도구 적용 여부 등을 청중이 이해하기 쉽게 설명
	•	난관과 극복 이야기: 개발 중 겪은 어려움과 이를 어떻게 해결했는지 공유 (배운 점 강조)
	•	프로젝트 결과에 대한 자기 평가: 애초 목표 대비 어느 정도 달성했는지, 사용자 입장에서 유용할 것으로 예상되는지 등
	•	팀 피드백 및 Q&A: 발표를 듣는 다른 스터디원들이 질문하고 피드백 제공
	•	향후 계획: 각 프로젝트를 앞으로 어떻게 발전시킬지 또는 배운 것을 본업/다른 분야에 어떻게 활용할지 발표자가 간단히 언급
	•	스터디 전체 회고: 10주간 스터디 커리큘럼 및 진행 방식에 대한 피드백 교환, 개선점 도출 (향후 다른 스터디나 후속 모임에 참고)

실습/발표 구성:
	•	프로젝트 소개 (3분): 문제 배경과 솔루션 개요 소개 – 왜 이 아이디어를 선택했는지, 사용자가 어떻게 활용하는지 시나리오 설명
	•	데모 시연 (2분): 애플리케이션 실제 동작 화면을 보여주며 핵심 기능 실행. (녹화 영상으로 대체 가능하나, 라이브 데모가 임팩트 큼)
	•	기술 설명 (2분): 아키텍처 다이어그램을 보여주며 시스템 구성 설명. 어떤 AI API/모델을 썼고, 어떻게 통신하는지, 특별히 신경 쓴 프롬프트나 알고리즘이 있다면 소개.
	•	성과 및 한계 (1분): 결과물이 가진 장점과 아직 개선이 필요한 부분 솔직하게 정리. (예: “XX 기능이 성공적으로 동작했지만 YY 상황에서는 오작동함을 발견”)
	•	배운 점 (1분): 프로젝트를 통해 얻은 교훈 or 생성형 AI에 대한 통찰 한 가지씩 말하기.
	•	질의응답 (각 2-3분): 청중(스터디 팀원 및 혹시 외부 초대자)이 질문하면 답변.
	•	총평 및 다음 계획: 스터디 리더나 전원이 각 발표에 대해 한마디 총평. 그리고 이 프로젝트를 더 발전시킬 의향이 있는지, 스터디를 확장/지속할 계획인지 등 자유롭게 언급.

(각 발표자당 약 10분 내외, 4명일 경우 40-50분 + Q&A로 1시간~1.5시간 예상)

논의할 질문 (회고):
	•	10주 동안 생성형 AI를 공부하고 프로젝트까지 완수한 소감을 서로 이야기해봅시다. 가장 기억에 남는 순간이나 인상적인 발견은 무엇이었나요?
	•	스터디 목표였던 “다양한 생성형 AI 도구 학습 및 프로젝트 배포 역량 향상”을 달성했다고 생각하시나요? 각자 느낀 변화를 공유하세요 (예: 예전보다 프롬프트 작성이 능숙해졌다, 새로운 도구에 겁먹지 않게 되었다 등).
	•	프로젝트를 진행하면서, 실제로 MCP나 기타 고급 개념을 적용해본 경우 그 효과는 어땠나요? 아니면 시간상 적용 못 했다면 이론과 현실 간의 간극은 어땠는지 토론합니다.
	•	앞으로 이 경험을 어떻게 활용할 계획인가요? 직장에서 작은 자동화에 적용해볼 생각이 있다든지, 더 공부하고 싶은 주제가 생겼다든지 자유롭게 공유합니다.
	•	커리큘럼이나 진행 방식에 대한 피드백: 10주의 스터디에서 좋았던 점과 아쉬운 점을 짚어보고, 만약 다음에 비슷한 스터디를 한다면 무엇을 바꾸고 싶은지 의견을 모읍니다.

참고 자료:
	•	각자 작성한 프로젝트 README 및 코드 저장소 (스터디원들 간 상호 참조)
	•	발표 녹화본 (선택): Zoom 등으로 발표를 녹화하여 이후 복기할 수 있음
	•	회사/커뮤니티에 공유할 소개 글: 원한다면 각자 LinkedIn이나 블로그에 이번 프로젝트 후기 작성 (생성형 AI 배움과 결과 정리)
	•	향후 학습 자료 추천: 스터디를 마치며 각자 앞으로 참고하려고 하는 자료 공유 (예: “LangChain 공식 튜토리얼 이어서 보기”, “DeepLearning AI의 생성 AI 전문가 과정 수강 계획” 등)

⸻

以上が、4명의 개발자가 진행한 10주간의 생성형 AI 스터디 커리큘럼입니다. 매 주차마다 학습 동기를 분명히 하고, 구체적인 목표와 과제, 자료를 제시함으로써 체계적으로 학습하도록 구성하였습니다. 이를 통해 모든 참가자가 Cursor, OpenAI, Claude 등의 도구 활용 능력을 향상하고, 최종적으로는 각자의 창의적인 사이드 프로젝트를 완성 및 발표하는 성과를 얻길 바랍니다. 10주간 고생 많으셨습니다! 🎉
