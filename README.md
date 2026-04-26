[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=%F0%9F%91%8B+Hi%2C+I'm+Darshan+Patil)](https://git.io/typing-svg)

## 🚀 About Me

- 🎓 AI & Data Science Student  
- 💡 Passionate about solving real-world problems  
- 🛠 Building an AI Data Analysis Agent  
- 📍 India

## 🧠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,c,java,sql,mysql,mongodb,git,github,aws,gcp,sklearn" />
</p>

###  Data & Analytics
Pandas | NumPy | Matplotlib | Power BI | Excel  

###  AI & Gen AI 
LangChain | LLM Integration | Prompt Engineering | AI Agents  

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=darshan6239&show_icons=true&theme=tokyonight" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=darshan6239&layout=compact&theme=tokyonight" />
</p>

name: Metrics
on:
  schedule: [{cron: "0 * * * *"}]
  workflow_dispatch:

jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          user: darshan6239
          template: classic
          base: header, activity, community, repositories
          plugin_languages: yes
          plugin_isocalendar: yes
          plugin_traffic: yes
