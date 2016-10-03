# My nginx Server Docker
My nginx proxy server
- Run with `docker run --detach --tty --restart=always --network=my_network --name=nginx -v /home/user/nginx/log:/var/log -v /home/user/nginx/servers:/etc/nginx/servers -v /home/user/nginx/www:/www -p 80:80 shervinkh/nginx` (All related containers should be connected to the same network)

