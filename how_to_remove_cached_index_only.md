#如何删除缓存中(通过git add且为commit)的索引

- 输入**git diff --name-only head -z | xargs -0 git rm --cached**
