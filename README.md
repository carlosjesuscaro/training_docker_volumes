# Command examples:
-  `docker run --name=cex4 -it -v ./data:/data/ abc:vb3`
- Using dockeer volumes:
  - `docker volume creatre vol_example`
  - `docker run --name=cex5 -it -v vol_example:/data/ abc:vb3 `
  - The docker volume files are stored in `/var/lib/docker/volumes/vol_example/_data`