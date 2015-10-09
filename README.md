### Docker typescript container based on the [Alpine Linux](alpinelinux.org) 


##### **How to use:**
  - **If you want to run node or a typescript stuff**
    - Make an alias:  
     `alias tsc="docker run --rm -v $(pwd):/home/developer/workspace jare/typescript tsc"`
    - Have fun!  `tsc -h`
  - **Also you can use this image as a docker volume. [See `jare/vim-bundle`](https://registry.hub.docker.com/u/jare/vim-bundle/)**
