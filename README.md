If you've made an app which you think other users can use for easy access on the hub; feel free to share.

# How do I add my scripts

1. Clone this repository to your system:

        git clone https://github.com/HiT-Hi-FiT-Hai/hhfh-apps.git

1. Create a directory with the name of your project. If you haven't thought of a name yet, use your HiT-Hi-FiT-Hai nickname.
1. Put the source files under sub-directory named `src/` and add a `README` file.

# License

By default, your application would be licensed under the [CC-BY-NC-SA][ccbyncsa] license. If you want it to be released under some other license, please also include a `LICESNE` file in your dirctory.

The final directory structure would look like:

     hhfh-apps/
               README.md
               hjpotter92/
                          README.md
                          src/
                              file1.lua
                              file2.c
                              file3.txt
               project-X/
                       README.txt
                       src/
                           myProj.php
                           some-sub-dir/
                                        dependencyFile.xyz

If your project depends on some other application, please mention so in your README file.


  [ccbyncsa]: http://creativecommons.org/licenses/by-nc-sa/4.0/ "Attribution-NonCommercial-ShareAlike 4.0 International  (CC BY-NC-SA 4.0) "
