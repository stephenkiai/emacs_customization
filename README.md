**emacs customization**

**RECOMMENDED: To ALX students who enjoy using emacs**

Customizing Emacs to suit your preferences can greatly improve your productivity
and streamline your workflow. This configuration file includes several settings
that can enhance your text editing experience.

One of the first settings in the configuration file **disables the Emacs startup
screen** with the command **(inhibit-startup-screen t)**. This can help you save time
and jump right into your work without any unnecessary distractions.

The configuration file also **sets the color scheme for displaying ANSI escape
sequences** using the **ansi-color-faces-vector** and **ansi-color-names-vector** variables.
This can help you better distinguish between different types of output in your terminal.

For C programming, the configuration file **sets the default tab width and indentation
style** using the **c-default-style, c-basic-offset, tab-width, and indent-tabs-mode** variables.
This can help ensure that your code is properly formatted and easy to read.

Enabling whitespace mode with the **whitespace-style, whitespace-line-column, and
global-whitespace-mode** variables can help you **identify and remove trailing whitespace**,
which can be a common source of errors in code. It can also help you stick to a column
limit to make your code more readable.

The configuration file **sets the face color for comments to green using set-face-foreground**,
which can make comments stand out more clearly in your code.

Enabling the **display of column and line numbers permanently** in the mode line using
**column-number-mode** and **global-display-line-numbers-mode** can help you keep track of
where you are in your file and make it easier to navigate.

Finally, the configuration file **sets up custom backup settings** for Emacs files using
**backup-directory-alist, force-backup-of-buffer, before-save-hook, and backup-buffer**.
These settings can help you ensure that your files are **properly backed up** and that
you can **recover previous versions** if necessary.

Overall, this configuration file can greatly enhance your text editing experience
in Emacs, making it easier and more efficient to work with code and other text files.

**steps to access and edit your .emacs file**

###Open a terminal and navigate to your home directory "cd ~"
###list all and check if .emacs file is there "ls -la"
###Do "emacs .emacs" which will open(if file is present) or create(if file is absent)
###Then copy contents of config_file to .emacs, save and close.
###Enjoy. Dont forget to star this repo if it helped you.

If you are an emacs fun feel free to contribute.