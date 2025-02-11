# Expense bot on Telegram

| Setup VPS with GPU | thuegpu.vn |  |  |
| --- | --- | --- | --- |
| Install NoAI | [https://github.com/thangnch/MIAI_n8n_dockercompose/blob/main/setup guide.md](https://github.com/thangnch/MIAI_n8n_dockercompose/blob/main/setup%20guide.md) | `curl -L https://bit.ly/n8n_install_noai | sh` |  |
| Bật ngrok | `sh <(curl -L https://bit.ly/n8n_with_ngrok)` |  |  |
| Install Ollama | curl -fsSL [https://ollama.com/install.sh](https://ollama.com/install.sh) | sh |  |  |
| Start Ollama service | systemctl status ollama |  |  |
| Export model path | export OLLAMA_MODELS=/usr/share/ollama/.ollama/models |  |  |
| Ollama serve anywhere IP/Port | export OLLAMA_HOST=0.0.0.0:8080 |  |  |
| Ollama serve | ollama serve | Then open a new terminal. Can use nohup to continue in same window |  |
| Load model to local | `ollama run deepseek-r1:8b` | [https://ollama.com/library/deepseek-r1](https://ollama.com/library/deepseek-r1) |  |
| Check model list | Access IP:Port/v1/models | curl -L http://localhost:8080/v1/models |  |
| Import Workflow | From desktop | Làm bot expense |  |
|  | Set credential cho GSheet | Detail in list https://www.youtube.com/watch?v=sks1uIA70ok&list=PLZPCoTKpEddD9_FGo_j_coJSwcdOUompQ |  |
|  | Tạo bot trên Telegram |  |  |
|  | Tạo file chi tiêu |  |  |
|  | Test WF |  |  |