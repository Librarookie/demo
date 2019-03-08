# demo
# 这是连接练习库


# 连接空库
git init 
touch fn
echo 11 > fn
git remote add origin https://github.com/{username}/{repoName}.git
git add .
git commit -m "提交描述"
git push origin master

# 连接已经存在的github库
在workspace中先初始化
git init 
git clone rpeoUrl
cd repoName
