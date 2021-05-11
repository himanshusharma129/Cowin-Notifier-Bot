# Cowin-Notifier-Bot
This repo talks about a telegram bot that I created to grab a vaccination slot for myselft using a telegram bot and Postman stack.

Link to my Collection at Postman. To get a notifier bot for yourself, just follow this collection's doc.

https://www.postman.com/lunar-moon-673991/workspace/himanshu-sharma/collection/11652110-ebc47ee1-a82b-4e10-b92c-2b5a75441b1b

With Postman you can build anything you want. Postman is not only an API testing tool. It has lot of other cool features like monitor, collection runner, mock servers, which helps you create apps without even acutally coding anything. You can use APIs with postman to build your bots and stuff.

I used similar to build a telegram bot for myself that notitfies when there is any slot available.
For that, first we need an API that would allow us fetch data. You can use Postman's API Network to search for APIs and relevant collections and workspaces.
The Government of India's API are also listed on https://apisetu.gov.in

Using the above API, and creating a telegram bot (using BotFather), I created a collection that -
- Fetches the vaccines slots data
- filters is based on AGE (18+)
- if any slot found, pushes the data to telegram bot which gives a notification (as new message) and the bot shows a list of hospitals having slots

Further, knowing that slots are available, you can go to gov website and book one for your and your family.

To keep this collection running you can use Collection Runner in Postman.
Monitors also work a way better but because this API is geolocked so Monitors give 403.

So you need to keep your `collection runner` running.
