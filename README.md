# Dify
About The next-gen development platform - Easily build and operate generative AI applications. Create Assistants API and GPTs based on any LLMs.

Applications created with Dify include:

Out-of-the-box web sites supporting form mode and chat conversation mode
A single API encompassing plugin capabilities, context enhancement, and more, saving you backend coding effort
Visual data analysis, log review, and annotation for applications

## Highlighted Features
**1. LLMs support:** Choose capabilities based on different models when building your Dify AI apps. Dify is compatible with Langchain, meaning it will support various LLMs. Currently supported:

- [x] **OpenAI**: GPT4, GPT3.5-turbo, GPT3.5-turbo-16k, text-davinci-003 
- [x] **Azure OpenAI Service**
- [x] **Anthropic**: Claude2, Claude-instant
- [x] **Replicate**
- [x] **Hugging Face Hub**

We provide the following free resources for registered Dify cloud users (sign up at [dify.ai](https://dify.ai)):
* 200 free OpenAI queries to build OpenAI-based apps

  
**2. Visual orchestration:** Build an AI app in minutes by writing and debugging prompts visually.

**3. Text embedding:** Fully automated text preprocessing embeds your data as context without complex concepts. Supports PDF, TXT, and syncing data from Notion, webpages, APIs.

**4. API-based:**  Backend-as-a-service. Access web apps directly or integrate via APIs without complex backend setup.

**5. Plugins:** Dify "Smart Chat" now supports first-party plugins like web browsing, Google search, Wikipedia to enable online lookup, analyzing web content, and explaining the AI's reasoning process conversationally.

**6. Team workspaces:** Team members can join workspaces to collaboratively edit, manage, and use team AI apps.

**7. Data labeling and improvement:**  Visually inspect AI app logs and improve data via labeling. Observe the AI's reasoning process to continuously enhance performance. (Coming soon)

### Quick Start

The easiest way to start the Dify server is to run our [docker-compose.yml](docker/docker-compose.yaml) file. Before running the installation command, make sure that [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) are installed on your machine:

```bash
cd docker
docker compose up -d
```

After running, you can access the Dify dashboard in your browser at [http://localhost/install](http://localhost/install) and start the initialization installation process.
