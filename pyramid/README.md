A friend got asked this question in a programming interview he had.  Given N, print a pyramid with N layers that looks like this.
_____________________________________________O
____________________________________________O_O
___________________________________________O_O_O
__________________________________________O_O_O_O
_________________________________________O_O_O_O_O
________________________________________O_O_O_O_O_O
_______________________________________O_O_O_O_O_O_O
______________________________________O_O_O_O_O_O_O_O
_____________________________________O_O_O_O_O_O_O_O_O
____________________________________O_O_O_O_O_O_O_O_O_O
___________________________________O_O_O_O_O_O_O_O_O_O_O
__________________________________O_O_O_O_O_O_O_O_O_O_O_O
_________________________________O_O_O_O_O_O_O_O_O_O_O_O_O
________________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O
_______________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
______________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_____________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
____________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
___________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
__________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
________________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_______________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
______________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_____________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
____________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
___________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
__________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
________________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_______________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
______________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_____________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
____________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
___________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
__________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
________O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_______O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
______O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_____O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
____O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
___O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
__O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O
_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O_O