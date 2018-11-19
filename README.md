# grafana
## Run

>mkdir /home/docker/monitoring
>git clone https://github.com/13paulmurith/grafana.git
>docker-compose up -d && docker-compose stop
>mv prometheus.yml prometheus/
>docker-compose rm && docker-compose up -d

## Connect to Grafana UI : 
Access it form localhost:3000
Default login : admin
Default password : secret

## Dashboard
I've done myself a simple Dashboard, to use it import dash.json in grafana UI. It should look like this : 
![alt text](https://github.com/13paulmurith/grafana/blob/master/dash.PNG)
