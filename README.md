# 혈압 예측 AI 프로젝트
## Demo
-- https://physionet-project-islom.streamlit.app/

## 📋 프로젝트 소개
PhysioNet 기반의 생리학 데이터를 활용하여 환자의 혈압을 예측하고,
AI 기반으로 건강 인사이트를 도출하는 시스템입니다.
---
## ⚙️ 프로젝트 개요
LangChain과 OpenAI GPT-4o-mini를 이용해 의학적 분석을 수행하며,
Scikit-learn 기반 머신러닝 모델을 통해 혈압을 예측합니다.
Streamlit 대시보드에서 모든 결과를 시각화합니다.
---

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


