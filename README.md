# 学習資料
- [Developing a Single Page App with Flask and Vue.js](https://testdriven.io/blog/developing-a-single-page-app-with-flask-and-vuejs/)  <- このリポジトリでメインで使用
- [FlaskとVue.jsでSPA Webアプリ開発](https://qiita.com/y-tsutsu/items/67f71fc8430a199a3efd)
- [Vue.js(vue-cli)とFlaskを使って簡易アプリを作成する【前半 - フロントエンド編】](https://qiita.com/mitch0807/items/2a93d93adbf6b5fc445c)
- [Vue.js(vue-cli)とFlaskを使って簡易アプリを作成する【後半 - サーバーサイド編】](https://qiita.com/mitch0807/items/c2e84beee6c9a61e86cd)



# Flask setup
## Install Python3.11.3
```bash
(pyenv install --list | grep 3.11.3)
pyenv install 3.11.3
```
## Install python package
```bash
python3.11 -m venv venv
source venv/bin/activate
python3.11 -m pip install -r requirements.txt
```
## Run the app
```bash
flask run
```

# Vue setup
## Install dependencies, and then fire up the development server
```bash
cd client
npm install
npm run dev
```