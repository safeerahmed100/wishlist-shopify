# WISHLIST-SHOPIFY
## Overview
This is a lightweight, free wishlist functionality for Shopify stores that works across product pages, collection pages, and related product sections. Unlike many paid apps that only offer wishlist features on product pages, this code allows customers to add products to their wishlist from anywhere on the store. The wishlist is stored in the user's session storage, ensuring the list persists across pages but is cleared when the browser cache is cleared.

This functionality was created as a free alternative to the limited capabilities of existing paid apps. It has been customized to work seamlessly across collection pages and related products, making it more versatile than other solutions on the market.

The core code was adapted from WebSensePro's guide on adding a wishlist in Shopify without an app.

## Features
Works Across Pages: Adds wishlist functionality to product pages, collection pages, and related products.
Session-Based Storage: Wishlist is stored in the user's session storage, ensuring it is not permanent but is retained during the user's session.
No Third-Party App Required: Provides a simple, self-hosted solution without the need for expensive apps or external services.
Easy Integration: Simple to add to your theme with minimal code.
Lightweight: Doesn't impact store performance, making it a fast and efficient solution.
Demo
To see the functionality in action, you can test it on the Dawn Theme on a Shopify store.

Add any custom CSS to style the wishlist button according to your store's design.

You can place the CSS code in assets/styles.css or a custom CSS file.
Customize the Wishlist Behavior (Optional):
You can customize the behavior of the wishlist, such as changing the button text, appearance, or session storage logic, by editing the JavaScript file.

## How It Works
Adding Products to the Wishlist:

When the user clicks the "Add to Wishlist" button, the product is saved to their session storage in the browser. This ensures that the wishlist data is only retained for the duration of the current session.
Viewing the Wishlist:

You can access the wishlist via a custom link or button that opens a modal or page displaying the saved products.
Removing Products:

Users can remove products from the wishlist by clicking a "Remove" butto`  n next to each item, which removes it from the session storage.
Session Persistence:

As long as the session is active (i.e., the browser is not closed or the cache cleared), the products will remain in the wishlist. However, clearing the cache or closing the browser will reset the wishlist.

## Known Issues
Session Expiry: The wishlist will be cleared when the user clears their browser cache or closes their browser window. This functionality is based on session storage, so it is not a permanent wishlist solution. For a more permanent solution, you may need to integrate with Shopify's backend or a third-party app.

Theme Compatibility: This code has been tested on the Dawn theme. While it should work with other themes, you may need to adjust selectors and code snippets based on your theme’s structure.

## Contribution
Feel free to fork the repository, submit issues, or create pull requests. This is an open-source project, and any contributions to improve the wishlist functionality are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Shopify for providing a powerful and flexible e-commerce platform.
WebSensePro for the inspiration and base code.
The open-source community for providing inspiration and support.
