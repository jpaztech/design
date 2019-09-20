# hexo-theme-jpaztech

hexo theme for jpaztech tech blog

> forked from [hexo-theme-landscape](https://github.com/hexojs/hexo-theme-landscape)

## Set Up

```sh
git clone https://github.com/jpaztech/hexo-theme-jpaztech.git themes/jpaztech
npm i -D hexo-generator-feed
npm i -D jpaztechid/hexo-helper-github-issues hexo-generator-root-tag
```

## hexo config.yml


```yml
root_tag_generator:
  root_tag_names:
    - Information
    - VM
    - Storage
    - Network
    - OSS
    - Other
    - Archive
  sub_tag_limit: 20
  
github:
  url: https://jpaztech.github.io/blog/
  posts_dir: articles

```
