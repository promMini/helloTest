## Copilot instructions (repo-specific)

This repo was minimal; the agent added a small Flask example under `example_flask/` to make local testing easier.

Quick commands (from repo root):

```bash
# Install and run example locally
python3 -m venv .venv
source .venv/bin/activate
cd example_flask
pip install -r requirements.txt
flask run

# Run tests
pytest example_flask -q

# Build Docker image
docker build -t example_flask:latest ./example_flask
```

CI: see `.github/workflows/python-app.yml` which runs pytest on the example.
