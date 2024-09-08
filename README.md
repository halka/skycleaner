# skycleaner
Delete your posts and reposts on Bluesky.

## Prepare
0. (Recommend) Setup venv
1. Install Required packages
```bash
    pip install -r requirements.txt
```
2. Edit config.json

**Use App Password for safety.**
```json
   {
    "username": "your_handle.bsky.social",
    "password": "ISSUED APP PASSWORD",
    "days_to_keep": {
      "posts": 20,
      "reposts": 20 
    }
   }
```

### days_to_keep
Avoid deleting posts/reposts configured duration. 

Set as **days**.

## Run
**YOU CAN NEVER GO BACK**
```bash
python cleaner.py
```

## Thanks
- [BLUESKY POST DELETER](https://deleter.shiroyama.us/)
- [sleep/deleteskee: a little script for automagically deleting blue sky (atproto) posts and reposts - Codeberg.org](https://codeberg.org/sleep/deleteskee)
