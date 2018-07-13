# docker-compose-nginx
Http/https docker service for multiple sites

## Installation
1. Install `docker` and `docker-compose` on your os
2. Clone repository `git clone https://github.com/DylanDelaporte/docker-compose-nginx.git`
3. Add your __hosts config__ (by default you have one which redirect http to https)
4. (Optional) Generate certificates for __https hosts__, I strongly recommand to use __let's encrypt__ and put them into __certs directory__
5. Add content inside __html directory__
6. Be sure that everything has been well linked up inside the host files with right path (certicates, path to html files)
7. Start the service with command `docker-compose up`

Also: You can stop with `Ctrl+C` ou with `docker-compose stop` inside the service directory
