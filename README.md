## 手順
# react app create
npm install --global create-react-app

# add allop & graphql
yarn add apollo-boost@0.1.16 graphql@14.0.2 react-apollo@2.1.11


# .envの設定
echo REACT_APP_GITHUB_TOKEN= ["設定したTOKEN"] > .env.development.local

# githubの設定
Settings -> Personal access tokensで対応させるappの登録 && public_repoを許可
