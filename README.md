 Restaurant Orders Automation

An automated workflow built with n8n to manage restaurant orders through Telegram. The workflow records new orders, checks stock availability, updates inventory in Google Sheets, and sends notifications automatically, reducing manual work and improving order accuracy.

Technologies: n8n Telegram Bot API Google Sheets JavaScript Webhooks

 Overview

This project automates the restaurant ordering process using n8n.

Customers place orders through Telegram, and the workflow handles the rest automatically by validating the order, checking inventory, updating stock, saving records, and notifying both the customer and the restaurant staff.

 Workflow

Full workflow screenshot:

![Workflow](screenshots/workflow.png)
 Features
Receive orders from Telegram
Save new orders to Google Sheets
Check stock availability automatically
Update inventory after each order
Generate order IDs
Increase order counter
Send confirmation messages
Notify the restaurant team
Reduce manual data entry
Technologies
n8n
Telegram Bot API
Google Sheets
JavaScript
Webhooks
<<h3>How It Works</h3>
Customer submits an order through Telegram.
The workflow validates the request.
A unique order ID is generated.
Google Sheets is checked for product availability.
If stock is available:
Stock quantity is updated.
The order is saved.
A confirmation message is sent.
If stock is unavailable:
The customer receives a notification.
The restaurant team receives an order notification.
 Notes
This project was built as a practical automation exercise to simplify restaurant order management. The workflow demonstrates integrating multiple services into a single automated process, minimizing manual intervention while improving accuracy and efficiency.
