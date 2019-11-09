# Hello, Micronaut

Run Locally:
```
./gradlew -t run
```

Visit: [http://localhost:8080](http://localhost:8080)

Deploy:

[![Run on Google Cloud](https://storage.googleapis.com/cloudrun/button.png)](https://console.cloud.google.com/cloudshell/editor?shellonly=true&cloudshell_image=gcr.io/ahmetb-public/button&cloudshell_git_repo=https://github.com/jamesward/hello-micronaut.git)



pack build hello-micronaut 

docker run -p8080:8080 hello-micronaut

pack build gcr.io/none-1232/hello-micronaut
