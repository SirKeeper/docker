To Build this image :

sudo docker build -t pacolain/nginx .

To launch this docker :

sudo docker run -d -p 80 --name website -v $PWD/website:/var/www/html/website pacolain/nginx nginx
