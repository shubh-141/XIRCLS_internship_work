# XIRCLS Internship Work

This repository contains the code of my tasks performed during my internship at XIRCLS.

A Django app that is connected to a Shopify partner app. The shopify app is a test app that is specifically created for testing purposes.

- The Django backend app takes in the API key and API secret key of the Shopify app and using that an authorization code is generated by inputting the &code parameter obtained 
from the GET url request generated when a Shopify store is connected to the Shopify app.
- The authorization code is then stored in the Django database for future use.
- Shopify Webhook is created in the Django app to fetch CRUD details of the Shopify store and store it locally in real-time and rendered on the webpage.
- Similar Webhooks can be created to access data related to different domains of the Shopify store i.e. Orders, Products etc.
- Better Reports app of Shopify is used to fetch data from the store and save it locally, which be used to run analytics and gain insights for business development.
- link to Better Reports: https://admin.shopify.com/store/xircls123/apps/betterreports

