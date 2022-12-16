# templates

Declarative templates for hosts, workloads, and deployments

tls:

- hosts:
  - {{deployment}}.{{workload}}.{{domain}}
    secretName: {{tlsSecret}}
