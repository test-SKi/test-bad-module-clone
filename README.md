[![test-checkout](https://github.com/test-SKi/test-bad-module/actions/workflows/blank.yml/badge.svg)](https://github.com/test-SKi/test-bad-module/actions/workflows/blank.yml)

```
export USER=test-SKi
git checkout new
git clone https://github.com/$USER/test-checkout.git
echo "add an update" >>  README.md
git add .
git commit
git push --set-upstream origin new
```
