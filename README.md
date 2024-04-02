# azure-openai-async-mod-filter
Azure OpenAI Service の [非同期修正フィルター](https://learn.microsoft.com/azure/ai-services/openai/concepts/content-filter?tabs=warning%2Cpython-new#content-streaming)機能の実験用サンプル

デザインは Azure-Samples の chatgpt-quickstart を使用しています。<br>
https://github.com/Azure-Samples/chatgpt-quickstart

## 前提条件
- Python ≥ 3.10

## 使用法
1. `AZURE_OPENAI_ENDPOINT` と `AZURE_OPENAI_KEY` を環境変数にセット
1. Python 仮想環境を作成し有効化

```cmd
cd azure-openai-async-mod-filter
python -m venv .venv
.venv\Scripts\activate.bat
```

2. Python ライブラリをインストールして Quart サーバーを起動
```cmd
pip install -r requirements.txt
python app.py
```
