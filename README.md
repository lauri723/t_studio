# Payment flow
1. Customer adds artwork to cart
2. Customer views cart
3. Customer goes to checkout
4. Payment intent created
5. Customer fills out info and submits form
6. Customer created and added to payment intent
7. Payment is attempted, if successful customer is notified and a webhook is fired off for payment_intent_.succeeded
8. Webhook invokes fulfillOrder function
Not done yet:
9. Email is sent to customer and site owner with info about the order