## Welcome to my github

- Today [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fgojunghyo&count_bg=%233D43C8&title_bg=%2317DDB2&icon=java.svg&icon_color=%23E7E7E7&title=number+of+visitors&edge_flat=false)](https://hits.seeyoufarm.com)

- ✨Let me introduce myself ✨

# MY STAT
- ![STAT](https://github-readme-stats.vercel.app/api?username=gojunghyo&show_icons=true&theme=cobalt)




## My Blog

- ✨ Blog 개인블로그 [Link](https://blog.naver.com/gojgho "my blog link") 
> This is my blog where I review what I have studied.


## Plugins

Plugins from my GitHub repository

| Plugin | README |
| ------ | ------ |
| 백준 | [/baekjoon/README.md][BJ] |
| 프로그래머스 | [plugins/github/README.md][PlGh] |
| 코딜리티 | [plugins/googledrive/README.md][PlGd] |
| MSA | [plugins/onedrive/README.md][PlOd] |
| MY-Project-one | [plugins/medium/README.md][PlMe] |
| MY-Project-two | [plugins/googleanalytics/README.md][PlGa] |

## Tech

Dillinger uses a number of open source projects to work properly:

- [JAVA] - I most spoken language
- [SPRING BOOT] - Frequently used frameworks
- [MYSQL] - Use as a relational db
- [MSA Arcitecture] - recently interested
- [CPP] - Use for coding test

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=gojunghyo&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)



## Test Installation

Use Another my repository requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```



## Test Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Test Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Test Docker

Dillinger is very easy to install and deploy in a Docker container.


```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.


```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [BJ]: <https://github.com/gojunghyo/baekjoon/blob/main//README.md>
   [PlGh]: <https://github.com/gojunghyo/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/gojunghyo/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/gojunghyo/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/gojunghyo/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/gojunghyo/dillinger/blob/master/plugins/googleanalytics/README.md>
