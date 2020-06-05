# RoboJackets EAGLE CAD Libraries

This repository contains unified libraries across the various RoboJackets teams.

Here are the steps to add the libraries to your EAGLE setup:

1. Use the [Git](https://git-scm.com) software to clone the libraries.  This can be done by running `git clone https://github.com/robojackets/eagle-libraries.git` 
in your command line or following [this tutorial](https://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop) for cloning with GitHub Desktop. Copy or note the file path to the location you cloned it into.

2. Open your EAGLE software. On the EAGLE Control panel, navigate to Options > Directories in the top ribbon. Here you will add your RoboJackets directories. 

3. At the end of the existing entry in the libraries box, add an append character (`;` on Windows, `:` on Mac/Linux) and then paste the file path you copied from pt. 1. Then, add `/libraries` to the end of the entry. For libraries, the path should look like `/path/to/directory/eagle-libraries/libraries`.

4. Press OK and restart EAGLE by closing the control panel and opening it back. Now, expand the 'Libraries' group in the EAGLE Control Panel. Locate the 'libraries' group within and expand it to see a list of libraries with the 'RoboJackets' prefix. Right click the group name (libraries), and select "Use All". Now, each RoboJackets library should now have a green dot next to it.

5. To verify that everything works, open a new schematic (File > New > Schematic) and start the `add` tool. In this panel, you should be able to find a set of libraries with the prefix "RoboJackets."

Congrats! You are now ready to work on RoboJackets CAD projects with EAGLE!
