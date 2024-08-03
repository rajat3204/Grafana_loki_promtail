You need to clone this repo as it is. 
and run the docker compose up -d command . 
Now go to grafana dash board
add a datasource as loki. provide loki url liek http://loki:3100
and save and test
Now again go to the datasource and check the explore option and select lable as container and it allow you to choose multiple value'" for eg your contianers name " 
Now You can see the logs in the grafana dashboard.

