`$ kubectl get engineer vipin-john-wilson -o yaml`

```yaml
apiVersion: vjw/v1
kind: Engineer
metadata:
  name: vipin-john-wilson
  namespace: stockholm
  labels:
    role: linux-cloud-infrastructure
spec:
  stack:
    languages: [go, typescript, python, bash]
    infra: [kubernetes/k3s, aws, github-actions]
  links:
    linkedin: https://www.linkedin.com/in/vipinjohnwilson
status:
  phase: Running
  ready: "1/1"  # since 1987
```
