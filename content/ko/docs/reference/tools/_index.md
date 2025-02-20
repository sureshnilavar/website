---
title: 도구


content_type: concept
weight: 80
no_list: true
---

<!-- overview -->
쿠버네티스는 쿠버네티스 시스템으로 작업하는 데 도움이 되는 몇 가지 도구를 포함한다.

<!-- body -->

## Minikube

[`minikube`](https://minikube.sigs.k8s.io/docs/)는 개발과 테스팅 목적으로
단일 노드 쿠버네티스 클러스터를 로컬 워크스테이션에서
실행하는 도구이다.

## 대시보드

[`대시보드`](/ko/docs/tasks/access-application-cluster/web-ui-dashboard/), 는 쿠버네티스의 웹기반 유저 인터페이스이며 컨테이너화된 애플리케이션을 쿠버네티스 클러스터로 배포하고
클러스터 및 클러스터 자원의 문제를 해결하며 관리할 수 있게 해준다.

## Helm
{{% thirdparty-content single="true" %}}

[Helm](https://helm.sh/)은 사전 구성된 쿠버네티스 리소스 패키지를 관리하기 위한 도구이다.
이 패키지는 _Helm charts_ 라고 알려져 있다.

Helm은 미리 구성된 쿠버네티스 리소스 패키지를 관리하기 위한 제 3자가
관리하는 도구로, 쿠버네티스 차트(charts)라고도 알려져 있다.

Helm의 용도

* 쿠버네티스 차트로 배포된 인기있는 소프트웨어를 검색하고 사용
* 쿠버네티스 차트로 나의 애플리케이션을 공유
* 쿠버네티스 애플리케이션의 반복가능한 빌드 및 생성
* 매니페스트 파일의 지능화된 관리
* Helm 패키지의 릴리스 관리

## Kompose

[`Kompose`](https://github.com/kubernetes/kompose)는 도커 컴포즈(Compose) 유저들이 쿠버네티스로 이동하는데 도움이 되는 도구이다.

Kompose의 용도

* 도커 컴포즈 파일을 쿠버네티스 오브젝트로 변환
* 로컬 도커 개발 환경에서 나의 애플리케이션을 쿠버네티스를 통해 관리하도록 이전
* V1 또는 V2 도커 컴포즈 `yaml` 파일 또는 [분산 애플리케이션 번들](https://docs.docker.com/compose/bundles/)을 변환
