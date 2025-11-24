# 2.1. How To Set Up An Endpoint URL In Appsflyer For Real-Time Data Integration

### Understand Appsflyer's Real-Time Postbacks 

Appsflyer sends real-time postbacks to an external endpoint whenever specific in-app events or actions occur (e.g., installs, purchases, app launches, etc.). Your job is to configure an endpoint to receive this data. 

### Configure Your Endpoint URL in Appsflyer 

- Log in to Appsflyer Dashboard
- Navigate to the **Export – API Access** section.
![](../image/img01.png)
- Set Up Real-Time Postbacks
    - **Endpoint configuration:** Add the endpoint URL: https://gio-data-ingestion.vnggames.net/v1/appsflyer/event
    - **Event messages:** Specify the **event types** you want to receive postbacks for (e.g., install, in-app purchase, etc.). => **Select All**
