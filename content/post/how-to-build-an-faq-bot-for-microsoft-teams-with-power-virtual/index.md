---
title: "How to build an FAQ bot for Microsoft Teams with Power Virtual Agents"
date: 2021-02-25T11:51:00-05:00
author: "Luise Freese"
githubname: LuiseFreese
categories: ["Community post"]
images:
- images/walle.png
tags: []
type: "regular"
---

In this blog I want to show you, how you can build, test and publish an
FAQ bot for Microsoft Teams within minutes. We will use the Power
Virtual Agents for Teams, which means, that you will not need any
additional license to your Microsoft 365 license, for reference see
also [Power Virtual Agents for Microsoft Teams
plan](https://docs.microsoft.com/power-virtual-agents/requirements-licensing-subscriptions#power-virtual-agents-for-microsoft-teams-plan).

## What is Power Virtual Agents? 

Power Virtual Agents belongs like Power Apps, [Power
Automate](https://flow.microsoft.com/) and Power Bi to the Power
Platform (wow, that was a powerFULL sentence :smiling_face_with_halo:).
You can create chatbots, which can interact with users in apps and
websites, trigger workflows and more, without the need of writing code.
You can choose if you want to use it in the [Power Virtual Agents
standalone web app](https://powerva.microsoft.com/) or as [app within
Microsoft Teams](https://aka.ms/PVAForTeams).

## Let's build a bot 

I will guide you how to create an FAQ bot. To feed our bot we will need
some FAQ so that our can bot can learn them. I will use [FAQ regarding
licensing](https://docs.microsoft.com/power-platform/admin/powerapps-flow-licensing-faq) :nerd_face:,
but you can choose any FAQ from a website or PDF or even Word file that
you like.

-   Open Teams
-   Select  the **Apps** icon
-   Search for **Power Virtual Agents**



{{< image alt="pva-teams.png" src="images/pva-teams.png" >}}

 
-   Click **Add**




{{< image alt="add-pva.png" src="images/add-pva.png" >}}
 


 

{{< image alt="pva-create.png" src="images/pva-create.png" >}}

-   Give your bot a name ans select a language that your bot shall
    understand (should be the same language as your FAQ)


 

{{< image alt="pva-create2.png" src="images/pva-create2.png" >}}

-   Click **Chatbots** - here you get an overview of ALL your chatbots

 

{{< image alt="my-chatsbots.png" src="images/my-chatsbots.png" >}}

### Add topics from any website 

-   Click **Topics**


{{< image alt="topics.png" src="images/topics.png" >}}
 
You see, that some basic topics are already created for you. You can
take a look later.

-   Click **Suggested**


{{< image alt="suggested.png" src="images/suggested.png" >}}
Now we want to work on feeding our bot with the FAQ from the website
that we selected.

-   Copy the URL auf the FAQ website
-   Paste the URL into the **Link to online content** field



{{< image alt="getfaq.png" src="images/getfaq.png" >}}

  

-   Click **Add**
-   Click **Start**

This may take now a couple of minutes. Grab a coffee in the
meanwhile: :hot_beverage:. Soon you will see the message that your new
suggested topics are now in:



{{< image alt="success.png" src="images/success.png" >}}

 
 

### Review & edit topics 

You can now review and edit each topic:

{{< image alt="edit-topics.png" src="images/edit-topics.png" >}}

-   Click **Save Topic**

After you are done with reviewing and editing your topics, you will need
to turn on the topics

-   Switch the toggle to **on**



{{< image alt="turn-on.png" src="images/turn-on.png" >}}

> Train your bot by entering more trigger phrases. This way, it is more
> likely that the Chatbot understands users asking questions even if
> they don't exactly match the trigger phrases
> 

Time to test the bot!



{{< image alt="end-connversation.png" src="images/end-connversation.png" >}}

You can now review and edit your topics until you are happy with the
results.

### Publish your Bot to Microsoft Teams 

-   Select the **Publish** icon


 

{{< image alt="publish.png" src="images/publish.png" >}}

-   Click **Add**

 

{{< image alt="add.png" src="images/add.png" >}}

-   Click **Add to Teams**



{{< image alt="publish-bot.png" src="images/publish-bot.png" >}}


-   Use your bot


{{< image alt="chat.png" src="images/chat.png" >}}

## Conclusion & what's next

It took us only a few minutes to create, test and publish a chatbot,
that now works inside of Microsoft Teams. Want to do some more? We could
extend the capabilities of our Power Virtual Agents bot: Let's say our
bot can't answer a question and needs to transfer the chat to a human
agent, who will answer that question. What if we trained the bot with
that answer so that our bot gets smarter over time? I will cover that in
one of my next blog posts. What do you use chatbots for? Did you already
try to make a 5 minute bot? Please share below :)
