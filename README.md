# wordpress-modules

Referenced code/forums:
https://stackoverflow.com/questions/10233550/launch-bootstrap-modal-on-page-load
https://stackoverflow.com/questions/16152073/prevent-bootstrap-modal-from-disappearing-when-clicking-outside-or-pressing-esca


Explanation of files:
current_website.html - Previous version of website, no pop-up menu, saved for purpose of reverting in case everything goes wrong
imported_css.css - Retrieved from http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css
cleaning_css.css - Cleaned css code (removed extra unnecessary parts)
test_website.html - Used to test different examples of code, currently has original modal code snippet
merged_test.css - Copy of cleaning_css.css - later unused due to conflicts with Wordpress' default CSS
merged_test.html - Merged copy of original website and modal/pop-up box update, currently works with sandbox Wordpress site
merged_test.js - Contains two imports from https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js and http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js, as well as functions that controls the modal pop-up and closing
test_website.js - Standalone functions that were added to merged_test.js, controls modal pop-up and closing