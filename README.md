## Replace master with orig
AMASDVMASVASB
```bash
git checkout orig

git merge -s ours master

git checkout master

git merge orig

git push
```
