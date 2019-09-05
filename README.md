# Unofficial Helm repo

Published at https://mans0954.github.io/helm-repo/

Build some Helm packages in the folder:
```
helm package ../comanage/
helm package ../kerberos/
helm package ../mdq-browser/
helm package ../pyff/
helm package ../shibboleth-idp/
helm package ../shibboleth-sp/
helm package ../passport-saml/
```
Rebuild the index:
```
helm repo index .
```
Add the built packages and the index to the repo, commit and push
```
git add *.tgz index.yaml
git commit -m "Add/Update charts in the repo"
git push
```

