# Set your own auto-stop timeout

*Published 2026-07-24*

Your GPU stops after a stretch of inactivity, so you are never billed for a machine you forgot about. That timeout used to be the same for everyone. Now it is yours to set.

- Set **LLM** and **Media** timeouts independently on the **Settings** page.
- Choose anything from 5 minutes up — or switch auto-stop off entirely for long jobs.
- **Media** treats a busy ComfyUI queue as activity, so a render that runs for hours keeps the pod alive. The countdown only starts once the queue is empty.
- **LLM** counts your own session, so your timeout never cuts anyone else off.

Running out of balance always stops a GPU, whatever you choose here.

---

[All news](https://imbutus.com/news) · [imbutus.com](https://imbutus.com)
