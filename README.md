# stock_predict

## 기획 
- 관심도 기반의 주가 예측 서비스 구현
  
### Use Data  
- 위키피디아 페이지뷰(features) type int
- 관심도(소셜네트워크 댓글) type int
- 소셜네트워크 댓글 긍부정 type char
- 생성형 모델 기반 분석 데이터 type text
- 주가 데이터 type float 
  
###  USE_Model
- LLama3 7B (주가 분석 리포트) and Gemini 1.5 flash (주가 분석 리포트)  Kn(owledge Distillation 기법 참고  
- 긍부정 판단 모델 bert 계열 base 모델 (연구중)
- 회귀예측 기반의 DLNP model


###  USE
- kubeflow + mlflow 
- FastAPI
- playwright 
- flutter 
- redis or firebase
- pgsql

## 최종 결과물 
- Web앱 형태의 주가 예측 서비스 개발
