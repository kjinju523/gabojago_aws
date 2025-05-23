# ⚡ Lambda

## 1. Lambda란?
- 서버를 **직접 운영하지 않고도** 코드를 실행하는 컴퓨팅 서비스 (서버리스)

## 2. 특징
- 이벤트 기반 실행 (ex. S3 업로드, API Gateway 등)
- 코드 단위 과금 (ms + 요청 수 기준)

## 3. 제한
- 실행 시간 최대 15분
- 기본 메모리 제한 128MB~10GB

## 4. 시험 팁
- IAM Role 반드시 필요
- S3, DynamoDB, SNS와 자주 연동됨
