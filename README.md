# 20240327_Salary_Data

Link : https://dacon.io/competitions/official/236226

## Goals

개인 특성 데이터를 활용하여 개인 소득 수준을 예측하는 AI 모델 개발
수상권 노리기

## Dataset

개인의 소득 수준과 연관된 컬럼들

train.csv
┣ ID : 학습 데이터 고유 ID
┣ Age : 나이
┣ Gender : 성별
┣ Education_Status : 교육 수준
┣ Employment_Status : 고용 상태
┣ Working_Week (Yearly) : 연간 근무 기간(주단위)
┣ Industry_Status : 산업군
┣ Occupation_Status : 직업군
┣ Race : 인종
┣ Hispanic_Origin : 히스패닉 출신지
┣ Martial_Status : 결혼 상태
┣ Household_Status : 가정 상태
┣ Household_summary : Household_Status 요약 버전
┣ Citizenship : 내국인 여부
┣ Birth_Country : 출생국
┣ Birth_Country (Father) : 출생국(부)
┣ Birth_Country (Mother) : 출생국(모)
┣ Tax_Status : 맞벌이 & 65세 이상 여부
┣ Gains : 재산 증가
┣ Losses : 재산 감소
┣ Dividends : 배당금
┣ Income_Status : 소득 수준(중간값 이상 여부)
┗ Income : 1시간 단위 소득(TARGET)

평가 방식
RMSE score

진행 기간
2024.03.20 ~ 2024.03.27
