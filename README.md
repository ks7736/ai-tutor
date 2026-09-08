# 🎯 SAIL AL Target Coach Engine

Samsung AI Language Test (SAIL) AL 등급 달성을 위한 실시간 음성 인식 및 AI 정밀 피드백 웹 애플리케이션입니다.

## 🚀 주요 기능 (Key Features)
- **실시간 음성 인식 (STT)**: Web Speech API를 활용하여 발화 내용을 화면에 실시간 영문 자막으로 표시
- **정적(Pause) 감지**: 발화 중 머뭇거리는 시간을 측정하여 유창성(Fluency) 개선 가이드 제공
- **AL 특화 정밀 분석**: 감점 주요 요인인 관사(a/the), 복수형(-s), 전치사, 수일치 오류 집중 피드백

## 🛠️ 기술 스택 (Tech Stack)
- HTML5 / CSS3 / JavaScript (ES6+)
- Web Speech API (SpeechRecognition)
- MediaRecorder API & Web Audio API
- Gemini API (AI Audio & Text Analysis)

## 📌 사용 방법 (How to Use)
1. `녹음 & 받아쓰기 시작` 버튼을 누르고 질문에 대해 영어로 답변합니다.
2. 답변하는 동안 화면에 실시간으로 작성되는 자막을 확인합니다.
3. 답변이 끝나면 `중단 및 정밀 분석` 버튼을 눌러 AI 피드백 리포트를 확인합니다.
