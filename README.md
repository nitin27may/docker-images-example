# Nginx Custom Image
Very Simple Example to build Custom Docker Image.

To build custom image, run below command, here . (dot) is to use current folder as context.
```
docker build -t my-custom-nginx .
```

To run the custom image, you can run below command and it will run your image on port 8080

```
docker run --name nginx-container -d -p 8080:80 my-custom-nginx
```

Now You can make changes in inde.html, re build it and run it and see the changes
