# UAC-No-coockies-v-0.1
#programed by Majid AL-Maashari
#Email : omanras@gmail.com
#https://github.com/omanras/UAC-No-coockies-v-0.1/
user access control for web app with out using cookies developed in python bottle "explain logic" .
This project developed on python Bottle freamework for more information about bottle please check this web site :
https://bottlepy.org/docs/dev/
This project designed to help you placed another authentication web app system using different logic than the usual who using session code stored in cookies HTTP header , the logic of this project build to storing unique token code in the database after conformed the username and password check function the function storing the ip address of the user who was conformed login to make sure the user was logged in and give the programer more flexibility for add security features and log system.
after check function generate the token and stored the ip address of the logged in user it will redircte to home page , the home page function import the token from the database and put the token code in all other linked pages who need authorized users  and all this pages checked both token code and ip address from the database .

So we can sae , this project is an example of this logic who designed in users group privileges using if statment mechanism by give the "adminroot" user the id number "1" and the admingroup group id number "1" , the adminroot have all authorizations to delete groups and add users ,so when adminroot create new group by create new admin with only admin group authorization who give the group admin to add and delete users in his group only .   

In the end I hope if you test this logic and give us notes and feedbacks who help me devlopeing new python lib in users access control systems .  
