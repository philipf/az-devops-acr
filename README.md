# Introduction 
Demonstrates how to build and push a docker image to ACR

```
 az devops login

 git add . && git commit -m 'test' && git push  && az pipelines run --project AcrDeploy --id 2 --branch feature-improve --open

```