# source
https://github.com/brentp/smoove/blob/master/docker/Dockerfile

* this repository originally resided at https://github.com/Benjamin-Vincent-Lab/lenstools , it was moved on 2/12/2024

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
