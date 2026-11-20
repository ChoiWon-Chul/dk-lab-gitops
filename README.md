# dk-lab-gitops — Argo CD가 읽는 배포 선언 저장소

이 폴더의 **내용물만** `dk-lab-gitops` 공개 저장소 루트에 업로드합니다.

- `k8s/deployment.yaml`: 이미지 주소·replicas·라벨 선언
- `k8s/service.yaml`: ClusterIP 서비스 정의
- 첫 실행 전 `localhost:5001/dk-first-web:seed`가 로컬 Registry에 존재해야 합니다.
- Argo CD의 `source.path`는 `k8s`, `targetRevision`은 `main`으로 맞춥니다.
