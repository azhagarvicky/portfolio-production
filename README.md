# azhagar.com — production

This repo only publishes the live site. The code lives in [azhagarvicky/portfolio](https://github.com/azhagarvicky/portfolio), and every push there updates https://uat.azhagar.com automatically.

**To release:** Actions → **Deploy production** → **Run workflow**. Leave "ref" empty to publish exactly what is on UAT, or paste an older commit to roll back. (Or run `./release.sh` in the source repo.)
