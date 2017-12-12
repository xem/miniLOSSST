MiniLOSSST
===

A super tiny demake of [LOSSST](http://js13kgames.com/entries/lossst) (my js13kgames 2017 entry)

Golfed in <512b by [xem](https://twitter.com/MaximeEuziere), [xen](https://twitter.com/Xen_the), xaotic, [veubeke](https://twitter.com/I_like_too_much), [corruptio](https://twitter.com/justecorruptio) & [p01](https://twitter.com/p01) <3

Featuring 25 puzzles!

Goal: try to match each pattern.

Controls: arrow keys = move / R = reset.

Demo(s)
===

- Colored version (501b): http://xem.github.io/miniLOSSST

- ASCII version (436b, by p01): http://xem.github.io/miniLOSSST/ascii.html

Source code
===========

````
<body onload='m=p=>(n=p%16)>5&n<10&[..."ٯӟ൳ͷϼ໴𦙷࿟⛿ཿ濸ｳ񵝗𷝳𮻼𷝗𿹦򌻷򏿨򿦟񯽗𷿮񿧳\0"
][l].codePointAt()>>(p/4&~3)+n-18&1;onkeydown=d=e=>{k=e.which%36;k>4&&d(0);s=k?s
.includes(q=p+[,-1,-16,1,16][k])?s:[p=q,...s]:[p=65,64];s.length=l<6?8:l<12?11:l
<21?13:15;w=s.every(m)&&setTimeout("d(++l)",999);for(B=i="";i<160;)b.innerHTML=B
+=`<dt style=width:3ch;height:3ch;float:left;background:#${s.includes(i)?w?792:"
da6":!m(i)*359}>${i++-p?"":"👀"}`};d(l=0)'style=width:48ch id=b>
````

Commented source code
=====================

https://github.com/xem/miniLOSSST/blob/gh-pages/commented.html

Our other code golfed projects
===

- see [HERE](https://gist.github.com/xem/206db44adbdd09bac424)

- discuss [HERE](https://jsgolf.club)