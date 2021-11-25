- 📫 How to reach me in twitter? https://twitter.com/realxar1

name: Update badges

on:
  schedule:
    # Runs at 2am UTC
    - cron: "0 2 * * *"
jobs:
  update-readme:
    name: Update Readme with badges
    runs-on: ubuntu-latest
    steps:
      - name: Badges - Readme
        uses: xareal/badge-readme@master
          CREDLY_USER: Sagar Adhikari # optional, but default will use the same from github

<!---
xareal/xareal is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
