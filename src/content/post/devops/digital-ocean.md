---
title: "Digital Ocean"
description: "This post showcases using the markdown admonition feature in Astro Cactus"
publishDate: "2 March 2025"
# updatedDate: "7 Jan 2025"
tags: ["devops", "linux","server","deploy"]
# coverImage:
  # src: "./cover.png"
  # alt: "Astro build wallpaper"
---

+ Droplet: Craete your Server
  - Select your: OS, Ram, Volume, Location
  - password: plain-text / pem
+ SSH Login into the droplet: `root@<ip>`
+ update the system:
  - `sudo apt update && sudo apt update`
  - reboot
+ install python & pip
  - `sudo apt install python3-pip python3-dev`
  - `sudo apt install libpq-dev postgresql postgresql-contrib`
  - `sudo apt install nginx certbot python3-certbot-nginx supervisor`
+ config posgresql
```sh
sudo -u postgres psql
> CREATE DATABASE project_1
>
```
