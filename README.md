aqva-shop.netlify.app

- Framework - [Next.js](https://nextjs.org)
- eCommerce - [Chec/Commerce.js](https://commercejs.com)
- Hosting - [Netlify](https://netlify.com)
- Styling - [Bootstrap](https://getbootstrap.com) and [SASS](https://sass-lang.com)






---










-
## Commerce.js features

This demo store uses a range of features provided by Commerce.js and powered by the Chec Dashboard.

### Carts

The shopping cart uses the Commerce.js cart API. Carts are persisted for up to 30 days, and Commerce.js automatically 
remembers carts for visitors.

### The checkout

Commerce.js provides many tools to streamline checkout implementations. The checkout in this demo store makes use of:

- Commerce.js's country and region APIs,
- the shipping methods API, and
- the discounts API (for validating and applying discounts at the checkout).

### Customers

Commerce.js provides inbuilt functionality for supporting customer logins without any server side code. This demo store
features an existing customer login page, and provides detail about previous orders. The customer information is also
used to pre-populate the checkout with known customer details.

### Payment gateways

This demo store is configured with the Chec "test gateway" out of the box, which provides a handy payment option while
testing your storefront. Additionally, Stripe Elements support is included if Stripe is configured on the Chec
Dashboard.

[Commerce.js <> Stripe integration documentation](https://commercejs.com/docs/guides/stripe-integration)

#### Enabling Stripe

You must enable Stripe in the Chec Dashboard by following the instructions provided. You may add your sandbox
keys for Stripe, and use a sandbox Chec public API key to test with Stripe. Both the Chec public API key, and the Stripe
"publishable" key are configured in the `.env` file. See step two of 
"[Manual setup and Netlify deployment](#manual-setup-and-netlify-deployment)"

## Customization and Extendability

Fork this project to customize and extend the demo however you want. Here are some ideas of what you can do and
directions you can take eCommerce.

- Add shipping zones and enable shipping options in each product
- Customizing the styling
    - All global styles are done using SASS and Bootstrap
- [A/B testing checkout designs](https://commercejs.com/blog/split-ab-testing-checkouts-with-netlify) and flows
- Integrating other backend tools like Content Management Systems, Customer Support, Fulfillment services, and more
- Fetching real client reviews from review APIs
- Adding search functionality
- Leveraging [webhooks](https://commercejs.com/blog/webhooks-pizza-and-order-notifications-via-twilio) to automate post checkout actions
