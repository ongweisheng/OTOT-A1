Ong Wei Sheng A0206042X

https://github.com/ongweisheng/OTOT-A1

# A1.1

1. Open terminal at folder `OTOT-A1/app`
2. Run command `docker build . -t otot-a1-app` to build the docker image for the app folder
3. Run command `docker run -p 8080:8080 -d otot-a1-app` to run the docker image
4. Open a browser tab and navigate to `http://localhost:8080`. A webpage should be shown as the below screenshot
![image](https://user-images.githubusercontent.com/57165946/195844344-39c8613c-8bf3-4d07-b528-5b8c957233be.png)
5. Run command `docker ps` to find container ID of the image being ran
6. Run command `docker kill <CONTAINER ID>` to shut down the image

# A1.2

1. Open terminal at folder `OTOT-A1/nginx-sample`
2. Run command `docker build . -t otot-a1-nginx-sample` to build the docker image for the nginx-sample folder
3. Run command `docker run -p 3000:3000 -d otot-a1-nginx-sample` to run the docker image
4. Open a browser tab and navigate to `http://localhost:3000`. A webpage should be shown as the below screenshot
![telegram-cloud-photo-size-5-6217441232771199385-y](https://user-images.githubusercontent.com/57165946/195851745-5ca8fabd-2907-45ec-8fad-33e02ca95722.jpg)
5. Run command `docker ps` to find container ID of the image being ran
6. Run command `docker kill <CONTAINER ID>` to shut down the image
