---
title: "My First Post"
date: 2019-01-25T00:37:21+09:00
draft: true
---

```sh
$ hugo new site hugo-quickstart
```

```sh
$ cd hugo-quickstart/
```

```sh
$ git init
$ git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
$ echo 'theme = "ananke"' >> config.toml
```

```sh
$ hugo new posts/my-first-post.md
$ hugo server -D
^C
```

```sh
$ git remote add origin https://github.com/mizuo/hugo-quickstart.git
$ git push -u origin master
```

```sh
$ git submodule add -b master https://github.com/mizuo/mizuo.github.io.git public
```
