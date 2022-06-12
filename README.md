### Study jenkins pipeline by myself

Start Jenkin on local
```shell
java -jar jenkins.war --httpPort=9191
```

** in Jenkinsfile steps use groovy script

Click on `New Item` to create Jenkin pipeline

![pipe item](https://github.com/Thanasornsawan/Jenkins_pipeline/blob/main/photos/start.JPG?raw=true)

Set the name and click `Multibranch Pipeline`

![pipe item2](https://github.com/Thanasornsawan/Jenkins_pipeline/blob/main/photos/start2.JPG?raw=true)

At Brach Sources, add `Git` and then put repo url and add the github credential and then save

![pipe item3](https://github.com/Thanasornsawan/Jenkins_pipeline/blob/main/photos/start3.JPG?raw=true)

** when want to use credential paramter from Jenkins,it need to set from here

![pipe cred](https://github.com/Thanasornsawan/Jenkins_pipeline/blob/main/photos/credId.JPG?raw=true)

Result after build

![pipe result](https://github.com/Thanasornsawan/Jenkins_pipeline/blob/main/photos/result.JPG?raw=true)
