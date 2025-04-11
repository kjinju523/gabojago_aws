# 🚀 CloudFront

## 1. CloudFront란?
- 전 세계 엣지 로케이션을 활용한 **콘텐츠 전송 네트워크(CDN)**

## 2. 사용 목적
- S3, EC2, ALB, 외부 서버에 저장된 정적/동적 콘텐츠를 빠르게 배포

## 3. 주요 개념
- Origin: 콘텐츠 원본 (예: S3)
- Edge Location: 사용자 가까운 서버
- TTL: 캐싱 유효 시간

## 4. 시험 팁
- S3 정적 사이트 + CloudFront 구성 시 **S3는 퍼블릭 접근 안 해도 됨**
- SSL 적용을 위한 ACM 연동 (무료 인증서)
