# 20240320_Salary_Data

Link : https://dacon.io/competitions/official/236226

## Goals

개인 특성 데이터를 활용하여 개인 소득 수준을 예측하는 AI 모델 개발
수상권 노리기

## Dataset

한 세션에서 발생한 다양한 정보를 기록한 웹 로그

train.csv
┣ ID : 학습 데이터 고유 ID
┣ Age : 나이
┣ Gender : 성별
┣ Education_Status : 교육 수준
┣ Employment_Status : 고용 상태
┣ Working_Week (Yearly) : 연간 근무 기간(주단위)
┣ Industry_Status : 산업군
┣ Occupation_Status : 근로 형태
┣ Race : 인종
┣ Hispanic_Origin : 이탈 여부 (0: 이탈하지 않음, 1: 이탈함)
┣ transaction : 세션 내에서 발생의 거래의 수
┣ transaction_revenue : 총 거래 수익
┣ continent : 세션이 발생한 대륙
┣ subcontinent : 세션이 발생한 하위 대륙
┣ country : 세션이 발생한 국가
┣ traffic_source : 트래픽이 발생한 소스
┣ traffic_medium : 트래픽 소스의 매체
┣ keyword : 트래픽 소스의 키워드, 일반적으로 traffic_medium이 organic, cpc인 경우에 설정
┗ referral_path : traffic_medium이 referral인 경우 설정되는 경로 test.csv sample_submission.csv

평가 방식
RMSE score

진행 기간
2024.03.06 ~ 2024.03.13
