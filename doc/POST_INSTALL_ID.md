Jika Anda memasang aplikasi ini di sub-jalur, maka faviconnya tidak akan tertampil karena beberapa batasan. Jika Anda benar-benar ingin menampilkan favicon, maka pastikan terlebih dahulu `__DOMAIN__/static/favicon.ico` tidak dipakai oleh aplikasi lain, setelah itu sunting konfigurasi nginx di `/etc/nginx/conf.d/__DOMAIN__.d/__ID__.conf` dengan menambah:
```
location /static/favicon.ico {
	root __INSTALL_DIR__/simplytranslate/static/favicon.ico;
}
```
Setelah itu, silakan dimuat ulang nginxnya `systemctl reload nginx`.
