## Getting started

```bash
python3 -m venv .venv
source .venv/bin/active
pip install --upgrade pip pipenv
pipenv sync
pipenv shell

echo "API_URL=https://[blueant-host]/blueant/services/" > config.py

./run.sh # Start development server
```