# 実装手順を記録。

## 環境構築
### GitBash
    ssh-keygen -t rsa -b 4096 -C "4ki.takamatsu@gmail.com"
    vi ~/.bash_profile
        eval "$(ssh-agent -s)"
        ssh-add ~/.ssh/github_key
    source ~/.bash_profile
    ssh -T git@github.com
    git clone git@github.com:shikimaki/shikimaki.github.io.git

## ポートフォリオ作成
**注意!!rootファイル名はindex.htmlである必要がある。**
