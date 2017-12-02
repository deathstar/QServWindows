## QServWindows

Welcome to the QServWindows project page! Thanks to BudSpencer for porting the mod from Unix to Windows. 
The port has uncovered some issues with outdated GeoIP code. I am working hard to fix these minor bugs, 
and also some more major ones. If you wish to see my progress, simply look at the commit history. I 
plan on making a stable release of QServ for Windows, and adding features to both the Unix and Windows 
versions as requested in the future. I will also start to work on server and client modifications.
You can compile the code from the source, but it might be tricky. Until I patch bugs, I will not release
binaries. This is because there is no point if some basic features like user location don't work.

## Helping Out

So you love QServ and what it can do and you want to help. Well that's great. There are many things to be 
done. QServ was written originally 7 years ago when c++ 11/17 weren't a thing. Now, newer compilers will 
not like some of the old code because of conflicting libraries and such. As always, patches are the only 
way to fix these issues. The GeoIP handler uses the geolite maxmind database. It is being patched now.
Another issue is the IRC Bot, it should be threaded properly with detachment and reinitilization. 



