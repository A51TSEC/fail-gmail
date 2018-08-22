
# fail-gmail

**Fail Gmail Bug in Gmail**
Social engineering? Not really 

![enter image description here](https://preview.ibb.co/b4CrAz/153490985371618984.jpg)

https://www.youtube.com/watch?v=AmDzPgR5ZfU

1.  X-Frame-Options (allows to iframe next url) .

2. https://mail.google.com/mail/u/0/?ui=&ik=64411c67&jsver=UpvwBf_7018.ru.&view=om&th=15fa48c10f45e439
3.  ( forces to logout) 

4. After we make death we make Redirection to auth into google account which makes redirection to google form which does not ask for permission
https://accounts.google.com/signin/v2/sl/pwd?service=wise&passive=1209600&continue=https://docs.google.com/forms/d/e/1FAIpQLSeScP-SSRCuHdJcXJ_ajX9opBbbQQVxdlDzZNf2PTlPK0Yr_Q/viewform#?gmail.com&followup=https%3A%2F%2Fdocs.google.com%2Fforms%2Fd%2F1zTt-nSYom-9sIEFeKW1QMHfdMDx6PwYzbKpkmKmmf2k%2Fedit%3Fusp%3Dsharing#https://gmail.com&ltmpl=forms&flowName=GlifWebSignIn&flowEntry=ServiceLogin


5. https://docs.google.com/forms/d/e/1FAIpQLSeScP-SSRCuHdJcXJ_ajX9opBbbQQVxdlDzZNf2PTlPK0Yr_Q/viewform google form which looks very simmilar to gmail login page

***Scenario attack: ->*** 
*Browser/OS: Chrome/Firefox . Windows, Linux.Feel free to rewrite it for mobile Chrome and Safari.*

**Google answer:**
![enter image description here](https://s22.postimg.cc/vo0zthp5t/2018-08-22_6.44.50.png)

**Usage**: upload html to your hosting, navigate and you will be able to understand how this works.
