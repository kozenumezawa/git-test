# 1つ目のコミット
git clone
git add .
git status
git commit
git log --graph

# 2つ目のコミット
git add memo.md
git commit -m "update"
git log --graph

# remoteの確認
git remote -v
git push origin master
githubの確認

# プルリクの書き方
git branch test
git branch
git checkout test
vim test.md
