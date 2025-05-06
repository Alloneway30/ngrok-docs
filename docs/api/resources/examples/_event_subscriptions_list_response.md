<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-05-06T10:07:09Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2wiYnjLjL3sAodNIhr4E8LxIqY8",
          "uri": "https://api.ngrok.com/event_destinations/ed_2wiYnjLjL3sAodNIhr4E8LxIqY8"
        }
      ],
      "id": "esb_2wiYnh6ku6S0ffRA5pLdVz17KZu",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2wiYnh6ku6S0ffRA5pLdVz17KZu/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2wiYnh6ku6S0ffRA5pLdVz17KZu"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
