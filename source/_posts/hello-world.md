---
title: Hello World
---
<div class="aplayer" data-id="26237342" data-server="netease" data-type="song" data-mode="single"></div>


Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

<!-- more -->

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)


## Use [APlayer-MetingJS](https://github.com/metowolf/MetingJS/)

### Load JS script

Add in `themes\next\layout\_partials\head\head.swig`

``` html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aplayer@1.7.0/dist/APlayer.min.css">
<script src="https://cdn.jsdelivr.net/npm/aplayer@1.7.0/dist/APlayer.min.js"></script>
```

Add in `themes\next\layout\_partials\footer.swig`

``` html
<script src="https://cdn.jsdelivr.net/npm/meting@1.1.0/dist/Meting.min.js"></script> 
```

### Use in document

Add code where you want to show music player.

``` html
<div class="aplayer" data-id="26237342" data-server="netease" data-type="song" data-mode="single"></div>
```

More options: [MetingJS-Options](https://github.com/metowolf/MetingJS#option)