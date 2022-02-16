# Dockerの練習
### インストール
<pre>
cd /home
git clone https://github.com/yangjiri/Docker-Practice.git
cd Docker-Practice/
</pre>
### Run
<pre>
# Login For public Docker Repository
docker login
docker pull tnvjwldms/docker-practice
docker run -p 80:80 -v /home/Docker-Practice/Project:/var/www/html tnvjwldms/docker-practice
</pre>
