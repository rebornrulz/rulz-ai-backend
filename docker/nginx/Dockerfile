FROM nginx:1.25.1-perl
COPY entrypoint.sh /entrypoint.sh
COPY default.conf.template /etc/nginx/conf.d/default.conf.template
CMD ["/bin/bash", "/entrypoint.sh"]
