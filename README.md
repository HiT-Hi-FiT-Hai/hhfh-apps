If you've made an app which you think other users can use for easy access on the hub; feel free to share.

# How do I add my scripts

1. Clone this repository to your system:

        git clone https://github.com/HiT-Hi-FiT-Hai/hhfh-apps.git

1. Create a directory with the name of your project. If you haven't thought of a name yet, use your HiT-Hi-FiT-Hai nickname.
1. Put the source files under sub-directory named `src/` and add a `README` file.

# Licence

By default, your application would be licenced under the [CC-BY-NC-SA][ccbyncsa] licence. If you want it to be released under some other licence, please also include a `LICENCE` or `LICENSE` file in your dirctory.

The final directory structure would look like:

     hhfh-apps/
               README.md
               hjpotter92/
                          README.md
                          LICENCE.txt
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

If your project depends on some other application, please mention so in your README file. If you have created two or more apps and haven't been able to decide on a name yet; I'd suggest choosing one as soon as possible. In case, you couldn't decide on a release name; create sub-directories as `project-1`, `project-2` etc. following the same conventions above.


  [ccbyncsa]: http://creativecommons.org/licenses/by-nc-sa/4.0/ "Attribution-NonCommercial-ShareAlike 4.0 International  (CC BY-NC-SA 4.0) "
