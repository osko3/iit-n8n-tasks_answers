# Short explanation:
I built a data pipeline that scrapes web pages using Jina.ai and then processes that content with an LLM to create structured summaries. Since some pages are huge, I added a bit of JavaScript logic to trim the text so it doesn't hit the model's token limit. The final step ensures that the person calling the webhook gets only the clean JSON data they need, without all the extra API metadata.

# Screenshots:
![10B1](10B1.png)
![10B2](10B2.png)
![10B3](10B3.png)
![10B4](10B4.png)
![10B5](10B5.png)
![10B6](10B6.png)
![10B7](10B7.png)
