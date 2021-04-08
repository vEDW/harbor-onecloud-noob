# harbor-onecloud-noob
Harbor deployment on Onecloud for dummies

Pre-reqs : 
1) Helm cli: https://helm.sh/docs/intro/install/
2) Harbor helm : 
    helm repo add harbor https://helm.goharbor.io
    helm fetch harbor/harbor --untar

3) cd harbor
4) create values_foor_onecloud.yaml
5) helm install harbor -n harbor harbor/harbor --values values_for_onecloud.yaml
6) 
