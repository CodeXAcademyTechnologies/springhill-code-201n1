# Lab 07-X Cookie Sales Page

Now that you have made a splash page for your shop, you must make a cookies sales page. For each product, create a link to a checkout page for that product. On the checkout page, the user can input how many cookies are desired, and a coupon code (if available) and the page will calculate the total price with tax and whether or not there is free shipping. This will be reported to the user by being written on the page.

## Instructions

Be sure to create a new branch in git for this lab. 

You should have four different products for purchase. Each product will have its own page. There should be a link from the front page to the purchase page for each product.

Each page should have its own JavaScript file to go with its html file. For example, for product 1, your might have `product-1.html` and `product-1.js`. For product 2, you might have `product-2.html` and `product-2.js`. (Feel free to call them something else like `lemon-salmon-cookie.html` and `lemon-salmon-cookie.js`) But you may use copy and paste after your have finished your first product as a template for the second one.

When a user visits the page, the user will be prompted for how many cookies are desired. Then the user will be asked for discount code. These values should be stored in variables.

There should be two discount codes. One for 10% off and one for $5.00 off.

There is a sales tax of 5.2%.

The shipping cost is $3.99 unless the total purchase price after discount and tax is over $25.

After calculating these costs, you should write the results to the page using `document.write()` or `textContent`.

### Stretch goals

* Use functions to encapsulate the logic of calculating the total cost. The function could take the cookieCount and cookiePrice as input and would output the total cost.
* DRY means Don't Repeat Yourself. You can try to DRY up your code by using the same function in more than one page to take out some logic.
* Update your function to allow for different tax rates or different coupons.
