##Mail Server on Ubuntu

####This guide is compatible with Ubuntu 14.04 

![alt tag](https://github.com/nirbhayph/Mail-Server-on-Ubuntu/blob/master/Working/Cover.png)

######This guide is intended to be a reference for setting up a server quickly. For that reason, I have intentionally omitted information which explains each step.

######But if you want to understand the working behind this click [here](https://github.com/nirbhayph/Mail-Server-on-Ubuntu/Working)

######There are several configuration variables that you will need to replace in certain configuration files. These occurrences are clearly marked during the guide.

######However, for your reference, here are the variables used:

- mail.example.com  

  The hostname for your mail server. This can be anything you like, however, it should match the public hostname as specified by your DNS records if you want to expose the server over the Internet.

- rootpassword  

  The password for the MySQL  root  user. You should pick something unique and secure; but something you can remember.

- mailpassword  

  The password for the MySQL  mail  user. You should pick something unique and secure; you don’t even have to remember it beyond this tutorial.

- adminpassword  

  The password for the administrator e­mail account that you’ll create later in the guide.
  
