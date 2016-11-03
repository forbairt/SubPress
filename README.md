# SubPress
## Sublime Snippets for WordPress Development with Genesis / CMB2

**Note: This is not yet fit for use**

I've recently found myself becoming more and more obsessed with editors and
now with Snippets. I've taken a look at a few projects out there but I find
to be rather personal. 

This is my collection and how I use them

### Installation
This is still very basic.

OSX 
1. From the command line cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
2. Create a snippets folder
3. Run git clone https://github.com/forbairt/SubPress.git

### Use - to setup a genesis child theme
(Assuming you've WordPress up and running and Genesis installed) 
1. Copy the file SubPress.tmPreferences.sample to SubPress.tmPreferences
2. Edit the file and fill in the details
3. Create a folder (for your child theme) in  wp-content/themes/ 
4. In Sublime create a new file style.css
5. Type child <tab> and fill in the details tabbing through them
6. type genesis <tab> this will pull in the default genesis CSS
7. Create a new file functions.php (starting it with <?php
8. Type CMD + Shift + P follow by g:Add .. you should have "g:Add support for HTML5 / Accessibility / Responsive in Genesis"
9. Select your child theme via WordPress 

Congratulations your child theme up and running

## Use - to create a new custom post type
1. Edit your functions.php file
2. Type cinit <tab> 
3. Type cnew <tab> and tab through the options filling them in as you go
4. Type cmeta <tab> change the post type to your new custom post type name
5. To add extra fields to your new Metabox type cimage <tab> and fill in the details

