### Docker TypeScript container based on the [Alpine Linux](alpinelinux.org) 

`jare/typescript:latest`  

##### **How to use:**
  - **If you want to run node or a typescript stuff:**
    - Make an alias:  
     `alias tsc='docker run -u 1000:1000 --rm -v $(pwd):/home/developer/workspace milanaleksic/typescript tsc'`
    - Have fun!  `tsc -h`
  - **Or you can use this image as a docker volume. [See `jare/vim-bundle`](https://registry.hub.docker.com/u/jare/vim-bundle/)**

##### **bundle:**
  - **[`tsd`](https://www.npmjs.com/package/tsd)** 
  - **[`http-server`](https://www.npmjs.com/package/http-server)** 
