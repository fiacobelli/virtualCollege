virtualCollege
==============

This is a compilation of libraries and websites for courses. It is also a place where we can start developing new courses with all kinds of materials.

the idea is that each course has a home directory and a "core" subdir. Under "core" there should be a "www" directory with an index.html or index.php file.

The course directory name should be explicit when necessary. For example:
programmingI_java or
programmingI_python or 

I tend to favor a structure like this:
\course_name\
+---core\
     +---syllabus\
         +--syllabus.pdf
         +--supporting files (if done in TEX or other).
     +---www\
         +--index.html
         +--unit_name.html
         +--unit_name2.html
         +--etc.
    +---unit_name\
         +--images\
         +--docs\
         +--homework\
         +--slides\
         +--etc. (in general all resources for unit_name)
    +---unit_name2\
         +-- same as above...
         
I still need to figure out how to protect the homework solutions, so if you have any ideas, I'm all ears.
    
