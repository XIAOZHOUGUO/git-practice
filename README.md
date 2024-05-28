### git-practice

#### 1. 创建一个本地仓库

```
mkdir git-practice
cd git-practice
git init
```

#### 2. 创建一个文件并提交

```
echo "hello world" > hello.txt
git add hello.txt
git commit -m "add hello.txt"
```

#### 3. 查看提交记录

```
git log
```

#### 4. 创建一个远程仓库

```
    git remote add origin https://github.com/your-username/git-practice.git
```

#### 5. 推送到远程仓库

```
    git push -u origin master
```

#### 6. 克隆远程仓库

```
    git clone https://github.com/your-username/git-practice.git
```

#### 7. 创建一个分支

```
    git checkout -b feature
`