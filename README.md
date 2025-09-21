AI_Agent_LangGraph/
│
├── .env                        # Chứa OPENAI_API_KEY (đã ignore)
├── .gitignore                  # Ignore .env, cache, venv, ...
├── requirements.txt            # Danh sách dependencies
├── README.md                   # Hướng dẫn chạy
│
├── script/
│   └── ChatBot/
│       ├── main.py             # File chạy chính (Gradio UI)
│       ├── agent.py            # Định nghĩa agent, graph, state
│       ├── tools.py            # Các tool (update, save, ...)
│       ├── config.py           # Load .env, setup OpenAI, config
│       ├── prompts.py          # System prompt, template
│       ├── __init__.py
│
├── data/
│   └── drafts/                 # Nơi lưu các file .txt (output)
│
└── notebooks/
    └── dev.ipynb               # Notebook thử nghiệm (LangGraph, tool call demo)
