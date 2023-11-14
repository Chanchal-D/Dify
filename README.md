**Dify** is an easy-to-use LLMOps platform that empowers more people to create sustainable, AI-native applications. With visual orchestration for various application types, Dify offers out-of-the-box, ready-to-use applications that can also serve as Backend-as-a-Service APIs. Unify your development process with one API for plugins and dataset integration, and streamline your operations using a single interface for prompt engineering, visual analytics, and continuous improvement.

Applications created with Dify include:

Out-of-the-box websites supporting form mode and chat conversation mode
A single API encompassing plugin capabilities, context enhancement, and more, saving you backend coding effort
Visual data analysis, log review, and annotation for applications

## Highlighted Features
**1. LLMs support:** Choose capabilities based on different models when building your Dify AI apps. Dify is compatible with Langchain, meaning it will support various LLMs. Currently supported:

- [x] **OpenAI**: GPT4, GPT3.5-turbo, GPT3.5-turbo-16k, text-davinci-003 
- [x] **Azure OpenAI Service**
- [x] **Anthropic**: Claude2, Claude-instant
- [x] **Replicate**
- [x] **Hugging Face Hub**
- [x] **ChatGLM**
- [x] **Llama2**
- [x] **MiniMax**
- [x] **Spark**
- [x] **Wenxin**
- [x] **Tongyi**


We provide the following free resources for registered Dify cloud users (sign up at [dify. ai](https://dify.ai)):
* 200 free OpenAI queries to build OpenAI-based apps
  
**2. Visual orchestration:** Build an AI app in minutes by writing and debugging prompts visually.

**3. Text embedding:** Fully automated text preprocessing embeds your data as context without complex concepts. Supports PDF, TXT, and syncing data from Notion, webpages, and APIs.

**4. API-based:**  Backend-as-a-service. Access web apps directly or integrate via APIs without complex backend setup.

**5. Plugins:** Dify "Smart Chat" now supports first-party plugins like web browsing, Google search, and Wikipedia to enable online lookup, analyzing web content, and explaining the AI's reasoning process conversationally.

**6. Team workspaces:** Team members can join workspaces to collaboratively edit, manage, and use team AI apps.

### Quick Start

The easiest way to start the Dify server is to run our [docker-compose.yml](docker/docker-compose.yaml) file. Before running the installation command, make sure that [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) are installed on your machine:

```bash
cd docker
docker-compose up -d
```

After running, you can access the Dify dashboard in your browser at [http://localhost/install](http://localhost/install) and start the initialization installation process.

### Configuration

If you need to customize the configuration, please refer to the comments in our [docker-compose.yml](docker/docker-compose.yaml) file and manually set the environment configuration. After making the changes, please run 'docker-compose up -d' again.

## Roadmap

Features under development:

- **Datasets**, supporting more datasets, e.g. syncing content from Notion or webpages
We will support more datasets, including text, webpages, and Notion content. Users can build AI applications based on their own data sources.
- **Plugins**, introducing ChatGPT Plugin-standard plugins for applications, or using Dify-produced plugins
We will release plugins complying with ChatGPT standard, or Dify's own plugins to enable more application capabilities. 

## Lint Code
If your IDE is VSCode, rename `web/.vscode/settings.example.json` to `web/.vscode/settings.json` for the lint code setting.

## Documentation
Visit readme to view the full documentation.


