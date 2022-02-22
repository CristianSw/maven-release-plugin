for first we need to execute ***mvn release:prepare***
that check and prepare code for release

second need to execute ***mvn release:perform*** 
to perform release and push it to repository and github automatically

if with release is something wrong then do ***mvn release:rollback*** 
and dont forget to delete release tag from origin on github.