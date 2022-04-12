# daily_shipping_report_SIGNODE_CANADA
 Sends data about today's shipped orders in an excel sheet through an automated  daily email.

Grabs data about all orders stored in a MongoDB database, and checks if they were shipped within the last 24 hours. If they meet this criteria, adds their order details to an excel sheet; then at 4:30 p.m. each day an email is sent to the specified addresses.
