# Apicurio Studio, Registry, Microcks. Full development docker-compose setup with authorization management using keycloak.


## Usage 

1. find your ip and export it

    ` export HOST=<YOUR_EXTERNAL_IP`
2. Change the $HOST environment variable in **apicurio-realm.json** ,  **registry-realm.json** and **microcks-realm.json** in realms folder.

3. Run everything 

    `docker-compose up -d`

4. Credentials (username/password) : you can change the credentials in the realms files
    
    Keycloak : admin/admin

    Apicurio : oussama.hafsi@pwc.com/admin

    Microcks : admin/admin

    Registry : oussama.hafsi@pwc.com/admin

