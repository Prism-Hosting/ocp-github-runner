# ocp-github-runner
Argo repo for GitHub runners

## Note
The `sa-github-actions` service account must have at least the `anyuid` SCC applied to it:  
```bash
oc -n github-actions adm policy add-scc-to-user anyuid -z sa-github-actions
```