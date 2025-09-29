customized kube-ovn for baremetal node

following env variables should be declared befor install
```bash
ENABLE_BAREMETAL=true
EXTERNAL_KUBE_API_SERVER_HOST={kube-api-server-lb-fip}
EXTERNAL_OVN_DB_IP={ovn-db-lb-fip}

bash install.sh
```
