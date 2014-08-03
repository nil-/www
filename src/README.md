The github directory overall is hosted on `/var/www/oneesama.moe` on the VPS. This directory `src/` contains any system configured files that don't already exist in `oneesama.moe`, in order for git to apply revision control for them. I apply symlinks to the following locations:

* `oneesama.moe`: `/etc/nginx/sites-enabled/oneesama.moe`
