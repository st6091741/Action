```
curl -X POST -H "Accept: application/vnd.github+json" -H "Authorization: Bearer <YOUR_GITHUB_ACTION>" -H "X-GitHub-Api-Version: 2022-11-28" https://api.github.com/repos/<YOUR_GITHUB_USER_NAME>/<YOUR_GITHUB_REPOS>/actions/workflows/CMD.yml/dispatches -d '{"ref":"main","inputs":{"CMD":"whoami"}'
```
