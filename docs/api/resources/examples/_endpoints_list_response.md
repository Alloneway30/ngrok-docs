<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-06T10:07:07Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2wiYmnPIv0afaIR8UmSTHf3EKNY",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wiYmnPIv0afaIR8UmSTHf3EKNY"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wiYnTZd5Duz67pclTGJ3X1Oj0H",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-06T10:07:07Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2wiYnTZd5Duz67pclTGJ3X1Oj0H",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-06T10:07:05Z",
      "hostport": "f1e0fe7594a2.ngrok.paid:443",
      "id": "ep_2wiYnCu6kBUYaTwzTibopmqBwBZ",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2wiYkkTod8MCSNSAMLin5agdmiE",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://f1e0fe7594a2.ngrok.paid",
      "tunnel": {
        "id": "tn_2wiYnCu6kBUYaTwzTibopmqBwBZ",
        "uri": "https://api.ngrok.com/tunnels/tn_2wiYnCu6kBUYaTwzTibopmqBwBZ"
      },
      "tunnel_session": {
        "id": "ts_2wiYnDn8MSvXS9XwKHQmho1VMRo",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2wiYnDn8MSvXS9XwKHQmho1VMRo"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-06T10:07:05Z",
      "upstream_url": "http://localhost:80",
      "url": "https://f1e0fe7594a2.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-06T10:07:02Z",
      "domain": {
        "id": "rd_2wiYmnPIv0afaIR8UmSTHf3EKNY",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wiYmnPIv0afaIR8UmSTHf3EKNY"
      },
      "edge": {
        "id": "edgtls_2wiYmlkpxH1meNJEnMRgJVL0q52",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2wiYmlkpxH1meNJEnMRgJVL0q52"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wiYmkuUTRAqODDwUd7VYk7vskJ",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-06T10:07:02Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
