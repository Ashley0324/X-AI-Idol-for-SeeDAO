# X：AI Idol for SeeDAO
We built an AI Idol for SeeDAO, she will work for community management and marketing!

# For developers
This project is based on FastGPT

## Local hosting
follow the guide in https://doc.tryfastgpt.ai/docs/development/docker/

### Something you might want to know
1. KnowledgeSet: Model is required to deal with embedding, for local users, Ollama is recommended. Config Ollama in OneAPI should work. Remenber to config proxy: http://host.docker.internal:11434

2. Embedding Database: Milvus is recommended, if you want to use it, you should change docker-compose.yml file based on your DB in: https://github.com/labring/FastGPT/tree/main/files/docker

3. Free GPT to use in OneAPI: If you don't want to deal with KnowledgeSet, just use cloud free GPT like glm-4-flash(ChatGLM),Yi(Baidu)

## TODO:
This is a list for contributors to collect and finish
1. Connectors: connect to Twitter, Discord and so on.
2. Crawler: collect twitter message about SeeDAO and answer according to this agent
3. Design: SeeDAO AI Idol
4. DevOps: For now we are using FastGPT online service, self cloud host is required for future development
