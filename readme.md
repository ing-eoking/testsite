# 간단한 정적 웹사이트 (Kubernetes 테스트용)

## 소개
이 프로젝트는 **쿠버네티스 테스트를 위한 간단한 정적 웹사이트**입니다.
주요 목적은 테스트를 위해 정적 웹 콘텐츠를 컨테이너화하여 쿠버네티스 클러스터에 배포해보고,
추후 인프라만 구축 후 **Kubeflow**와 같은 머신러닝 플랫폼 교체를 목표로 합니다.

## 프로젝트 구성 (예정)
- `index.html` : 정적 웹페이지 내용
- `Dockerfile` : 도커 이미지 정의
- `k8s/deployment.yaml` : 쿠버네티스 Deployment
- `k8s/service.yaml` : 쿠버네티스 Service

## 사용법 (예정)
