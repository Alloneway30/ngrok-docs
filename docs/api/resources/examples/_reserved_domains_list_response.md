<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2vZ9SriBgDStK8ARPE73yDMuGkU",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2vZ9SriBgDStK8ARPE73yDMuGkU"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.5fcosryhhl59lf2dl.local-ngrok-cname.com",
      "created_at": "2025-04-11T03:22:11Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2vZ9SqY8LVDygZh7p3twTEi3B3C",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2vZ9SqY8LVDygZh7p3twTEi3B3C"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-04-11T03:22:11Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.5fcosryhhl59lf2dl.local-ngrok-cname.com",
      "created_at": "2025-04-11T03:22:11Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2vZ9SpzWRZB28j2yT0nkjLUcQdi",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2vZ9SpzWRZB28j2yT0nkjLUcQdi"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
