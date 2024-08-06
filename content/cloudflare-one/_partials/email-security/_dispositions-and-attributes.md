---
_build:
  publishResources: false
  render: never
  list: never
---

- **Malicious**: Traffic invoked multiple phishing verdict triggers, met thresholds for bad behavior, and is associated with active campaigns.
- **Spoof**: Traffic associated with phishing campaigns that is either non-compliant with your email authentication policies ([SPF](https://www.cloudflare.com/en-gb/learning/dns/dns-records/dns-spf-record/), [DKIM](https://www.cloudflare.com/en-gb/learning/dns/dns-records/dns-dkim-record/), [DMARC](https://www.cloudflare.com/en-gb/learning/dns/dns-records/dns-dmarc-record/)) or has mismatching `Envelope From` and `Header From` values.
- **Suspicious**: Traffic associated with phishing campaigns (and is under further analysis by our automated systems).
- **Spam**: Traffic associated with non-malicious, commercial campaigns.
- **Bulk**: Traffic associated with [Graymail](https://en.wikipedia.org/wiki/Graymail_%28email%29), that fall in between the definitions of spam and suspicious. For example, a marketing email that intentionally obscures its unsubscribe link.