# Super Shop

An example shop developed in vanilla PHP.

## [Step 1](https://github.com/arestivo/supershop/tree/step1)

Initial page developed using only HTML and CSS:

  * Created folder for images
  * Created folder for css
  * Added css/style.css
  * Added images/products/1.png
  * Added images/site/logo.svg
  * Added index.php

## [Step 2](https://github.com/arestivo/supershop/tree/step2)

Organize the HTML code into separate template files:

  * Created folder templates/common
  * Created folder templates/category
  * Created folder templates/product
  * Added templates/common/header.php
  * Added templates/category/list_categories.php
  * Added templates/product/list_products.php
  * Added templates/common/footer.php
  * Moved code from index.php to new files

## [Step 3](https://github.com/arestivo/supershop/tree/step3)

Created the database:

  * Created folder database
  * Added database/connection.php
  * Added database/shop.sql
  * Generated database/shop.db using sqlite3
  * Added images for 3 more products in images/products
  * Included database/connection.php in index.php

