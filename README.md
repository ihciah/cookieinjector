# cookieinjector
Wireshark cookie injector for tampermonkey
###Setup:
use ```https://github.com/ihciah/cookieinjector/blob/master/CookieInjector.user.js``` or simply copy file content to a new script in tampermonkey.
###Usage:
Use some filters like ```http.cookie``` in wireshark and right click on some packets, copy cookie as value

Open a new tab(u'd better open a private window in firefox or something similar called incognito tab in chrome)

Open the site you want to inject cookie in, after finished press ```Alt+C```, paste cookie and fillin the domain, and click OK.

Refresh the page, you should see the cookie has been successfully applied:)
###Some tips:
When filling in domains, you should write ```.```+root domain

For example: ```.baidu.com```, ```.weibo.com```

Donot use this tool for something ilegal :) 你懂的
