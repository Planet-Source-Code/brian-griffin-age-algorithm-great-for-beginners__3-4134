<div align="center">

## Age Algorithm \- GREAT for Beginners\!


</div>

### Description

This is my first C++ algorithm as well as my first submission to PSCode. It is definitely great for beginners. It has basic I/O and practices doing math in C++. You enter your age, the current year, and a year in the future and it tells you how old you will be in that year.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Brian Griffin](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/brian-griffin.md)
**Level**          |Beginner
**User Rating**    |4.0 (24 globes from 6 users)
**Compatibility**  |C, C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Algorithms](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/algorithms__3-29.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/brian-griffin-age-algorithm-great-for-beginners__3-4134/archive/master.zip)





### Source Code

<br>
/*************************************<br>
* Age Calculation Algorithm *<br>
* By: Brian Griffin  *<br>
*************************************/<br>
#include <iostream.h><br>
  &nbsp;&nbsp;//NOTE: the above line is supposed to say iostream.h inside <>'s following the include. It was interpreted as HTML so it disappeared.
<br><br>
void main(){<br>
     int age, newYear, currentYear, newAge, next;<br><br>
     cout << "Age Calculation Algorithm" << endl;<br>
     cout << "By: Brian Griffin" << endl;<br>
     cout << "--------------------------" << endl;<br>
     cout << "Age: ";<br>
     cin >> age;<br>
     cout << "Current Year: ";<br>
     cin >> currentYear;<br>
     cout << "Year to find age in: ";<br>
     cin >> newYear;<br>
     cout << "--------------------------" << endl;<br><br>
     newAge = (newYear - currentYear) + age;<br>
     cout << "You will be " << newAge << " in the year " << newYear << "." << endl;<br>
     cin >> next;<br>
}<br>

