
### UCBS
admin password
admin-01@example.com : P@ssw0rd

### DB status check
“docker exec oracle19c lsnrctl status”

### Local URL
[http://kmitl-local-admin-portal.skilllane.net:9080/transfer](http://kmitl-local-admin-portal.skilllane.net:9080/transfer)
  
### Api six dev
admin key: [http://10.0.0.39:9180/ui](http://10.0.0.39:9180/ui) | edd1c9f034335f136f87ad84b625c8f1
  

## FortiClient
name: SKL-NCBS-Server 
gateway: 58.137.120.130:10443 
username: ncbs_vpn02 
port: 10443
password: T320Ro)^
  
### Swagger
[https://dev-api-gateway.skilllane.net/ncbs/api/docs](https://dev-api-gateway.skilllane.net/ncbs/api/docs)
https://dev-api-gateway.skilllane.net/ucbs/api/docs

### FE deploy
NEXT_PUBLIC_API_BASE_URL=[https://dev-api-gateway.skilllane.net/ucbs/api](https://dev-api-gateway.skilllane.net/ucbs/api)

Prompt

  

In admin achievement record controller. Create the new api to get the achievement record pagination

  

Api details

- GET /admin/achievement-records

- no request

- response common filed as the same as the credit transfer request pagination res

- respone data item seem like

- flow: controller -> query handler -> query the data direct from db not use the repository -> map the data to response dto

Todo
