## Vagrant Box

Base virtual machine (VM) for running a linux server right inside your computer. Checkout this project and run the VM in order to create the environment to run the IW projects.


~~~

cd ./vagrant
vagrant up

vagrant ssh

cd /vagrant/application

npm install

allcountjs init --template student-classes

~~~


You can install templates using:


    $ ./node_modules/allcountjs-cli/bin/allcount.js init --template student-classes


 install dependencies:
     $ cd iwt_crm && npm install

   run the app:
     $ DB_URL=mongodb://localhost:27017/iwt_crm:* npm start

   or
     $ allcountjs run
