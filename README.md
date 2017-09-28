# kodexplorer

This is simply a repo to hold the Dockerfile for KodExplorer

* KodExplorer: https://github.com/kalcaddle/KodExplorer
* Semi-fork from https://hub.docker.com/r/yangxuan8282/kodexplorer/

`sudo docker run -d -p 0.0.0.0:8080:80 --name my_kodexplorer -v </path/to/share>:/var/www/html/data/User/admin/shared --restart always flamableconcrete/kodexplorer`