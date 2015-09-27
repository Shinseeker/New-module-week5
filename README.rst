#########################
Week 5: Creating Modules.
#########################

Creating modules can be easy. It is another way to stay DRY where you don't
have to keep using multiple variables in one module. Essentially, a module is
a function that is included in another file.

example 1: 

abcd.py
    
def x:
  print()
 
example 2:      

efgh.py 

import abcd                       
 abcd.x()
 
In module efgh once can see it is copying the data from abcd and 
printing function x.

.. note:

Just to note i am using simple code to demonstrate my point.

#############################################
Installing modules & packages from a library.
#############################################

Python users can install modules that they did not create.
If you use the termnial in lubuntu or whatever version of ubuntu 
you're running,you can install packages that are alredy in the 
software's library.

A good example discussed in class is the terminal comand:

sudo pip search file.

you can search and upload software like  sql or django.
Then you can  import module after finding in the library.

###################################################
Installing modules and packages from other sources.
###################################################

Python users don't have to import modules from a library.
You can import them from virtually anywhere online.

An example of this is:

import random
import urllb.request

def download_web_image(url):
    name = random.randrange(1, 1000)
    full_name + str(name) + ".jpg"
    urllib.request.urlretreive(url, full_name)

download_web_image(link)

This code allows someone to download  jpegs from a website.

##########
Conclusion
##########

Importing modules makes life easier by helping python users write less code. 
In addition, it also makes programming less redudant.

##########
Refrences.
##########

-https://www.youtube.com/watch?v=rFv9PHjUJrI
-https://www.youtube.com/watch?v=GQiLweAoxgQ
