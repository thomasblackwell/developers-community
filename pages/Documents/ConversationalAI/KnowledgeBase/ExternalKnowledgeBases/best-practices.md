---
pagename: Best Practices
redirect_from:
Keywords:
sitesection: Documents
categoryname: "Conversational AI"
documentname: Knowledge Base
subfoldername: External Knowledge Bases
permalink: knowledge-base-external-knowledge-bases-best-practices.html
indicator: both
---

For a flexible architecture and an optimal consumer experience, follow these best practices:

* Before you begin, ensure the content in the CMS is appropriate for conversational AI.
* Design a modular approach, where each knowledge base supports a particular classification in your business: Create external knowledge bases per category, likewise split the intents into domains based on category, and add multiple knowledge base integrations for use in bots. A modular approach like this makes it easier to use a knowledge base for a specific purpose in a bot. Moreover, it yields a faster response during the conversation.
* When you add an external knowledge base, configure it to use LivePerson AI whenever possible, and consider caching the fetched content at run time for improved performance.
* When using an external knowledge base with LivePerson AI, remember to manually [sync with the CMS](knowledge-base-external-knowledge-bases-external-kbs-with-liveperson-ai.html#sync-with-the-cms) after you make changes in the CMS.