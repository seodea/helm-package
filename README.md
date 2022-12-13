# Helm Chart package 정보

## Helm Chart package - xxx.tgz

Helm chart를 package 하게되면, Helm chart에서 선언한
name + version으로 아래와 같이 tgz

apiVersion: v1
entries:
subchart-test:

- apiVersion: v2
  appVersion: 1.23-alpine
  created: "2022-12-09T16:33:21.127416+09:00"
  description: A Helm chart for Kubernetes
  digest: 655996bce4318bfe0fa8bbb1439cd2c9f83ca5abee8d233bc49d2d6a6733fb75
  name: subchart-test
  type: application
  urls:
  - https://seodea.github.io/helm-package/charts/main/subchart-test-0.2.0.tgz
    version: 0.2.0
- apiVersion: v2
  appVersion: 1.23-alpine
  created: "2022-12-09T16:33:21.126477+09:00"
  description: A Helm chart for Kubernetes
  digest: dc341f37218f09b53408c24bbcb2f80347a9378a7e7bda6d2ca3a47cf59e936b
  name: subchart-test
  type: application
  urls: - https://seodea.github.io/helm-package/charts/main/subchart-test-0.1.0.tgz
  version: 0.1.0
  generated: "2022-12-09T16:33:21.121912+09:00"
