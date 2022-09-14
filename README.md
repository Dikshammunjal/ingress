# ingress 
run ns.yaml
run svc3.1.yaml
run deploy3.1yaml in this order




# on running curl www.intellectfabric.io 308 redirect permanent error coming on customer tenancy . we resiolved by adding nginx.ingress.kubernetes.io/ssl-redirect: "false"
in ingress file under annotations/.
