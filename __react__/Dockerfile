FROM node:lts-alpine

# カレントワーキングディレクトリとして 'app' フォルダを指定する
WORKDIR /app

# プロジェクトの依存ライブラリをインストールする
RUN apk update && \
  yarn global add create-react-app
