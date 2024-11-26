## Git基本指令

### 1. 下载repo

```bash
git clone <repo-name>
```

### 2. 查找/切换branch

#### - 在本地查找

```bash
git branch
```

#### - 切换到本地的branch

```bash
git checkout <branch-name>
```

#### - 在云端查找

```bash
git branch -r
```

#### - 切换到云端的branch

```bash
git checkout -b <branch-name> origin/<branch-name>
```

### 3. 删除不想push的改动

```bash
git stash
```

### 4. 从云端更新

```bash
git pull origin <branch-name>
```

### 5. 执行 node server.js 时出现sqlite3错误

```bash
npm rebuild sqlite3
```
