# init
```bash
git clone https://github.com/DarkNoah/wechat-mcp
uv sync
```
you need to login wechat pc first

# start sse
```bash
uv run main.py --wxid "your_wechat_id" --port 8000
```

# tool list
- get_wechat_message
- get_last_wechat_message
- sql_wechat_message
- send_wechat_message
  
# client config
## sse
http://127.0.0.1:8000/sse

# start stdio
uv run main.py --wxid "your_wechat_id" --transport stdio