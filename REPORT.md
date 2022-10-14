Ong Wei Sheng A0206042X

https://github.com/ongweisheng/OTOT-A1

# A1.1

1. Open terminal at folder `OTOT-A1/app`
2. Run command `docker build . -t otot-a1` to build the docker image for the app folder
3. Run command `docker run -p 8080:8080 -d otot-a1` to run the docker image
4. Open a browser tab and navigate to `http://localhost:8080`. A screenshot should be shown as below 
![image](https://user-images.githubusercontent.com/57165946/195844344-39c8613c-8bf3-4d07-b528-5b8c957233be.png)
5. Run command `docker ps` to find container ID of the image being ran
6. Run command `docker kill <CONTAINER ID>` to shut down the image