# Unofficial Helm repo

Build some Helm packages in the folder:
```
helm package ../comanage/
```
Rebuild the index:
```
helm repo index .
```
Add the built packages and the index to the repo, commit and push
```
git add comanage-0.1.1.tgz index.yaml
git commit -m "Add COmanage chart 0.1.1 to the repo"
git push
```

