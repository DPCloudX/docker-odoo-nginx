docker-odoo-nginx
=================

[![Join the chat at https://gitter.im/DPCloudX/docker-odoo-nginx](https://badges.gitter.im/DPCloudX/docker-odoo-nginx.svg)](https://gitter.im/DPCloudX/docker-odoo-nginx?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

NGINX Reverse Proxy
-------------------

This nginx based reverse proxy is optimized for running an Odoo SaaS solution.

### Running the container

For easier creation of nginx container we have created a small bash script.
You can get this script by taking the github repository with

    git clone https://github.com/jamotion/docker-odoo-nginx
    cd docker-odoo-nginx

or by downloading the script only

    wget https://raw.githubusercontent.com/jamotion/docker-odoo-nginx/master/docker-run-nginx

Then make the file executable

    chmod u+x docker-run-nginx

And now run the script followed by the name which is applied to the container

    ./docker-run-nginx odoo.nginx
