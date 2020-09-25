# 使用方法


添加 src-git test https://github.com/Beginner-Go/my-package.git 到 OpenWRT源码根目录feeds.conf.default文件

然后执行

```bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```
