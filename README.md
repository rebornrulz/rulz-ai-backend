The rulz-ai backend alternative.

## Motivation

The AI ecosystem is developed primarily around Python, and there are advantages to choosing Python as a backend.
This project is an attempt to replace only the /api/chat endpoint with a Python backend.

## Usage

```bash
# create .env and set api keys.
cp .env.example .env
```

```bash
git clone https://github.com/rebornrulz/rulz-ai.git
cd rulz-ai
make build
cd ..

# launch rulz-ai and nginx.
docker compose up -d
```

```bash
pip install -r requirements.txt
uvicorn src.main:app
```
