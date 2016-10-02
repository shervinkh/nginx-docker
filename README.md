# My nginx Server Docker
My nginx proxy server
- Run with `docker run --detach --tty --restart=always --name=nginx -v /home/user/nginx/log:/var/log -v /home/user/nginx/servers:/etc/nginx/servers -v /home/user/nginx/www:/www --link mail-server:mail-server --link duplicati:duplicati --link dockerui:dockerui -p 80:80 shervinkh/nginx` (Link all necessary containers)

