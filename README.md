******1.**You need to clone this repo as it is. 
**2.**and run the docker compose up -d command . 
**3.**Now go to grafana dash board
**4.**add a datasource as loki. provide loki url liek http://loki:3100
and save and test
**4.**Now again go to the datasource and check the explore option and select lable as container and it allow you to choose multiple value'" for eg your contianers name " 
**5.**Now You can see the logs in the grafana dashboard.

**Use this command if you want to reset the grafana admin passwod** 
--> grafana-cli admin reset-admin-password <newpassword>
