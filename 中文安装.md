git clone --recurse-submodules https://gh-proxy.com/https://github.com/NousResearch/hermes-agent.git
cd  hermes-agent
.venv\Scripts\activate
pip install -e ".[all]"
hermes model
打入24
(○) 24. Custom endpoint (enter URL manually)
Custom OpenAI-compatible endpoint configuration:

API base URL [e.g. https://api.example.com/v1]: http://127.0.0.1:11434/v1
API key [optional]:
Verified endpoint via http://127.0.0.1:11434/v1/models (2 model(s) visible)
  Available models:
    1. gemma4:e4b
    2. gemma4:26b
按你自已的东东选 象我的是打入1或2
Context length in tokens [leave blank for auto-detect]:直接回车
ok了 这次直接打入  hermes 就看到了
