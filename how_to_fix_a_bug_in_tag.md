#How to fix a bug in tag 

-	git branch **fixbug-tag_name** **tag_name**
-	git add .
-	git commit -m "message"
-	git tag **-f**  **tag_name** [-m "message"]
-	git checkout master
-	git merge --no-ff **tag_name**
