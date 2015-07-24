# CustomCategoryProductImage-Magento
Adds additional images to the category page according to the label and the category user is in.

http://heruniverse.com/ needed to display Plus-Size product images for a product IF that product is being viewed under one of the plus size categories.

As a solution I made use of the image labels. This code checks if the user is in one of the plus-size categories and if she is, then we load the plus-size labeled images instead of the default ones. 

This code also takes into consideration that there might be a backview image as well. The backview images are displayed when the user hovers on the product.

Within the list.phtml file, you can see the customizations in between the following two comment lines:
 //Plus-size Image customization Start
//Plus-size Image customization End
