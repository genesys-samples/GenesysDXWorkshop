---
title: "Message Flows"
chapter: false
weight: 40
---
With our Knowledgebase and Bot constructed, it is time to tie all of the work together with a simple message flow
## Construct your Queue
> Queues are logical groupings of agents for routing purposes, these are often paired with ACD skills for more refined interaction routing. The easiest way to differentiate queue's and ACD skills is to think of a Billing Queue as being the list of all of your agents that handle billing inquiries. Within that Queue you might have agents that speak spanish, or specialize in collections; ACD skills are tagged to individual interactions to ensure the customer is reaching the agent that most fits their needs (such as spanish).

Within the main administration panel search for "queues" in the search bar and construct a new queue.
No additional queue configuration is required, however you can add yourself to this queue in the members tab for later testing.

![image](/images/queueconstruction.PNG)

## Construct your Flow
Now that our queue has been constructed, we will navigate over to architect by searching for and selecting it from the administration panel

Once in architect, ensure you are on the correct flow type of "Inbound Message", and select Add

![image](/images/SelectFlowType.PNG)

Provide your flow a name and description that will be clear for future references, select your language and division. Error Event Transfer Queues are not required, however in the event of a logic failure they will allow customers to still reach an agent.
>it is best practice to use meaningful names and descriptions to assist colleagues in easily finding and referencing the flow for future work or troubleshooting 

![image](/images/CreateFlow.PNG)
