# CKA (Certified Kubernetes Administrator) 자격증 문제풀이

이 저장소는 CKA 자격증을 준비하는 과정에서 문제풀이를 챕터별로 정리한 자료입니다. 각 섹션은 Kubernetes의 주요 주제를 다루며, 실습 및 문제풀이를 포함하고 있습니다.

---

## 목차
1. [클러스터 아키텍처 및 설치 (Cluster Architecture, Installation, and Configuration)](1_클러스터_아키텍처_및_설치.md)  
2. [네트워크 (Networking)](2_네트워크.md)  
3. [워크로드 및 스케줄링 (Workloads and Scheduling)](3_워크로드_및_스케줄링.md)  
4. [스토리지 (Storage)](4_스토리지.md)  
5. [클러스터 유지관리 (Cluster Maintenance)](5_클러스터_유지관리.md)  
6. [보안 (Security)](6_보안.md)  
7. [로깅 및 모니터링 (Logging and Monitoring)](7_로깅_및_모니터링.md)  
8. [문제 해결 (Troubleshooting)](8_문제_해결.md)  

---

## 1. 클러스터 아키텍처 및 설치 (Cluster Architecture, Installation, and Configuration)
- **주요 주제**
  - Control Plane 구성 요소 이해
  - etcd 설정 및 구성
  - kubeadm을 사용한 클러스터 설치

- **실습**
  - Control Plane 장애 조치 시뮬레이션
  - etcd 백업 및 복원

[🔗 상세 내용 보기](./chapter1/README.md)

---

## 2. 네트워크 (Networking)
- **주요 주제**
  - CNI 플러그인 이해
  - 서비스 네트워크 및 Pod-to-Pod 통신

- **실습**
  - NetworkPolicy 작성 및 테스트
  - 서비스 디버깅

[🔗 상세 내용 보기](./chapter2/README.md)

---

## 3. 워크로드 및 스케줄링 (Workloads and Scheduling)
- **주요 주제**
  - Deployment 및 ReplicaSet 구성
  - Node 및 Pod Affinity 설정

- **실습**
  - CronJob 작성 및 관리
  - Deployment 롤링 업데이트 수행

[🔗 상세 내용 보기](./chapter3/README.md)

---

## 4. 스토리지 (Storage)
- **주요 주제**
  - PersistentVolume 및 PersistentVolumeClaim 설정
  - StorageClass 이해

- **실습**
  - PVC를 사용하는 Pod 생성
  - 동적 프로비저닝 테스트

[🔗 상세 내용 보기](./chapter4/README.md)

---

## 5. 클러스터 유지관리 (Cluster Maintenance)
- **주요 주제**
  - 클러스터 업그레이드
  - 노드 유지관리 모드(Maintenance Mode)

- **실습**
  - kubeadm을 사용한 업그레이드 시뮬레이션
  - 노드 드레인 및 복구

[🔗 상세 내용 보기](./chapter5/README.md)

---

## 6. 보안 (Security)
- **주요 주제**
  - RBAC 구성 및 관리
  - Pod Security Policy 이해

- **실습**
  - 사용자 정의 Role 및 RoleBinding 생성
  - Pod Security Context 설정

[🔗 상세 내용 보기](./chapter6/README.md)

---

## 7. 로깅 및 모니터링 (Logging and Monitoring)
- **주요 주제**
  - 로그 수집 및 분석
  - Prometheus 및 Grafana를 사용한 모니터링

- **실습**
  - kubectl logs 명령어로 Pod 디버깅
  - Prometheus 경고 규칙 구성

[🔗 상세 내용 보기](./chapter7/README.md)

---

## 8. 문제 해결 (Troubleshooting)
- **주요 주제**
  - 컨테이너 및 Pod 문제 해결
  - 클러스터 구성 문제 식별 및 해결

- **실습**
  - Pod CrashLoopBackOff 디버깅
  - 클러스터 DNS 문제 해결

[🔗 상세 내용 보기](./chapter8/README.md)

---

## 기여 방법
이 자료는 지속적으로 업데이트됩니다. 기여를 원하시는 분은 PR(Pull Request)을 보내주세요!

---

## 라이선스
이 프로젝트는 MIT 라이선스에 따라 배포됩니다. [LICENSE](./LICENSE) 파일을 참조하세요.
