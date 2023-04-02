## useful-debian-commands


/etc/init.d/networking stop && /etc/init.d/networking start   - перезагрузка сети

ifconfig enp0s3 192.168.0.20 netmask 255.255.255.0 – сменить ip, перезагрузка сети не нужна

hostnamectl set-hostname       <*>   - установить имя хоста

sudo service apache2 stop && sudo systemctl restart nginx

sudo fuser -k 80/tcp && sudo systemctl restart nginx

sudo rm /etc/nginx/sites-enabled/default && sudo service nginx restart

nginx -t -c /etc/nginx/nginx.conf   - проверка корректности синтаксиса

eval "$(ssh-agent -s)"

ssh-add /home/demin/git-homework/github

git clone

cp -r /media/sf_Share/10.5-haproxy-nginx/  /home/demin/git-homework/homework-10.5/img/

nano /home/demin/git-homework/homework-10.3/README.md

git status

git add img/

git commit -am "added screenshots for cases NN 3,4,5"

git push
