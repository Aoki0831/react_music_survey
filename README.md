[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

# react_music_survey

## Spotify から楽曲情報をとってきて表示するアプリケーション

### 構成

- フロント
  - React と TypeScript(no Next.js)
  - CSS フレームワーク
    - Chakra UI
- サーバー
  - Python の FastApi

### 入力コマンド

- フロント側
  - npx create-react-app frontend --template typescript
  - npm install axios
  - npm install @types/react-router-dom
  - npm i @chakra-ui/react @emotion/react@^11 @emotion/styled@^11 framer-motion@^6
    - yarn にすればよかったかも
- サーバー側
  - pip install virtulenv
    - これはグローバル
  - cd backend
  - python -m venv .venv
  - .\.venv\Scripts\activate
  - pip install fastapi[all]
-

### 参考ページ

- [FastAPI + React でフルスタックアプリを作成する](https://qiita.com/miruon/items/c7243d7adcd6d38b3829)
- [【完全版】React + FastAPI で開発するモダンな web アプリ](https://zenn.dev/sawao/articles/15a9cf0e3360a7)
- [FastApi チュートリアル](https://fastapi.tiangolo.com/ja/tutorial/first-steps/)
