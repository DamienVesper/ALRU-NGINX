<div align="center">
    <h1>NGINX</h1>
    <p>NGINX site configurations for the Alliance Reunited webserver.</p>
</div>

## Updating Configuration
To update a site's configuration, simply edit the file and commit it to GitHub.

## Deployment
* SSH into the webserver.
* Navigate to `/etc/nginx/sites-enabled`.
* Run `git pull` to update the configuration.
* Optionally, test the configuration with `sudo -s nginx` (if NGINX is currently running, may conflict).
* Restart NGINX with `systemctl restart nginx` to apply the new changes.
