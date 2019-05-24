# line Editor

## Introduction  
The line editor is a course project of my C programming class in ZheJiang university in the first year of college.
Its graphical user interface is implemented based on the ACLLib,a graphics library designed by ZJU.
The project original request is listed on the PTA.  
I am a new learner in C,and I will update my program if I make some improvement.Any advice given to me will be highly appreciated.
## Function
This program deals with the text you enter which will be displayed on the graphical interface.
You can enter the text according to the caret.
As you press enter,this line will be displayed on the power shell.
The editor permits most keys include number,uppercase and lowercase letters,punctuation and so on.This editor support special function.  
  1)Esc: end this program.  
  2)Table: Indents one table step.  
  3)Backspace: delete the character behind the caret.
  4)Delete: delete the character before the cater.  
  5)Home: Move the caret to the beginning of the line.  
  6)End: Move the caret to the end of the line.  
  7)F1-F4: change the color of the text of one line.  
  8)F5-F8: change the backcolor of the text of one line.  
  9)Shift: type capital letters and other alternate "upper" characters.  
  10)CapsLock: change to uppercase/lowercase letters.  
## Version 1.0
Compared to the first version I commit,it makes some improvement:  
This version add a reference line at the end of one line.And it will automatically move to the next line and print the text of this line.
