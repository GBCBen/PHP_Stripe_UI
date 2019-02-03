# PHP_Stripe_UI
PHP Stripe UI projects to ease or aid in development
ben@gobecreative.com

Reguirements: PHP + PHP Stripe SDK
Notice: It's a quick, and simple, and even a little dirty, solution. Use at your own risk. I'm not responsible for how you utilize or modify the code. -It should be pretty easy to also port over to other languages.

Stripe Update Card Form - 
Stripe Update card form assumes cutomer ID is already saved and stored. It didn't seem helpful for those wanting users to update cards via email address. So:
- This self submitting form gets customer ID by looking up via email @ stripe.
- Goes over results and stores customer ID as a session variable.
- session variabe is used to update customer after the stock UPDATE CARD FORM stripe.js form fires and returns a token.
