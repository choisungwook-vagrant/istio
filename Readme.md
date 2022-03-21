# 개요
* istio실습을 위한 vagrantfile

# 하드웨어 사양
> 하드웨어 사양은 config.yaml에서 수정할 수 있습니다.
* cpu: 최소 4core
* memory: 최소 8GB이상, 권장 16GB

# 버전 상세내용
* 운영체제: 우분투 20.04
* 컨테이너 엔진: Docker latest
* minikube: latest
* kubectl: latest

# 실행방법
```sh
vagrant up
```

# 중지방법
```sh
vagrant halt
```

# 삭제방법
```sh
vagrant destroy --force
```
