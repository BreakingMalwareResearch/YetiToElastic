# YetiToElastic
YETI (Your Everyday Threat Intelligence) Integration to Elastic Stack.

Additional Information in [enSilo's BreakingMalware Blog](https://blog.ensilo.com/yeti-eslasticstack).

Usage Example:

```python
from yeti_to_elasticsearch import YetiFeedSender

sender = YetiFeedSender("yeti-feeds", excluded_feeds=("AsproxTracker"),
                        elastic_hostname="="<elasticsearch hostname>",
                        elastic_port=<elasticsearch port>)
sender.extract_and_send()
```
