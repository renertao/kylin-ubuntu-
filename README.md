# kylin-ubuntu-
client package 
how to build simple debian package
1.make a tar&&gzip package of code folder
2.dh_make -f ../****.tar.gz //to make debian 
3.modify files in debian, just like rules, control, package.postinst and so on.
4.debian/rules clean  //clean code  
5.debian/rules build  //make code compiled
6.debian/rules binary //make deb
