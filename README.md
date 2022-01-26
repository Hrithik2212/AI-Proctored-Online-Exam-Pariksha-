# Pariksha
# AI-Proctored-Online-Exam-Portal
Hello guys
Now-a-days due to the ongoing Pandemic exams are taking 
place online. Due to this many students tend to cheat and there 
is very little education organizations can do to prevent their 
students from committing malpractice. In order to solve this, 
we have created Pariksha which uses AI to check students and 
prevents them from cheating up to some extent.
Pariksha is established on a website which gives easy access to 
the students. It uses python OpenCV face detection AI to check 
whether the student continuously is present in front of the 
camera. It also detects if anyone else is present and sees to it 
only one student is present in front of camera. When the 
above-mentioned conditions become false the AI detects it and 
stops the student from writing the exam and informs the 
invigilator.


We are intending to further develop our project 

->By Introducing an Android App for second camera which 
checks on the user's hand visibility which will make cheating 
even more difficult 

->An AI which will track users eye pattern movement and check 
the possibility of male practice

->Speech recognition to check if only the users voice is present 
in the room and no other person voice is present in the room



                                           This project intends to prevent cheating in online exams  

In this project we have used : -
1) C Language
2) Python
3) Html
4) Css
5) Javascript
                                                         
                                                         
                                              Use of C Language in this project
                                                                 
                                                                 
In C Language we created a database for Students Login with File Operation
With File operations in C Language we created a text file database named as stdb.txt
To create Invigilator Data base we integrated C language and Python.
In C Language we have used
1)Functions
2)Pointers
3)File Operations 
4)Loops 
5)Conditions 
6)Arrays of Structures
7)Arrays
8)String Functions



                                                   Use of Python in this project
                                                                 
In python we used Django
For face detection we used Opencv
We used time function in Python
For integration we use ctypes in Python


                                             This project is website based project
                                                               

For webframe work we used Django
Django is a Python-based free and open-source web framework that follows the model–template–views architectural pattern.
In Django we used Html to create websites
For GUI we have used CSS
To display imgs in websites we have used javascript


                                              Integrate C Language with Python
                                                               

In main folder there is two shared files libcalci.dll and studb.o
Studb is file name of c language file this file present in main/authentication/Studb.c
To create studb.o we use gcc -c -fPIC studdb.c -o studdb.o in cmd
To create connection between python and studdb.o and we create libcalci.dll
To create connection between libcalci.dll and python we use gcc studdb.o -shared -o libcalci.dll
To create connetcion between libcalci.dll and studb.o we use gcc -shared -o libcalci.dll -fPIC studdb.c

                                                                 Changes need in your pc
If you need to use this file in your pc please change this two lines
In main/authentication/views.py  in line number 19 change path according to your pc
In  main/authentication/views.py in line number 80 change path according to your pc



