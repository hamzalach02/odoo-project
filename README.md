> [!IMPORTANT]
> Read it carefully.

Step Work by odoo
----



1. Create machine virtual ubuntu
2. Download pycharm :
                    - https://www.jetbrains.com/pycharm/download/?section=linux
                    
3. install Dependencies
                    - sudo apt install python3-pip libldap2-dev libpq-dev libsasl2-dev
4. install postgess 
                    - sudo apt install postgresql postgresql-client
                    - sudo su - postgres -C "createuser -s odoo16"
                    - sudo su postgres
                    - alter role odoo16 with password "odoo16"
                    - exit
                    - curl -fsS https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo gpg --dearmor -o /usr/share/keyrings/packages-pgadmin-org.gpg
                    - sudo sh -c 'echo "deb [signed-by=/usr/share/keyrings/packages-pgadmin-org.gpg] https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update'
                    - sudo apt install pgadmin4
                    - sudo apt install pgadmin4-desktop
                    - sudo apt install pgadmin4-web 

5. clone this projet : 
                    - git clone https://github.com/Oussama-benrkia/event-odoo
6. open repo:
                    - cd /odoorep
                   - sudo pip install -r requirements.txt
 <a href="https://youtu.be/0ut8-lL-E14?list=PLT3v18VYaHYXY6qa2frMIV2FVl52L2tmP">For help ( video )</a>,

 <a href="https://www.odoo.com/documentation/17.0/administration/install/source.html">For help ( doc 1 )</a>,

 <a href="https://www.pgadmin.org/download/pgadmin-4-apt/">For help ( doc 2 )</a>,


