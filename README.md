# 혈압 예측 AI 프로젝트
## Demo
-- https://physionet-project-islom.streamlit.app/

## 프로젝트 소개
PhysioNet 기반 혈압 예측 머신러닝 시스템

## 주요 기능
- 머신러닝 기반 혈압 예측
- LangChain을 활용한 AI 분석
- Streamlit 웹 인터페이스
- 데이터 시각화

## 설치 방법
```bash
pip install -r requirements.txt
```

## 실행 방법
```bash
streamlit run app.py
```

## 프로젝트 구조
```
혈압예측_AI_프로젝트/
├── app.py                      # Streamlit 메인 앱
├── physionet_predictor.py      # ML 예측 모델
├── langchain_processor.py      # LangChain AI 분석
├── utils/
│   └── helpers.py              # 유틸리티 함수
├── data/                       # 데이터 저장소
├── models/                     # 모델 저장소
└── results/                    # 결과물 저장소
```

