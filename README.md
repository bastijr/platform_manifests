# anbox定制镜像源码（google源修改为清华源）
## Fetch all relevant sources
```shell
echo "export REPO_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/' "  >> .bashrc
repo init -u https://github.com/bastijr/platform_manifests.git -b anbox
repo sync -j4
```
