### Docker TypeScript container based on the [Alpine Linux](alpinelinux.org) 

`jare/typescript:latest`  
[![jare/typescript:latest](https://badge.imagelayers.io/jare/typescript:latest.svg)](https://imagelayers.io/?images=jare/typescript:latest 'jare/typescript:latest') 

##### **How to use:**
  - **If you want to run node or a typescript stuff:**
    - Make an alias:  
     `alias tsc="docker run --rm -v $(pwd):/home/developer/workspace jare/typescript tsc"`
    - Have fun!  `tsc -h`
  - **Also you can use this image as a docker volume. [See `jare/vim-bundle`](https://registry.hub.docker.com/u/jare/vim-bundle/)**

##### **bundled:**
  - **[`tsd`](https://www.npmjs.com/package/tsd)** 
  - **[`http-server`](https://www.npmjs.com/package/http-server)** 
