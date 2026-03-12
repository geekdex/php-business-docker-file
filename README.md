# PHP Docker Images

Production-ready PHP Docker images built on Alpine Linux.

[中文版本](README.zh_CN.md)

## Available Images

- `8.2-fpm-alpine` - PHP 8.2 FPM
- `8.5-fpm-alpine` - PHP 8.5 FPM

## Usage

```bash
docker pull registry.cn-guangzhou.aliyuncs.com/geekpub/php:8.2-fpm-alpine
docker pull registry.cn-guangzhou.aliyuncs.com/geekpub/php:8.5-fpm-alpine
```

## Building

Images are automatically built and pushed to Aliyun Registry when Dockerfile changes are pushed to `main` branch.

Each directory's Dockerfile is tagged with its directory name.
