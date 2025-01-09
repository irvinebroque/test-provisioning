`npx wrangler@latest deploy --x-provision`

```
-- START CF API RESPONSE: Bad Request 400

RESPONSE: {
  "result": null,
  "success": false,
  "errors": [
    {
      "code": 10085,
      "message": "workers.api.error.bucket_not_found"
    }
  ],
  "messages": []
}

-- END CF API RESPONSE
Your worker has access to the following bindings:
- R2 Buckets:
  - FOOOOOO: fooooo

✘ [ERROR] A request to the Cloudflare API (/accounts/ID/workers/scripts/test-provisioning) failed.

  workers.api.error.bucket_not_found [code: 10085]

  If you think this is a bug, please open an issue at:
  https://github.com/cloudflare/workers-sdk/issues/new/choose
```
