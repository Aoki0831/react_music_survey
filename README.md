# react_music_survey

## Spotify から楽曲情報をとってきて表示するアプリケーション

### 構成

- フロント
  - React と TypeScript(no Next.js)
  - なんかしらの CSS フレームワーク
- サーバー
  - Python の FastApi

### 入力コマンド

- フロント側
  - npx create-react-app frontend --template typescript
  - npm install axios
  - npm install @types/react-router-dom
  - npm i @chakra-ui/react @emotion/react@^11 @emotion/styled@^11 framer-motion@^6
- サーバー側
  - pip install virtulenv
    - これはグローバル
  - cd backend
  - python -m venv .venv
  - .\.venv\Scripts\activate
  - pip install fastapi[all]
  - pip install black
-

### 参考ページ

- [FastAPI + React でフルスタックアプリを作成する](https://qiita.com/miruon/items/c7243d7adcd6d38b3829)
