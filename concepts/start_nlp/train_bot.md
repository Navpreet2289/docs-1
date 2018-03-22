---
layout: concept
title: Train your bot
permalink: /concepts/train-your-bot
---

## Create an intent

Everything your bot knows is in the intents. Intents are boxes including expressions that mean the same thing but are paraphrased. Each intent corresponds to one action your user wants to perform. For example, an intent **greetings** makes your bot understand when a user says \`Hello\`.

In the meeting bot you will find all intents you need to create a bot that can book you a meeting room.
Explore each intent a little bit by clicking on the name and you will see expressions inside that train your bot to understand the user intent ;)

Add a new intent called **Thanks**, to understand when users will thank your bot! Type \`thanks\` in the input Search and Fork from the community, then click on the **Search button**.

As the platform is collaborative, there are a lot of intents already created. Select one of the first results and just click on the **FORK** button on the right.

![Recast.AI fork intents](https://cdn.recast.ai/man/recast-ai-fork-intentb.png)

## Add expressions

You have a new intent in your bot! Click on it. The optimal setting for a great intent is to contain around twenty paraphrased expressions. Add some expressions your users will say by typing the sentence in the field **Add an expression**.

![Recast.AI expressions](https://cdn.recast.ai/man/recast-ai-add-expressionsc.png)

## Use entities

Go to the **Booking** intent. If you click on one of the expressions you will see highlighted words, with tags. These are **entities**. They’re keywords detected in expressions that are important to you in order to automate a task.

![Recast.AI intents](https://cdn.recast.ai/man/recast-ai-entitiesb.png)

We automatically detect [31 different entities](https://recast.ai/docs/api-reference#list-of-entities) like: Location, Datetime, Colors, Emojis, Number… We call them gold entities. If you need another entity, a custom one like a **meal** for a cooking bot, just select what you want to tag as your new entity and type a name. The more examples you provide, the better the detection will be ;)

![Recast.AI tag entities](https://cdn.recast.ai/man/recast-ai-tag-entitiesb.png)

## Use the console

Once you’ve set up your bot, you can test it with the console. Click on the **TEST** bubble icon on the top right to make it appear. Select the tab **Analyse**, and type a sentence to test if your bot is well trained: \`I want meeting room 2 for tomorrow\`

![Recast.AI NLP analyse](https://cdn.recast.ai/man/recast-ai-test-consoleb.png)

You will see which intent is detected and which entities are extracted. Click on the **Smart view** toggle to switch the view to the JSON mode.
The JSON contains a lot of useful information about the message you’ve sent, like all the enrichments we can provide for the gold entities.

![Recast.AI NLP JSON](https://cdn.recast.ai/man/recast-ai-console-jsonc.png)

## Train your bot

When your message doesn’t match any intent, you have to train your bot. Go to the **MONITOR** tab on your bot page, and click on the **Log feed** menu.
Here are the logs of your bots. Select the expressions that did not match and redirect them to the right intent. After that, check that your custom entities have been automatically tagged. If not, do it and remember “Bot trained, mommy approved!”.

![Recast.AI bot monitor](https://cdn.recast.ai/man/recast-ai-monitorb.png)