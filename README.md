# azure-debugger
Azure App Services Web App debugger

This tool would help you debug applications on Azure Web Apps

Usage:
- Naviagte to wwwroot folder in kudu console
- Below command would install azured cli

> npm install -g azured  

- Below command would download xdebug based on php versoin and windows architecture in use. It will also create a userini file with xdebug and php logs enabled.

> azured  //(or) 

> azured .

- Below command would start xdebug with trigger

> azured -t //(or)

> azured -t .

Note: If you use this option Xdebug profiling can be triggered with a query string (e.g. http://<yoursite>/<pagename>.php?XDEBUG_PROFILE=1) to profile an individual request instead of profiling your whole site which will affect your website’s performance.
