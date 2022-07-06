---
title: "Bots"
chapter: false
weight: 20
---

## Bot Flow Setup

Bot flows are the orchestrator of our self service offerings and are where we will tie our knowledgebase together with bot functionality.

Within Architect you will hover over flows and select Digital Bot Flow and Add. Using the same best practice of meaningful names and descriptions you will create a new Bot Flow

![image](/images/botflowselect.PNG)

Bots are comprised of 2 primary components - 
**Intents**
>Intents are ultimately what you are expecting your bot to be able to assist with, such as providing account information or loan information.

When adding a new intent you will provide an intent name (such as accountInfo) and map it to a new or existing task
>Mapping to tasks allows you to break your bot into bite sized portions of functionality to simplify administration and readability. You can use a single task to manage all of your bot functionality if you prefer.

![image](/images/addIntent.PNG)

**Utterances**

Utterances are what you're expecting a customer to say in order to get the information they need, one customer might say "what is my account balance?", while another might just say "Balance". The more utterances you provide, the more capable your bot will become at understanding what a customer is asking for.

**Slots**

Slots are the individual words we need to capture to determine the focus of the intent. 

>While a customer might say they need to check their balance, we need to know what account they need to check their balance on. The account type in this example would be the slot.

When constructing slots, you can provide synonyms to broaden the likelihood of capturing what the customer is referring to. 

![image](/images/slots.PNG)

**Tieing the component together**

Within intents we can begin bringing together the slots and utterances we've constructed by highlighting words or phrases within your list of utterances and mapping slots to them.

>Note: you can capture multiple slots within a single utterance. In the example below we highlight "monies" and set it to a slot type of Balance. We will then highlight "checking" and map it to account type

![image](/images/slotHighLight.PNG)

Once you have completed your slot mapping, you will see colored indicators of the key words within your utterance and what slots they will be filling

![image](/images/slotmapping.PNG)