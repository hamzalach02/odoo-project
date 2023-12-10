
Step Work by odoo
----
1-Create machine virtual ubuntu
2- Download pycharm :
                    https://www.jetbrains.com/pycharm/download/?section=linux
                    
3- install Dependencies
                    sudo apt install python3-pip libldap2-dev libpq-dev libsasl2-dev
4-install postgess 
                    sudo apt install postgresql postgresql-client
                    sudo su - postgres -C "createuser -s odoo16"
                    sudo su postgres
                    alter role odoo16 with password "odoo16"
                    exit
                    curl -fsS https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo gpg --dearmor -o /usr/share/keyrings/packages-pgadmin-org.gpg
                    sudo sh -c 'echo "deb [signed-by=/usr/share/keyrings/packages-pgadmin-org.gpg] https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update'
                    sudo apt install pgadmin4
                    sudo apt install pgadmin4-desktop
                    sudo apt install pgadmin4-web 

5-clone this projet : 
                    git clone https://github.com/Oussama-benrkia/event-odoo
6- open repo:
                    cd /odoorep
                    sudo pip install -r requirements.txt
 <a href="https://youtu.be/0ut8-lL-E14?list=PLT3v18VYaHYXY6qa2frMIV2FVl52L2tmP">For help ( video )</a>,

 <a href="https://www.odoo.com/documentation/17.0/administration/install/source.html">For help ( doc 1 )</a>,

 <a href="https://www.pgadmin.org/download/pgadmin-4-apt/">For help ( doc 2 )</a>,
 
Odoo
----

Odoo is a suite of web based open source business apps.

The main Odoo Apps include an <a href="https://www.odoo.com/page/crm">Open Source CRM</a>,
<a href="https://www.odoo.com/app/website">Website Builder</a>,
<a href="https://www.odoo.com/app/ecommerce">eCommerce</a>,
<a href="https://www.odoo.com/app/inventory">Warehouse Management</a>,
<a href="https://www.odoo.com/app/project">Project Management</a>,
<a href="https://www.odoo.com/app/accounting">Billing &amp; Accounting</a>,
<a href="https://www.odoo.com/app/point-of-sale-shop">Point of Sale</a>,
<a href="https://www.odoo.com/app/employees">Human Resources</a>,
<a href="https://www.odoo.com/app/social-marketing">Marketing</a>,
<a href="https://www.odoo.com/app/manufacturing">Manufacturing</a>,
<a href="https://www.odoo.com/">...</a>

Odoo Apps can be used as stand-alone applications, but they also integrate seamlessly so you get
a full-featured <a href="https://www.odoo.com">Open Source ERP</a> when you install several Apps.

Getting started with Odoo
-------------------------

For a standard installation please follow the <a href="https://www.odoo.com/documentation/17.0/administration/install/install.html">Setup instructions</a>
from the documentation.

To learn the software, we recommend the <a href="https://www.odoo.com/slides">Odoo eLearning</a>, or <a href="https://www.odoo.com/page/scale-up-business-game">Scale-up</a>, the <a href="https://www.odoo.com/page/scale-up-business-game">business game</a>. Developers can start with <a href="https://www.odoo.com/documentation/17.0/developer/howtos.html">the developer tutorials</a>
