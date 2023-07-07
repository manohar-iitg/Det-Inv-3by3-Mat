# Determinant and Inverse of 3x3 Matrix
This is a Python project which I did when I was in school. A thought for this came upon when finding the inverse of a 3x3 matrix and having no method to verify it. Why not make a python program? And why not make it using UI elements and interface? So I made an interface in Python using Tkinter which calculates the determinant and inverse of a 3x3 matrix.

# UI

<img src="https://github.com/manohar-iitg/Det-Inv-3by3-Mat/assets/96137651/2ecc0952-19bd-441f-a8d6-13ffce6aa20b" width=300 height=500>
<img src="https://github.com/manohar-iitg/Det-Inv-3by3-Mat/assets/96137651/cc440867-2b74-4855-a2d6-fbdd4cf16f11" width=300 height=500>
<img src="https://github.com/manohar-iitg/Det-Inv-3by3-Mat/assets/96137651/498882dc-4339-4f93-8164-33320c4ef21a" width=300 height=500>

# Modules used and features implemented
* The main module used is Tkinter. It is used for the interface of the program. Entry boxes and buttons were places.
* Used the module of os for buttons in the menu. Menu feature was implemented using Tkinter but the New option in the menu which opens up a new window for entering elements is executing with the help of os module.
* I used the basic method of cofactors for determinant and inverse calculation. Since we mostly use the convention of expression the elements of inverse matrix in fractions form in the NCERT, I used the fractions module to represent the numbers are reduced fractions.
* I also considered the fact that a matrix with determinant 0 cannot possibly have an inverse and displayed the same message if determinant was found out to be 0.
* I handled a few exceptions by displaying possible errors while entering the elements.
