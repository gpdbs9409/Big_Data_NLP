# 빅데이터를 활용한 자연어 처리 프로젝트

홍콩 링난대학교의 빅데이터 수업에서 진행한 자연어 처리(NLP) 프로젝트의 전체 코드

## 프로젝트 개요

이 프로젝트 목표는 대규모 텍스트 데이터를 활용하여 자연어 처리 기술을 적용하고,
각 모델의 정확도 비교 후, 하이퍼 파라미터 튜닝 및 앙상블 모델을 제작하여 정확도 높은 모델을 설계하는 것입니다.

+스파크 프레임워크 사용 

- **데이터 수집 및 전처리**: 다양한 출처에서 텍스트 데이터를 수집하고, 분석에 적합하도록 정제 및 전처리 수행.
- **토큰화 및 품사 태깅**: 텍스트를 단어 단위로 분할하고, 각 단어에 품사 태그를 부여하여 언어 구조 분석.
- **개체명 인식(NER)**: 텍스트 내에서 인물, 장소, 조직 등 특정 개체를 식별.
- **감정 분석**: 텍스트의 감정적 톤을 분석하여 긍정, 부정, 중립 등의 감정 상태 분류.
- **모델 학습 및 평가**: 머신러닝 모델을 활용하여 NLP 작업을 수행하고, 모델의 성능을 평가.

## 파일 구조

- `Whole project Code.ipynb`: 프로젝트의 전체 코드와 설명이 포함된 Jupyter Notebook 파일.
