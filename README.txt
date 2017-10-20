Go to    C:\Windows\System32\Drivers\etc\hosts  and open this wile in notepad (running as administrator ) 
after opening at line 22 and 23 add
 127.0.0.1      shortenurl.co
127.0.0.1      www.shortenurl.co

- type url www.shortenurl.co:8000 or shortenurl.co:8000 checkout to access home page 
- you can run command KirrURL.objects.all() in python shell to see which links are active
this is also accessible in admin page in analytics section

- you can also run custom command as python manage.py refreshcodes to refresh all the codes
or you can give arguments to refresh the latest shortcodes in reverse order by  python manage.py refreshcodes --items 5/6 
or as much shortcodes you want to refresh

admin page can be accessed from  www.shortenurl.co:8000/admin 

make sure you keep your net connection on

--------------------------HAPPY CODING-----------------------------------------

