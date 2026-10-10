`$ kubectl get engineer vipin-john-wilson -o yaml`

```yaml
apiVersion: people.cloudopsshell.com/v1
kind: Engineer
metadata:
  name: vipin-john-wilson
  namespace: stockholm
  labels:
    role: linux-cloud-infrastructure
spec:
  building:
    - name: deaconguard
      description: Linux security scanner with a server and enrollment-token agents
      advisories: [ubuntu, debian, rhel, amazon-linux]
      checks: [packages, file-integrity, config, clamav, yara-x]
      url: https://deaconguard.io
  stack:
    languages: [go, typescript, python, bash]
    infra: [kubernetes/k3s, aws, github-actions]
  links:
    linkedin: https://www.linkedin.com/in/vipinjohnwilson
status:
  phase: Running
  ready: "1/1"  # since 1987
```

**[DeaconGuard](https://github.com/Cloudopsshell/deaconguard)** is a Linux security scanner with a central server and enrollment-token agents. It checks packages against the official Ubuntu, Debian, RHEL and Amazon Linux advisories and covers file integrity, security configuration and malware (ClamAV, plus optional YARA-X rules). [deaconguard.io](https://deaconguard.io)
