# Example Flask App

簡單的 Flask 範例應用程式，用於示範如何啟動、測試，以及如何把指令加入 copilot 指引檔。

啟動（開發）：

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
FLASK_APP=app.py FLASK_ENV=development flask run
```

測試：

```bash
pytest -q
```
