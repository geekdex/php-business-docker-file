# PHP Docker 镜像

基于 Alpine Linux 的生产级 PHP Docker 镜像。

[English](README.md)

## 可用镜像

- `8.2-fpm-alpine` - PHP 8.2 FPM
- `8.5-fpm-alpine` - PHP 8.5 FPM

## 使用

```bash
docker pull registry.cn-guangzhou.aliyuncs.com/geekpub/php:8.2-fpm-alpine
docker pull registry.cn-guangzhou.aliyuncs.com/geekpub/php:8.5-fpm-alpine
```

## 构建

当 Dockerfile 变更被推送到 `main` 分支时，镜像会自动构建并推送到阿里云镜像仓库。

每个目录的 Dockerfile 会以目录名作为镜像 tag。
