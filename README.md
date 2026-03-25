# Titanic ML Pipeline Project

## Overview
Titanic dataset을 활용한 생존 예측 모델링 프로젝트입니다.  
Pipeline과 ColumnTransformer를 사용하여 전처리와 모델을 통합하였습니다.

## Experiments
- SVM (No Scaling)
- SVM + StandardScaler
- SVM + MinMaxScaler
- KNN + StandardScaler

## Results
| Model | Accuracy |
|------|---------|
| SVM (No Scaling) | 0.5978 |
| SVM (Standard) | 0.8156 |
| SVM (MinMax) | 0.8101 |
| KNN (Standard) | 0.7989 |

## MLOps
- Git: 코드 버전 관리
- DVC: 데이터 및 metrics 관리

## Key Insight
Scaling은 SVM, KNN과 같은 거리 기반 모델에서 성능에 큰 영향을 미친다.
