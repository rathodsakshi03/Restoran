Restoran Management using Azure Web
App Bot

Chapter-I

Objective

In this project, I would be using QnA Maker Service to make a Chatbot that give solution and answer your question about Restoran related.

Problem Statement

Develop a Chatbot for Restoran Management that solve the customer problems related to enhance the overall dining experience for customers while optimizing internal restaurant operations.

Problem Context

The purpose of chat bots is to support and scale business teams in their relations with customers. It could live in any major chat applications like Facebook Messenger, Slack, Telegram, Text Messages. Chatbot applications streamline interactions between people and services, enhancing customer experience. At the same time, they offer companies new opportunities to improve the customers engagement process and operational efficiency by reducing the typical cost of customer service. This project is focussed on building a custom chatbot that will be your fundamental step of the learning curve of building your own professional chatbots. But you must be tired of the weird chat bots out there in the world which are made for business purposes? In this project, we would be building an extensive Chatbot service, to which you can talk. And talking to a chatbot would not be business driven. It would just be casual conversations. Collaborating with these types of APIs is very much critical as in today's world the popular chatbots do much more than simply having a data-driven conversation; to supplement additional user-oriented features.

What is a Microsoft Azure QnA Maker Service?

QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. QnA Maker is commonly used to build conversational client applications, which include social media applications, chat bots, and speech-enabled desktop applications. QnA Maker does not store customer data. All customer data (question answers and chat logs) is stored in the region the customer deploys the dependent service instances in. For more details on dependent services see here. This documentation contains the following article types: • The quickstarts are step-by-step instructions that let you make calls to the service and get results in a short period of time. • The how-to guides contain instructions for using the service in more specific or customized ways. • The conceptual articles provide in-depth explanations of the service's functionality and features. • Tutorials are longer guides that show you how to use the service as a component in broader business solutions. When to use QnA Maker • When you have static information - Use QnA Maker when you have static information in your knowledge base of answers. This knowledge base is custom to your needs, which you've built with documents such as PDFs and URLs. • When you want to provide the same answer to a request, question, or command - when different users submit the same question, the same answer is returned. • When you want to filter static information based on meta-information - add metadata tags to provide additional filtering options relevant to your client application's users and the information. Common metadata information includes chit-chat, content type or format, content purpose, and content freshness. • When you want to manage a bot conversation that includes static information - your knowledge base takes a user's conversational text or command and answers it. If the answer is part of a pre-determined conversation flow, represented in your knowledge base with multi-turn context, the bot can easily provide this flow.

After you publish your knowledge base, a client application sends a user's question to your endpoint. Your QnA Maker service processes the question and responds with the best answer.

Problem’s Primary Goals

• Setting up a chatbot that can order your requirements (Dining, Food, Restoran Environment and offers).

• Using a QnA Maker Bot service to build Restoran Management chatbot.

• Having a real-world chatbot, to which you can chat like you chatting to a real person and solve your problems.

Input

For input source i use a Editorial custom question and answer type.

Output

