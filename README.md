<!-- HEADER -->
<div align="center">
  <img src="https://github.com/maithili-gohokar.png" width="120" style="border-radius:50%;" />

  <h2>Maithili Gohokar</h2>

  <p>
    Software Engineer @ Dealermatix Technologies • Salesforce Developer  
    <br>Double Star Ranger ⭐⭐ • AgentBlazer Legend 🛡️
  </p>
</div>

---

<!-- GITHUB METRICS INSPIRED DASHBOARD -->
<div align="center">

### 📊 GitHub Analytics Dashboard

<img src="https://github-readme-stats.vercel.app/api?username=maithili-gohokar&show_icons=true&theme=dark&hide_border=true" height="160"/>  
<img src="https://github-readme-streak-stats.herokuapp.com/?user=maithili-gohokar&theme=dark&hide_border=true" height="160"/>  
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=maithili-gohokar&layout=compact&theme=dark&hide_border=true" height="160"/>

</div>

---

<!-- METRICS SECTION -->
### 🧩 GitHub Metrics (Advanced)

> Enable metrics by using GitHub Actions (steps provided below)

```yaml
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
          token: ${{ secrets.METRICS_TOKEN }}
          base: header, activity, community, repositories, metadata
          plugins_activity: yes
          plugins_languages: yes
          plugins_lines: yes
          plugins_followup: yes
          plugins_traffic: yes
