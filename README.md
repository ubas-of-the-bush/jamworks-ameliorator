# jamworks-ameliorator
Marginally improves UX of Jamworks auto-captioning software.
# How To Use
**!! USE AT YOUR OWN RISK! !!**

IT WORKS ON MY MACHINE. IT MAY NOT WORK ON YOURS. MAKE A GODDAMN BACKUP BEFORE YOU START TINKERING WITH FORCES WITH(OUT) YOUR COMPREHENSION.

Use `patch` or whatever util to apply the .patch files - they're generated from running `diff` on various amendments I made to the index.js

The index.js file can be found at [jamworks_install_folder]/app-[VERSION]/resources/app/src. For me, Jamworks is installed at C:/Program Files (x86)/Jamworks, but this may vary on your machine. These changes were made to __Jamworks 1.4.5__.

These were made from a Windows install of Jamworks. I do not own a Macbook, nor do I wish to go through the mild inconvenience of reinstalling Jamworks on a Linux box to test my changes. If you're on Linux - you probably know what you're doing enough to DIY it from what I've provided. MacOS users... how do you know what GitHub is?

# Patches
devtools.patch: enables devtools. Dev tools can be accessed by pressing CTRL-SHIFT-I

resizeable.patch: enables resizing the window.

no_close_prompt.patch: removes the "are you sure" prompt, so pressing the close button actually closes the window.


# Licence
Licenced under the MIT licence because the Jamworks code is MIT-licenced :)

Source: Jamworks/app-1.4.5/resources/app/packages.json
