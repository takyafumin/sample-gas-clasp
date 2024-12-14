<!--
Copyright 2023 takyafumin@gmail.com

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->
# sample-gas-clasp
GAS を ローカルで開発してみる

## 環境

- node v20
- clasp

## プロジェクト作成

```bash
# clasp でログインする
clasp login

# プロジェクト作成
# Script ID には既に作成済みのScript IDを指定すると、Google Drive からソースコードをダウンロードしてくる
npx aside init
✔ Project Title: … GAS Sample by aside
✔ Create an Angular UI? … No / Yes
✔ Generate package.json? … No / Yes
✔ Adding scripts...
✔ Saving package.json...
✔ Installing dependencies...
✔ Installing src template...
✔ Installing test template...
✔ Script ID (optional): …
✔ Script ID for production environment (optional): …
```
