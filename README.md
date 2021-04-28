## Decoding the tag structure
v.w.x
vw is the version of ubuntu.  
x is the version of this Dockerfile.  

## Making commits, tags:
```bash  
cd /home/dbortone/docker/lenstools
my_comment="Initial commit."
git add .
git commit -am "$my_comment"; git push
git tag -a 16.04.0 -m "$my_comment"; git push -u origin --tags
```
