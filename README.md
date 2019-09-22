# Amazon Price Checker
Testing my VSC, React, Git, npm, etc. on my Windows desktop@home

How to use:

    node parser.js AMAZONURL MINPRICE

aka

    node parser.js https://www.amazon.com/Nintendo-Switch-Bundle-Console-Joy-Super/dp/B075MV3VX2 500
    
You'll also need (REQUIRED) https://sendgrid.com/ to get an API Key and (OPTIONAL) https://temp-mail.org/en/ for a test email

Write into the .env file with your SendGrid API Key like so

    SENDGRID_API_KEY=SG.exampleAPIkey
    
All done. Plugin real emails, upgrade your SG account, and set this script to run as a job on a schedule
