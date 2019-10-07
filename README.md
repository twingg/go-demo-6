## Replace master with orig



asfvsfb
```bash
git checkout orig

git merge -s ours master

git checkout master

git merge orig

git push
```
