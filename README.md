Bower
=====


some lib packages we need to use metronic package, because of the compatibility. but the work flow is the same. 1. check out from svn, 2 run command bower install. NOTE if we use metronic package, we should write in bower.json like this: "libxxx":"./public/vendor/libxxx".  THE *"./"* BEFORE PUBLIC IS IMPORTANT, or bower can not find the lib, that is relative path something.
so if you used metronic lib, also need to upload to svn
