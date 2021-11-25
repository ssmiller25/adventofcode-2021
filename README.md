# adventofcode-2021

[Advent of Code for 2021](https://adventofcode.com/2021/about) code for Steve Miller.
Taking a slightly differing approach.  Each "solution" will be performed via a k8s 
operator or operators, all written with the [shell-operator](https://github.com/flant/shell-operator) 
and using CRDs unique to each day's problem (I believe).  

All managed in a modern k8s stack 

- ArgoCD for deployment, 
- [Kube-Prometheus-Stack](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack)
- ObervIQ for logging




