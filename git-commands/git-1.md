## Git基本指令

### 1. 下载repo

```bash
git clone <repo-name>
```

### 2. 查找branch

#### - 在本地查找
```bash
git checkout <branch-name>
```

#### - 在云端查找
```bash
git branch -r
```

#### - checkout到云端的branch
```bash
git checkout -b <branch-name> origin/<branch-name>
```
