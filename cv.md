# [rsschool-cv](https://github.com/R3dFr0g/rsschool-cv)
---
# Timur Ospanov
---
## Contact information:
  
#### E-mail: r3d.Fr0g31337@gmail.com
#### Discord: r3d.fr0g#8032  
---  
## About myself:
#### I am interested in information technology and try to improve my programming skills.  
---  
## Proffesional skills:
+ C++ Basics
+ JavaScript Basics
+ Unity Basics(C#)
+ adobe Photoshop
+ Microsoft Office(Exel, Word, PowerPoint)
---  
## Code example:  
```  
// learning a recursion  
function findSolution(target){

    function find(current, history){

            if (current == target)      { return history; }
            else if (current > target)  { return null; }
            else { return find(current + 5, `(${history} + 5)`)||
                          find(current * 3, `(${history} * 3)`);}
    };
    return find (1, `1`);};
}
```  
---