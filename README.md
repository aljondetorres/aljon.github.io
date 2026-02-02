# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  --method POST \
  -H "Accept: text/html" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /markdown \
   -f 'text=Hello **world**'
