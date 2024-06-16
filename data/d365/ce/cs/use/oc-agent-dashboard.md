---
title: Omnichannel Agent Dashboard in Omnichannel for Customer Service
description: Learn about the Omnichannel Agent Dashboard that shows work items for agents who use the Customer Service workspace or Omnichannel for Customer Service app.
author: neeranelli
ms.author: nenellim
ms.reviewer: shujoshi
ms.topic: how-to
ms.collection:
ms.date: 04/12/2024
ms.custom: bap-template
---

# View agent dashboard and agent conversations

[!INCLUDE[cc-use-with-omnichannel](../../includes/cc-use-with-omnichannel.md)]

When you sign in to the Customer Service workspace or Omnichannel for Customer Service app, the Omnichannel Agent Dashboard is the default view. You can set any dashboard as the default view by selecting the **Set As Default** option. The dashboard displays the following streams:

- My work items
- Open work items
- Closed work items

 ![Agent dashboard of Omnichannel for Customer Service app.](../media/oceh-oc-mydashboard.png "Screenshot of Agent dashboard in the Customer Service workspace app")

## My work items

In the **My work items** section, you can see the conversations (work items) that you're actively working on. Select the ellipsis and select the **Open** option to open the work item in a session.

## Open work items

In the **Open work items** section, you can see the conversations (work items) that are in an open state from all queues in which you're added as member. Select the ellipsis, and then select the **Assign to me** option to assign the work item to yourself. A session starts for the pick action. When you select a work item, you get a notification, and when you accept it, a session starts and the **Active Conversation** or case page loads.

The work item that you pick is moved from the **Open work items** section to the **My work items** section. If you reject the request, then the work item remains in the **Open work items** section.

## Closed work items

In the **Closed work items** section, you can see all the conversations that you closed on the same day. To view a closed work item, select its ellipsis button (**...**), and then select **Open** to view the details.

When you open a record from the **Closed work items** section, you can view the attributes of the closed conversation record. This action won't reopen or reactivate the conversation.

## Sort work items

On the dashboard, you can sort work items by the following categories:

- Modified On
- Work distribution mode (for open work items only)
- Customer
- Work stream
- Created On
- Transfer Count

## View multiple conversations at the same time

You can have multiple conversations open on multiple browsers and view the conversations in a split screen. Viewing multiple conversations side by side improves your ability to serve customer requests without the need to switch between sessions.

For example, when you select an active work item or monitor a conversation, it opens on the same browser. All other browsers remain as-is.

When multiple browsers are open, you see incoming conversation request on all the browsers. However, the browser that you select **Accept** from is the browser that loads that conversation. All other browsers remain as-is, with incoming notifications dismissed.

For example, for incoming calls, the conversation gets accepted only on one browser and the notification gets dismissed on other browsers.

### See also

[Create a record](oc-create-record.md)  
[Introduction to the agent interface](oc-introduction-agent-interface.md)  
[View communication panel](oc-conversation-control.md)  



[!INCLUDE[footer-include](../../includes/footer-banner.md)]
