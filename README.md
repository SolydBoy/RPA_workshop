# RPA workshop subject <br/>

##First part <br/>
Before you start coding we need some python package.<br/>
To properly organize ourselves we are going to use **python virtualenv**.

###Exercise 1 <br/>
Install python and *virtual env* and **create** a virtualenv which using python3 named **RPAenv**.

###Exercise 2<br/>
Then install **selenium** and **openpyxl** <ins><span style="color:red">**INSIDE**<span/></ins> your virtualenv<br/>

##Second part <br/>
Now that the setup is finished we are be able to start the real exercises.  
This first part will help you to fetch different type of data.

###Exercise 1 <br/>
Write a python script which extract the little sentence on this web site every second using selenium and print it.  
site: http://whatthecommit.com/index.txt.

###Exercise 2 <br/>
Write a python script which go on https://www.random.org/ and generate a number between 1 and 300 then print the result.

###Exercise 3 <br/>
Write a python script which go on https://www.amazon.fr/ search *Koala* then get the rating of every product using selenium and display the name of the highest.

##Third part <br/>
Now you know how to fetch data on a website.  
The next step is to process this data.

###Exercise 1 <br/>
Write a python script which open https://intra.epitech.eu/module/2019/B-DEV-510/PAR-5-1/acti-367235/project/#!/group and extract all register students.
Then move the excel on your current repository.

###Exercise 2 <br/>
Write a python script which generate a random gpa with this web site https://pinetools.com/random-number-generator for each member of the group and write it next to the member column.
```shell script
A                                           | B                                             | C                         | D                            | E                              | F                       | G                       | H                      | I   | J   | K   | L   | M   | N   |
name                                        | code                                          | master                    | member0                      | member1                        | member2                 | member3                 | member4                |     |     |     |     |     |     |
[B5][DEV] AREA clovis.de-villars@epitech.eu | B5-DEV-AREA-PAR-5-1-arthur.dassier@epitech.eu | arthur.dassier@epitech.eu | camille.bouzerand@epitech.eu | guillaume.loiseleux@epitech.eu | louis.nicaud@epitech.eu | mammar.cyril@epitech.eu | theo.dedieu@epitech.eu | 2,1 | 1,3 | 2,3 | 1,0 | 1,8 | 2,4 |
```
###Exercise 3 <br/>
Write a python script which open which write a formula in excel which averages GPA in colomn O.
```shell script
A                                           | B                                             | C                         | D                            | E                              | F                       | G                       | H                      | I   | J   | K   | L   | M   | N   | O   |
name                                        | code                                          | master                    | member0                      | member1                        | member2                 | member3                 | member4                |     |     |     |     |     |     |
[B5][DEV] AREA clovis.de-villars@epitech.eu | B5-DEV-AREA-PAR-5-1-arthur.dassier@epitech.eu | arthur.dassier@epitech.eu | camille.bouzerand@epitech.eu | guillaume.loiseleux@epitech.eu | louis.nicaud@epitech.eu | mammar.cyril@epitech.eu | theo.dedieu@epitech.eu | 2,1 | 1,3 | 2,3 | 1,0 | 1,8 | 2,4 | 1.8 |
```

##Last part <br/>
Well done you have completed all the exercises !  
Now this is just the fun part of the workshop.

###Exercise 1 <br/>
Write a python script which go on https://orteil.dashnet.org/cookieclicker/ and clicks for you !

###Exercise 2 <br/>
Your script will now make the upgrade

###Exercise 3 <br/>
Your script will ave you progression every minute !


###Well done you finish the work shop !<br/>
if you want to go further look :  
* ImageGrab
* DirectKeys 