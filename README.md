# fractal-pset
A repository for materials distributed to the COMP3652 class for an assignment on a language (called FRACTAL) for 
creating fractals

Below is a quick guide to the files available here.  (You need almost all of them)

Filename     |  Purpose
----------   | ----------
desc-2017.pdf | Language specification for FRACTAL
pset-2017.pdf | The document describing what you must do for the assignment (and how many marks have been allotted to what parts)
pset-code-2017.zip | A zip file of the starter source code
cs34q-utils.jar  | A JAR that you will need to put in your library folder (lib) and include in your classpath
cs34q-docs.zip   | A zip file of Java docs for the classes contained in cs34q-utils.jar
build.xml        | If you are using NetBeans, this file is handy for calling JFlex and CUP as part of the compilation process


**A Word to NetBeans Users**

Note: In the past, some students have reported that they had difficulty using the build.xml file.  I'm not certain why that might
have been the case; but just to cautious, if you are using NetBeans, you should create an empty project first 
(or one from existing sources after unpacking pset-code-2017.zip).  That will create a build.xml file (and all its supporting
files) automatically.  You can then rename that file for safe-keeping, and move the version provided here in to replace it. 
If you have already put in come customisations of your own into build.xml, then you probably just want to add the customized parts
of the given file (the last parts) into your own existing build.xml file.  To do that look for the sections after the big comment
very near the end of the file.
