# E-commerce Webhook Simulator

Simulate webhook responses for e-commerce platforms to test integrations and event handling.

```bash
curl -X POST https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/ \
  -H "Content-Type: application/json" \
  -d '{"order_id":"ORD123456","event":"order_placed","timestamp":"2025-04-24T14:01:21Z"}'
