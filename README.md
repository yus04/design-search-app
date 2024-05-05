# design-search-app
デザイン検索を実装するためのアプリです。
Azure AI Search のカスタムスキルで、GPT-4V によるエンリッチメントを実装するための Azure Functions のコードになります。

## 準備
Azure OpenAI Search に関連した以下の環境変数を Azure Portal から設定する。
(ローカル実行の場合は、`local.settings.json` の `Values` に環境変数を設定する。)
- `AZURE_OPENAI_API_VERSION`
- `AZURE_OPENAI_SERVICE`
- `AZURE_OPENAI_TOKEN`
- `GPT_DEPLOYMENT`