![image](https://github.com/leekarande29/Restoran/assets/54453317/d3755f2b-1818-4aed-ae46-aeac93313698)
![image](https://github.com/leekarande29/Restoran/assets/54453317/dfc152b6-e93f-421d-9ff9-03140a6d3f23)
![image](https://github.com/leekarande29/Restoran/assets/54453317/add190be-0d6c-4440-b51c-e3f1e00e5787)
![image](https://github.com/leekarande29/Restoran/assets/54453317/83e05ae3-4fcf-4f53-bb7a-79e4a312d7c4)
![image](https://github.com/leekarande29/Restoran/assets/54453317/fd4aa75a-664c-4593-9609-d89ed43e2c7c)
![image](https://github.com/leekarande29/Restoran/assets/54453317/7e33b234-eb9e-404a-8068-647ebe920898)
![image](https://github.com/leekarande29/Restoran/assets/54453317/51f3c0e5-37f0-4302-8195-9e4c9d94ce76)
![image](https://github.com/leekarande29/Restoran/assets/54453317/6a660ff5-0665-48f0-8154-99b79a1da57f)


Chapter-II

Microsoft Azure Bot Framework Architecture(Resource visualizer)
![image](https://github.com/leekarande29/Restoran/assets/54453317/e6f40283-52e2-43a1-ad67-953eff152015)


Microsoft Azure QnA Maker Development Cycle

![image](https://github.com/leekarande29/Restoran/assets/54453317/097493eb-2b7b-495c-9817-42cf97ba8fff)


Life Cycle of a Conversational Bot

![image](https://github.com/leekarande29/Restoran/assets/54453317/d24da468-e7fa-49e4-8157-6d4a6fbcb690)


How to build a bot

Azure Bot Service and the Bot Framework offer an integrated set of tools and services to facilitate the building process. Choose your favorite development environment or command line tools to create your bot. SDKs exist for C#, Java, JavaScript, Typescript, and Python. We provide tools for various stages of bot development to help you design and build bots.

Plan

As with any type of software, having a thorough understanding of the goals, processes and user needs is important to the process of creating a successful bot. Before writing code, review the bot design guidelines for best practices and identify the needs for your bot. You can create a simple bot or include more sophisticated capabilities such as speech, natural language understanding, and question answering.

Build

Your bot is a web service that implements a conversational interface and communicates with the Bot Framework Service to send and receive messages and events. Bot Framework Service is one of the components of the Azure Bot Service and Bot Framework. You can create bots in any number of environments and languages.

![image](https://github.com/leekarande29/Restoran/assets/54453317/af0321e5-29a4-408f-9dcc-f61a6e5b2fc3)


Test

Bots are complex apps with a lot of various parts working together. Like any other complex app, this can lead to some interesting bugs or cause your bot to behave differently than expected. Before publishing, test your bot. We provide several ways to test bots before they are released for use: • Test your bot locally with the emulator. The Bot Framework Emulator is a stand-alone app that not only provides a chat interface but also debugging and interrogation tools to help understand how and why your bot does what it does. The Emulator can be run locally alongside your in-development bot application. • Test your bot on the web. Once configured through the Azure portal your bot can also be reached through a web chat interface. The web chat interface is a fantastic way to grant access to your bot to testers and other people who do not have direct access to the bot's running code.

Publish

When you are ready for your bot to be available on the web, publish your bot to Azure or to your own web service or data center. Having an address on the public internet is the first step to your bot coming to life on your site, or inside chat channels.

Connect

Connect your bot to channels such as Facebook, Messenger, Kik, Slack, Microsoft Teams, Telegram, text/SMS, and Twilio. Bot Framework does most of the work necessary to send and receive messages from all these different platforms - your bot application receives a unified, normalized stream of messages regardless of the number and type of channels it is connected to. For information on adding channels, see channels topic.

Evaluate

Use the data collected in Azure portal to identify opportunities to improve the capabilities and performance of your bot. You can get service-level and instrumentation data like traffic, latency, and integrations. Analytics also provides conversation-level reporting on user, message, and channel data.

Decision Making Between LUIS and QnA Maker

When to use the QnA Maker?

If your organization has lots of static questions and answers), take advantage of out of the box features of QnA Maker. Upload your static questions and answers into QnA Maker Portal, and your application can call QnA API to search for questions asked by the user on the front-end application and return the response.

When to use the LUIS?

If you would like to design the application which needs to extract the information from the user’s questions and further process their intents, then use the LUIS.

Process

![image](https://github.com/leekarande29/Restoran/assets/54453317/acbe2231-c630-4f20-a845-e0af28ec160d)


Task 1

Create a Resource Group on Azure

![image](https://github.com/leekarande29/Restoran/assets/54453317/e86f9656-4e81-4486-a49a-468c8ce1f65e)


Task2

Create a Language Service on Azure

![image](https://github.com/leekarande29/Restoran/assets/54453317/a3448714-3947-4900-b540-af5b796909f0)


Task3

Create a Knowledge Base on Azure

![image](https://github.com/leekarande29/Restoran/assets/54453317/b3016dd5-b9a1-4276-a067-11140df235de)


Task4

Create an App Service on Azure

![image](https://github.com/leekarande29/Restoran/assets/54453317/70282ecd-94da-4427-bd08-246232c2d403)


Task5

Create a Web App Bot on Azure

![image](https://github.com/leekarande29/Restoran/assets/54453317/7b3fd136-4c7c-4aca-8f41-ce02bf202c05)


Task6

Testing my Bot on Azure

![image](https://github.com/leekarande29/Restoran/assets/54453317/92aa0e68-c61f-4e11-98ce-4b07c462ed81)


![image](https://github.com/leekarande29/Restoran/assets/54453317/8e8412a7-5e2e-430f-97ae-8e8ef0066ff8)


![image](https://github.com/leekarande29/Restoran/assets/54453317/184dcd3a-2ad3-4443-aa35-62d355ac9b59)

Expected Outcome

By the end of this milestone, you would be having a working chatbot system that solve your problems about Muscle gaining,Diet Plan and Lose fat.

Technologies / Tools Used

• Microsoft Azure QnA Maker Service and cognitive service

• Git Hub

• Azure Storage account and App Service

• Microsoft Visual Studio

URLs
Drive video URL: 

PDF File With ScreenShoots and explanation about project: https://drive.google.com/file/d/1UHcyuAY69bG5xlvqVL_Q5bsffIUxcAkR/view?usp=sharing

working project URL: https://rathodsakshi03.github.io/Restoran/

Azure Account ID: sahilrathod2407@gmail.com

Acknowledgements
My sincere thanks, to Microsoft for an impressive QnA Maker service on MS Azure Cloud to make the chatbot development easy. Sincere appreciation to Team of Future Ready Talent who supported and encouraged us to work on this project.
