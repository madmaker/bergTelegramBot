#Docker Letsencrypt cert issuer

Issues SSL certificate

1. Upload all files to server
2. Update `example.com` in `data/nginx/app.conf` and `init-letsencrypt.sh` to your real domain name
3. Run `chmod +x init-letsencrypt.sh`
4. Run `sudo ./init-letsencrypt.sh`
5. Run `docker-compose up`

That's it
