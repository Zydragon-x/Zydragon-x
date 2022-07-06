## Zydragon-x
[![Typing SVG](https://readme-typing-svg.herokuapp.com?center=%E5%81%87&vCenter=%E5%81%87&lines=Abstractness+is+the+price+of+generality)](https://git.io/typing-svg)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}

<!--END_SECTION:waka-->


