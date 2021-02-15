"Module" REES46 for OpenCart
======
Initialization
------
Set the code `catalog / view / theme / THEME_NAME / template / common / footer.tpl` before` </body> `.

Don't forget to insert the store code in two places.

Tracking
------
Set code `catalog / view / theme / THEME_NAME / template / product / product.tpl` before` <? Php echo $ footer; ?> `.

Paste the code from `catalog / controller / checkout / success.php` before` $ this-> cart-> clear (); `.

Set code `catalog / view / theme / THEME_NAME / template / product / category.tpl` before` <? Php echo $ footer; ?> `.

Recommendations
------
Create a file with the content `catalog / controller / common / rees46_recommend.php`.

Then, you can insert the recommenders into the necessary templates, in the right places.

`<div class =" rees46 rees46-recommend "data-type =" see_also "data-limit =" 4 "data-tile =" Don't forget also "> </div>` 
