<h1 align="center">
    <img width="100" alt="Homer MilkyWay" src="https://cdn-icons-png.flaticon.com/512/1808/1808512.png">
    <br>
    Homer
</h1>

A simple and beautiful design🔆 for home dashboard. For more information visit: [Homer Github](https://github.com/bastienwirtz/homer). 
<br>

![Preview image for the project](/../main/preview.png)
# 🐣 Getting ready
Required :
+ [Docker]() 
+ [Docker Compose]()
+ [Portainer]()
+ [Git Command]()
# 🔰 Install
## Using git clone <sup>*[Git]*</sup>
**Required** :
+ [Git Command]()
+ [Docker]()
+ [Docker Compose]()
> Install files from github 
```
git clone https://github.com/fleeforezz/Homer-Modified.git
```
> Open Homer-Modified file
```
cd Homer-Modified
```
> Run docker-compose.yml file
```
docker-compose up -d
```
## Using Portainer
**Required** :
+ [Docker]()
+ [Docker Compose]()
+ [Portainer]()
> Install Portainer
```
    docker run -d \
              --name="portainer" \
              --restart on-failure \
              -p 9000:9000 \
              -p 8000:8000 \
              -v /var/run/docker.sock:/var/run/docker.sock \
              -v portainer_data:/data \
                portainer/portainer-ce:latest
```
<br>

After installing finished head to [http://yourip:9000](http://yourip:9000)
<br>

1. Choose your **environment** ( usually local )
2. Choose **stack**
3. Create a new **stack**
4. Name the stack and click on Git **Repository** :
    - Repository URL : [ https://github.com/fleeforezz/Homer-Modified.git ]
    - Repository reference : refs/heads/branch_name ( usually main )
<br>

If everything setup correctly **Deploy the stack**
