# 축구 용어 해설 모델_FootBot

## 팀원
- 김진형(서강대학교 학부 수학과 전공)
- 문유정(서강대학교 학부 경영학, 컴퓨터공학 전공)
- 신현지(서강대학교 학부 경제학, 빅데이터사이언스 전공)
- 하지원(서강대학교 컴퓨터공학과 대학원)
- 한지인(이화여자대학교 학부 컴퓨터공학 전공)

## 진행 기간
2024년 11월 1일 ~ 2일

## 프로젝트 개요
축구는 세계에서 가장 인기 있는 스포츠 중 하나로, 매 경기마다 다양한 규칙과 심판 판정이 경기를 좌우합니다. 하지만 초보자나 젊은 관중들에게는 VAR 판정, 오프사이드 등 복잡한 규칙이 다소 혼란스럽게 느껴질 수 있습니다. 이에 따라 축구 경기를 더욱 쉽게 이해할 수 있도록 AI 기반 ‘축구 규칙 용어 해설 모델’이 개발하게 되었습니다.
이 모델은 경기 기사 요약, 규칙 용어에 대한 친절한 해설을 통해 초보자도 쉽게 경기를 즐길 수 있도록 돕는 것을 목표로 합니다. 축구 팬들에게 친근하고 전문적인 정보 제공 도구가 될 것입니다.

## 구조
<img width="593" height="97" alt="image" src="https://github.com/user-attachments/assets/436d6d18-56c6-4602-bf65-8969eeac77bf" />
<img width="592" height="97" alt="image" src="https://github.com/user-attachments/assets/508ba3a1-be4a-4796-8dd4-ef4aa69569f7" />
<img width="594" height="98" alt="image" src="https://github.com/user-attachments/assets/50595a94-7c2a-4bd5-9878-3faed416cc5f" />

- 데이터 로더: UpstageDocumentParseLoader
- 텍스트 분할기: RecursiveCharacterTextSplitter
- 임베딩 모델: UpstageEmbeddings
- 벡터 DB: Chroma
- 리트리버: Chroma 기반 리트리버
