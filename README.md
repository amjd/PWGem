PWGem
=====

PWGem is an adaptation of [PasswordChameleon](https://www.passwordchameleon.com). It's essentially a browser bookmarklet which makes using unique passwords for different websites a breeze, without needing to remember them all.

###How to use it

1. Drag and drop this bookmarklet to your bookmarks toolbar: [PWGem](javascript:(function(){s=document.createElement('script');s.type='text/javascript';s.src='https://dl.dropboxusercontent.com/u/63010476/pwgem.js?v='+parseInt(Math.random()*99999999);document.body.appendChild(s);})();)
2. Open any site where you wish to use a unique password and enter a strong master password in the password field.
3. Click on the bookmarklet you saved in Step 1. An alert box will display your unique password for that website, and it will be automatically entered in the password field.
4. There's no Step 4, enjoy!
