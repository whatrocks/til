fetch with ssh instead of https for github (e.g. go get commands)
```bash
git config --global url."git@github.com:".insteadOf "https://github.com/"
```

Remove directory that's been accidentally pushed to remote and now in gitignore
```sh
git rm -r --cached some-directory
git commit -m 'Remove the now ignored directory "some-directory"'
git push origin master
```
