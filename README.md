# uptimebot Haqq
Simple and fast monitoring get requests with notifications to email and phone


1. https://uptimerobot.com/
2. Created New Monitor
3. Monitor Type - choose a ```keyword```
4. Friendly Name - come up with names for the project
5. URL (or IP) - add an api link validator explorer

```https://haqq.api.explorers.guru/api/validators/YOUR VALIDATOR ADDRESS/signing_infos```

6. Keyword - ```"missed_blocks_counter":"0"``` 

0 - receive notifications as soon as your validator skips at least 1 block

7. Alert When - ```Keyword Not Exists```
8. Select "Alert Contacts To Notify" - Specify where you want to receive notifications

To receive notifications on your phone, install the mobile version of the app

you can also set up notifications if you are in jail, to do this, you need.

```https://haqq.api.explorers.guru/api/validators/YOUR VALIDATOR ADDRESS```

In the Keyword field, specify - ```"jailed":false```
Alert When - ```Keyword Not Exists```
