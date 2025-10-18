# Home Assistant Entity Renamer

## Project Overview

Python script to bulk rename Home Assistant entities and their
friendly names via WebSocket API.

## Development Setup

```bash
# Activate virtual environment
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

## Configuration

- Copy `config.py.example` to `config.py`
- Update with your Home Assistant URL and long-lived access token

## Usage

```bash
python homeassistant-entity-renamer.py input.csv
```

## Dependencies

- requests
- websocket-client
- tabulate
- argparse

## Key Files

- `homeassistant-entity-renamer.py` - Main script
- `config.py.example` - Configuration template
- `requirements.txt` - Python dependencies
