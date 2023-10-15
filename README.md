# <span style="color:green"> springboot-jenkin </span>
Integration of jenkin for a springboot application


### <span style="color:cyan"> How to run this application ? </span>

1. Install docker desktop (Required to run jenkin in container)
2. Execute docker-composer.yaml to download jenkin image and run
3. Open jenkin http://localhost:8080 it will ask for password. Execute below command in terminal to find it.
    > $> docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
4. Logged in successfully!!!

### <span style="color:cyan"> How to create jenking Pipeline ?</span>