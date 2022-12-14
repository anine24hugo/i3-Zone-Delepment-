 Editor – vscode
 Grails version – 5.2.4 - https://grails.org/download.html
 JVM version – 17.0.5 - https://sdkman.io/usage
 Groovy
 SDKMAN - https://sdkman.io/
 Database – H2 in-memory database

I installed and used SDKMAN in my terminal as a tool to manage multiple software
development kits in my terminal and installed grails through sdkman and also to install
JVM.

To start/run the application you need to open the terminal and make sure your in the
correct directory as where the application root file was created and then type grails to
access the grails framework in the terminal to be able to create your domain classes,
services and the controllers and to run the application etc. that you will need as you
develop the application in vscode.
So when you have the grails framework running in terminal you type the command “ run-
app ” and this will boot the application on your localhost server to view in the browser. The
port that will be used by grails is localhost:8080 unless specified to run on a different port
as the one grails will use.
To stop the application, you just type in terminal “ stop-app ” and this will terminate the
current running grails application.

I started the project by first getting everything installed that will be needed for a grails
framework application on my linux OS system – ZORIN 16. I found that developing the
application through a linux based system is easier to get things installed and working as
using a windows OS which I tried to install on windows 11 which took me way too long to
get the grails framework and JVM running to be able to start coding in win 11.
I had no prior experience of working with grails and groovy and was a learning curve from
the start for me. I had to go and read up a lot in the documentation of grails framework
which can be found on the grails website and used SDKMAN in my terminal to make the
set up easier of installing the needed versions of grails, JVM to be able to start developing
the application.

I also used examples of code snippets that I came across on stackoverflow as I did my
research to understand how the framework is used exactly and just tried to build on the
examples I got when looking for example how the login of the application should work and
improve the code so that it can be used in my application without breaking the application.
What I would do if the application gets more traffic due to an increased amount of users
and starts to run slower of not being able to keep up with the amount of user traffic is to
use a SQL database in the application like MySQL, postgreSQL that will be more than
capable of running the application and handling high amounts of user traffic without losing
performance of the application or make it slower or cause the bottle neck effect that
happens when a applications database can’t handle the CRUD operations that needs to
happen without any complications of slowing the application down and not cause the users
experience to decline due to high traffic of users that the application is receiving.
