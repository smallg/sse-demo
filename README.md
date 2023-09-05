# sse-demo
Server Sent Event demo

```bash
curl -H Accept:text/event-stream http://localhost:3000/events

curl -X POST \
 -H "Content-Type: application/json" \
 -d '{"info": "111asdfasdfShark teeth are embedded in the gums rather than directly affixed to the jaw, and are constantly replaced throughout life.", "source": "https://en.wikipedia.org/wiki/Shark"}'\
 -s http://localhost:3000/fact
{"info":"111asdfasdfShark teeth are embedded in the gums rather than directly affixed to the jaw, and are constantly replaced throughout life.","source":"https://en.wikipedia.org/wiki/Shark"}%
```
