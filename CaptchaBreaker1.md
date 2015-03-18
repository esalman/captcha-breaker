# Introduction #

This Script breaks this Captcha <img src='http://captcha-breaker.googlecode.com/files/captcha1.png' />


# Usage #

This Captcha Breaker is a single function. All you need is to pass the URL of the image (without the http://) and it will return the code.

# Example #

```
   <?php

      include_once('captchabreaker1.php');
      
      $code = breakcaptcha('captcha-breaker.googlecode.com/files/captcha1.png');    

      echo $code;

   ?>

```

# What you need #

In order to get the script running you need all files and folders that you can find <a href='http://code.google.com/p/captcha-breaker/source/browse/#svn/trunk/Captcha%20Breaker%201'>here</a>. Even if they are empty.

The folders unkown and tmp need to be writeable
The folder letters needs to be writeable