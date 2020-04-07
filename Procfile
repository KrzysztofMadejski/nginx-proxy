nginx: nginx
dockergen: docker-gen -watch -notify "nginx -s reload" /app/nginx.tmpl /etc/nginx/conf.d/default.conf
# TODO run nginx -T to test configuration, fail run if it fails