# 💫 About Me:
🔨 Applied AI engineer building agentic systems, LLM evaluation infrastructure, and production AI applications on AWS<br>
🧪 Recent work: **TerraformAgent** (multi-agent IaC generator gated on real `terraform validate`) and **EvalBench** (multi-provider eval platform with statistically honest confidence intervals)<br>
📦 I maintain **mcp-second-opinion**, an MIT-licensed MCP server on PyPI that lets any MCP-aware agent consult OpenAI, Gemini, Anthropic, and Grok mid-conversation<br>
✍️ I write about building agents on AWS at [blog.akashpersetti.com](https://blog.akashpersetti.com)<br>
💬 Ask me about LangGraph, MCP, AWS Bedrock, LiteLLM, RAG evaluation (recall@k, nDCG@k, faithfulness), and serverless Terraform CI/CD<br>
🎓 M.S. Computer Science, Indiana University Bloomington (2026)<br>
⚡ Fun fact: I built an AI version of myself that lives on my website and can answer questions about my career — go talk to it at [akashpersetti.com](https://akashpersetti.com)

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/akash-hp) [![Blog](https://img.shields.io/badge/Blog-2962FF?logo=hashnode&logoColor=white)](https://blog.akashpersetti.com) [![Dev.to](https://img.shields.io/badge/dev.to-0A0A0A?logo=devdotto&logoColor=white)](https://dev.to/akashpersetti) [![X](https://img.shields.io/badge/X-000000?logo=x&logoColor=white)](https://x.com/akash_171717) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:hadagalipersettiakash@gmail.com) [![Website](https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white)](https://akashpersetti.com)

## 🚀 Featured Projects
| Project | What it does | Stack |
|---|---|---|
| **[TerraformAgent](https://terraform-agent.akashpersetti.com)** | 6-node LangGraph pipeline turning natural-language infra requests into validated Terraform. Multi-LLM security review with veto, targeted retries on flagged domains only, gated on real `terraform fmt` + `validate` against a baked-in provider cache. 94 tests | LangGraph, FastAPI, Step Functions, Lambda, DynamoDB |
| **[EvalBench](https://evalbench.akashpersetti.com)** | Multi-provider LLM eval platform — 3 suites (structured-output reliability, latency/cost, RAG) on a shared `MetricRecord` contract. 27 runs across 75 tasks and 7 variants, with 95% Wilson intervals on every leaderboard cell. 262 tests | FastAPI, LiteLLM, Next.js, Terraform |
| **[Wingman](https://wingman.akashpersetti.com)** | Self-evaluating agent: worker-evaluator loop with up to 5 feedback retries, 5 tool domains, LangGraph state reconstructed from DynamoDB per request for serverless safety | LangGraph, FastAPI, Lambda, DynamoDB |
| **[Twin](https://akashpersetti.com)** | Streaming digital twin on my site with a public evals dashboard — recall@k and nDCG@k on 35 labeled queries per push, LLM-judged faithfulness on live traffic via an S3-event-driven judge | Bedrock, Titan embeddings, Next.js, Lambda |
| **[mcp-second-opinion](https://pypi.org/project/mcp-second-opinion)** | MIT-licensed MCP server that fans queries across four providers in parallel and returns per-call latency, tokens, and cost. Published to PyPI | Python, LiteLLM, MCP |

## ✍️ Writing — *Building Agents on AWS*
Field notes from shipping the projects above. Cross-posted to [Hashnode](https://akashpersetti.hashnode.dev), [Dev.to](https://dev.to/akashpersetti), and [CoderLegion](https://coderlegion.com/user/akashpersetti).

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1.svg?style=flat&logo=postgresql&logoColor=white) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white)

**Agentic AI & LLM Engineering**<br>
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-D97757?style=flat&logo=anthropic&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white) ![Anthropic](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white) ![LiteLLM](https://img.shields.io/badge/LiteLLM-4B32C3?style=flat&logo=litellm&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

**Cloud & DevOps**<br>
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat&logo=awslambda&logoColor=white) ![Amazon Bedrock](https://img.shields.io/badge/Bedrock-232F3E?style=flat&logo=amazonwebservices&logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=flat&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat&logo=githubactions&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=flat&logo=vercel&logoColor=white)

**Backend & Frontend**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi) ![Next JS](https://img.shields.io/badge/Next-black?style=flat&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=flat&logo=flask&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white)

**Data & Tools**<br>
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=flat&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=flat&logo=sqlite&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=flat&logo=opencv&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white) ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=flat&logo=latex&logoColor=white)

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=akashpersetti&theme=dark&hide_border=true&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=akashpersetti&theme=dark&hide_border=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=akashpersetti&theme=dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=akashpersetti&limit=5&theme=dark&combine_all_yearly_contributions=true)
