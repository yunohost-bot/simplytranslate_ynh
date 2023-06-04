If you install this app in a sub-path, the favicon is not gonna work because some limitation. If you really want to use the favicon, make sure that `__DOMAIN__/static/favicon.ico` isn't used by any other app, then change the nginx conf in `/etc/nginx/conf.d/__DOMAIN__.d/__ID__.conf` and add this:
```
location /static/favicon.ico {
	root __INSTALL_DIR__/simplytranslate/static/favicon.ico;
}
```
Then, reload nginx `systemctl reload nginx`.