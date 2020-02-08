#  Resume
 
## Mikhail Stankevich

## Contact info
tel.: +375 25 905 26 88

## Goals, wishes
Main goal in my life is always take some knowledges, i think wthout selfeducation people would remained monkeys. I want use my      knowledges to make my life more easily. 
## Skills? *(lol)* 
Learning Html, css, php, C, C++, js on basic lvl and now want to learn more.

## Code example
My latest code examples is code from codewars. 
```
The task was return the string representation of the sum from string representations of two integers(>32bit)

 function res(a, b, t, c){
  if(a.length == 0 && b.length == 0)
    return t;
  var l = parseInt(a.pop() || '0') + parseInt(b.pop() || '0') + (c || 0);
  if(a.length == 0 && b.length == 0)
    return res(a, b, l + (t || ""), l > 9? 1:0);
    return res(a, b, (l % 10) + (t || ""), l > 9? 1:0);
}
function sumStrings(a, b) {
  return res(a.split(""), b.split(""), "").toString().replace(/^0+/, '');
}
```