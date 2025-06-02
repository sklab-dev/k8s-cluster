I asked in Home Operations what was the best operation hoe to mamage git

OneDrop Recommends:
```
task kubernetes:ks-apply PATH=default/sonarr
task kubernetes:ks-delete PATH=default/sonarr
```

Roxedus how to clean git
```
alias ifuckedup="git commit --amend --no-edit . && git push --force"
```

```
You can also utilize PRs and the flux local GH workflow, that should catch some errors like the kustomization or helm release not being able to be built
```

```
https://github.com/allenporter/flux-local
pip3 install flux-local
```
