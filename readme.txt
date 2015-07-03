Contribution:  Zen Cart Lazy Loader
Author: Delia Wilson Lunsford, http://teamwiztech.com
Date: June 29, 2014
Thanks to Dan123 on the Zen Cart forums for his description of how to do this. His great example of this mod is at http://www.klybni4ka.net/sale.
jQuery module for the lazy loader is http://www.appelsiini.net/projects/lazyload. Thank you, Mika Tuupola!
Version:  1
Designed for: Zencart 1.5.1,though will probably work with most versions.
Released under the GPL license found in the root directory of this package.
Support thread: http://www.zen-cart.com/forum/showthread.php?p=729343

This simply loads images in a more graceful way as you scroll down the page.  

Included in this text file:
Directions
Files list
CSS directions
-------------------------------------------------------------------
Directions:
Change the your custom template folder names to your custom name.
Upload all files.

-------------------------------------------------------------------- 
More jQuery Information:
This package does include the most recent version of jQuery on this date - 1.11.1. 
If you already are using jQuery, that file is not necessary to upload. But, and this is a very big but,
if this does not work, then the version of jQuery you have installed may be the problem. 
Replacing your present version of jQuery core with this one would solve that problem but can result in 
your old jQuery mods not working. I prefer to upload the jQuery core file that I know works instead of pulling 
the most recent from the depository since subsequent versions can disable this particular plugin.

--------------------------------------------------------------------
Cart Modified Files:
includes/modules/your custom template / product_listing.php
Cart New Files:
includes/functions/extra_functions/lazy_loader_extra_function.php
includes/templates/your custom template/jscript/jscript_jquery1.11.1.js
includes/templates/your custom template/jscript/jscript_lazy_loader_function_start.js
includes/templates/your custom template/jscript/jscript_lazyload_plugin.js

-------------------------------------------------------------------
CSS style tips:

Add this to your stylesheet:
 .listingProductImage{display: none} 
img.listingProductImage1 

This is for browsers that do not support javascript so it's not incredibly important.