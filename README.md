# docker-lemp-wordpress
Docker LEMP Project for WordPress

## ให้สิทธิ์การใช้งาน docker เกี่ยวกับการเขียนข้อมูล
`git clone https://github.com/PanupongDeve/docker-nginx-wordpress.git`
`cd docker-nginx-wordpress`
`find www -type d -exec chmod 707 {} \;`
`find www -type f -exec chmod 707 {} \;`

### runserv
docker-compose up -d

### closeserv
docker-compose down

## ขอบคุณบทความ
https://medium.com/@teamteam/%E0%B8%95%E0%B8%B4%E0%B8%94%E0%B8%95%E0%B8%B1%E0%B9%89%E0%B8%87-wordpress-%E0%B8%9A%E0%B8%99-docker-lemp-stack-b61623ca28e3

https://gist.github.com/dianjuar/1b2c43d38d76e68cf21971fc86eaac8e
