## Laboratory Work 4 Cross-Site Scripting:

# Tools used:
1. Brain

# Steps
1. Find a XSS vulnerable site. I found https://iticket.md/
2. Create a new account.
3. Go to settings and change the fullname to <script>alert(1)</script>

![alt text](https://github.com/dcalance/SI/blob/master/res/lab4_1.png)

4. Observe some dark magic happening.
5. Use a script that will secure your account "><script>document.body.style.setProperty("-webkit-transform", "rotate(-90deg)", null);</script>

![alt text](https://github.com/dcalance/SI/blob/master/res/lab4_2.png)

6. Use a infinite loop to brick the account to secure it even more.
