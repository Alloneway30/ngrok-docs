<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
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
          "started_at": "2025-05-06T10:06:47Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.ydr7cqzshz4ftoxf.local-ngrok-cname.com",
      "created_at": "2025-05-06T10:06:47Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2wiYku8J3Iy6Vx8sahdQp0sFNLR",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2wiYku8J3Iy6Vx8sahdQp0sFNLR"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2wiYkk9zE1d2pF9OhhkURVHL6Cg",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2wiYkk9zE1d2pF9OhhkURVHL6Cg"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.ydr7cqzshz4ftoxf.local-ngrok-cname.com",
      "created_at": "2025-05-06T10:06:46Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2wiYkrYoYxL71lOAcUIsTcdenhj",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2wiYkrYoYxL71lOAcUIsTcdenhj"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
