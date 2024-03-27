# githubmodulesdemo
```bash
mkdir dockerfiles
mkdir dockerfiles/19.3.0
mkdir dockerfiles/21.3.0
mkdir common
mkdir common/scripts
cd dockerfiles/19.3.0/
ln -s ../../common/scripts scripts
touch ../../common/scripts/test.txt
ls scripts/
test.txt
```