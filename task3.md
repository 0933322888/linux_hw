   30  useradd boris -G sudo | history | tail -1 >> task3.md
   40  touch /etc/yum.repos.d/nginx.repo
   41  vim /etc/yum.repos.d/nginx.repo
   42  apt-get install nginx
   43  yum install nginx
   44  systemctl start nginx
   45  curl localhost
   46  ps aux
   47  kill -9 1844
