[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=HighTechPuddle)](https://github.com/anuraghazra/github-readme-stats)

- name: Comment reactions
  uses: lowlighter/metrics@latest
  with:
    filename: metrics.plugin.reactions.svg
    token: ${{ secrets.METRICS_TOKEN }}
    base: ""
    plugin_reactions: yes
    plugin_reactions_limit: 100
    plugin_reactions_details: percentage
