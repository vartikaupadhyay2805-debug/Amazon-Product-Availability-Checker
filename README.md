# Amazon-Product-Availability-Checker

This project is a Python-based tool designed to monitor the availability of a product on Amazon and notify the user through email as soon as the product becomes available.



FEATURES:

Track availability of any Amazon product using its URL.

Automatic periodic checking.

Email notification when the product status changes to “Available”.

Configurable time interval.

Lightweight and easy to run.



REQUIREMENTS:

Python 3.x

requests

beautifulsoup4

smtplib (built-in)



HOW IT WORKS?

1. The script fetches the product page HTML from Amazon.
   
2. It parses the HTML to detect the availability text (like "In stock").
 
3. When availability is detected, it sends an email alert.

 4.The script repeats based on your configured interval.


CONFIGURATION:

Edit the script with your:

 Amazon product URL
 
 Sender email and app password
 
 Receiver email
 
 Checking interval (seconds or minutes)




IMPORTANT NOTES:

Amazon may block frequent scraping; use reasonable intervals.

Do not commit or upload your email credentials.

HTML structure changes may affect availability detection.
