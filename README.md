PWGem
=====

PWGem is a browser bookmarklet based on [Password Chameleon](https://www.passwordchameleon.com) which makes using unique passwords for different websites a breeze, without needing to remember them all.

###How to use it


```javascript
javascript:(function(){s=document.createElement('script');s.type='text/javascript';s.src='https://raw2.github.com/amjd/PWGem/master/pwgem.js?v='+parseInt(Math.random()*99999999);document.body.appendChild(s);})();
```

1. Create a new bookmark in your bookmarks toolbar with the above code.
2. Open any site where you wish to use a unique password and enter a strong master password in the password field.
3. Click on the bookmarklet you saved in Step 1. An alert box will display your unique, strong password for that website (derived from the master password), and it will be automatically entered in the password field.
4. There's no Step 4, enjoy!

**Note**:
- Feel free to self host the javascript for your own use.
- It might be safer if you remove the line which displays the password in a pop-up dialog, it's currently left unremoved as some users might prefer to see the generated password.
- If you wish to change your passwords, just think of a new master password and all subsequent generated passwords based on it will be new and unique.

**All credits to Password Chameleon developer(s).**

###Disclaimer

I don't take any responsibility about the security of this approach. Use it at your own risk.
