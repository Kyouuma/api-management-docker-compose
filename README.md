# Apicurio Studio full development docker-compose setup


## Usage 

1. find your ip and export it

    ` export HOST=<YOUR_EXTERNAL_IP`
2. Change the $HOST environment variable in 
**apicurio-realm.json** and **microcks-realm.json** in realms folder.

3. Run everything 

    `docker-compose up -d`

4. Credentials (username/password)
    
    Keycloak : admin/admin

    Apicurio : oussama.hafsi@pwc.com/admin

    Microcks : admin/admin


## Useful Links

*  [microcks realm setup](https://microcks.io/blog/integrating-in-apicurio-keycloak/)