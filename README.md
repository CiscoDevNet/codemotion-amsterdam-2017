# Cisco's presence at CodeMotion Amsterdam 2017 (May 16,17)

[CodeMotion Amsterdam](http://amsterdam2017.codemotionworld.com ) proposes 6 tracks in parallel, plus codelabs.

You have more than one opportunities to learn more about Cisco APIs:
- [May 16th, 09:00-09:15](http://amsterdam2017.codemotionworld.com/wp-content/themes/event/detail-talk.php?detail=5855): The power of connections (KeyNote).
- [May 16th, 11:30-12:10](http://amsterdam2017.codemotionworld.com/wp-content/themes/event/detail-talk.php?detail=5838): From IoT to Human Interactions: Voice and Messages to the rescue.
- [May 16th, 12:30-13:10](http://amsterdam2017.codemotionworld.com/wp-content/themes/event/detail-talk.php?detail=5839): Building advanced ChatBots.
- [May 16th, from 10:30 till 18:00](http://amsterdam2017.codemotionworld.com/schedules/labs/): 20' instructor-led codelabs. Learn to build ChatBots, add Video or SMS capabilities to your existing apps with Cisco Spark and Tropo APIs.
Access to the labs is free, provided by [Cisco DevNet](http://developer.cisco.com).

<!-- To discover what's going on in real-time
>
>    call **+39-069-480-4685** and meet the [Tropo Voice Machine](https://github.com/ObjectIsAdvantag/codemotion-rome-2017-api)-->



# <a id="code-labs"></a>Thanks for joining the DevNet CodeLabs 

__Pick a lab in the list below to experience how to [create a ChatBot](#lab-botl-ngrok), or add [Voice and SMS interactions](#lab-voice-machine) to existing apps. Note that the labs below can be taken in any order as they are independant one from another.__


## From ZERO to Enterprise ChatBots with Cisco Spark APIs

In this labs serie, you’ll go through the various steps to build Chat Bots for Cisco Spark: create a Bot account, register it into Cisco Spark, run your own bot locally, deploy it live...

1. <a id="lab-botl-ngrok"></a>[**Run a Cisco Spark Bot locally** (15min)](labs/SPARK-2-Run-a-Cisco-Spark-Bot-locally.pdf): as introduced earlier, Cisco Spark Bots are applications that invoke the Cisco Spark API under a Bot account identity. In this lab, you will learn to run your own Cisco Spark Bot by taking several steps: create a Bot account, run a sample Cisco Spark bot on your local machine, expose your bot to the internet, and register Webhooks in order to have Cisco Spark post notifications to your bot.

2. [**Run a Cisco Spark Bot on Cloud9** (25 min)](labs/SPARK-3-Deploy-a-Cisco-Spark-Bot.pdf): in this lab, you will learn to run your own Cisco Spark Bot by taking several steps: create a Bot account, deploy a nodejs code sample from Cloud9 development environment, and finally register Webhooks to have your bot receive events as they happen in Cisco Spark rooms.

3. [**Run a Cisco Spark Integration locally** (15 min)](labs/SPARK-4-Run-a-Cisco-Spark-Integration-locally.pdf): by creating custom applications, developers can tie together Cisco Spark with existing enterprise processes and data. For example, you may add the Jira Integration to an existing Room and get the participants notified as Jira issues (EPIC, Story, Task or Bugs) are created or updated. The process used to request permissions is called "OAuth Grant Flow".
In this lab, we’ll go through an existing NodeJS example that displays the name of Cisco Spark users. We will deploy it on Heroku, and register it as a Cisco Spark Integration.

4. [**Deploy a Cisco Spark Integration on Heroku** (15 min)](labs/SPARK-5-Deploy-a-Cisco-Spark-Integration.pdf): as introduced in previous labs, Cisco Spark Integrations and Bots concretize Cisco Spark’s extensibility. Cisco Spark Integrations let your applications request permission to invoke the Cisco Spark API on behalf of other users. In this lab, we’ll go through an existing NodeJS example that displays the name of Cisco Spark users. We will deploy it on Heroku, and register it as a Cisco Spark Integration.

5. [**Introduction to Cisco Spark Apps** (15min)](labs/SPARK-1-Introduction-to-Cisco-Spark-Apps.pdf): in this lab, we will take a few steps back to present Cisco Spark's extensibility "Big Picture",
As we introduce Cisco Spark API, you will use the interactive documentation to experience Cisco Spark programmability. We’ll then go through a few use-cases, and drill into the fundamentals of Cisco Spark Apps.
After this lab, you should have enough knowledge to easily navigate among Cisco Spark Learning Labs, as well as broader technical resources such as “Spark for Developers” and DevNet ’s “Cisco Spark Community of Interest”.  


## Add SMS and Voice to your apps using Tropo APIs

In this labs serie, you'll learn to give a voice to your code and send SMS in batch by taking several steps: create an inbound Voice channel for your application, attach a Tropo phone number to your application, create outbound sessions dynamically to mix Voice an SMS..

6. <a id="lab-voice-machine"></a>[**Create a Voice Machine** (15 min)](labs/TROPO-1-Create-a-Voice-Machine.pdf): Tropo is a cloud API that allows you to automate communications over the phone and SIP VoIP networks. Both voice and SMS are supported, and no telephony knowledge is needed. In this lab, you will learn the basics of how to use Tropo. You'll create a simple Tropo application, get a Tropo number in a country of your choice, and build a simple Voice Machine controlled by your code.
      
7. [**Mixing Voice and SMS** (10 min)](labs/TROPO-2-Mixing-Voice-and-SMS.pdf): learn to mix Voice and SMS in a single call. You'll build an app that will prompt you for a phone number and send a SMS containing a randomly selected quote.

8. [**Outbound SMS Dialer** (15min)](labs/TROPO-3-Outbound-SMS-Dialer.pdf): create a basic dialer that will send multiple SMS to a list of Mobile phone numbers read from a CSV file.


## Add Video to your Mobile and Web applications with Cisco Spark SDKs

Reach to your Cisco technology mentors to get info about the Spark SDKs early access programs,
as well as the code samples you can run today on your own machines.


## How to take the labs after the conference

Simply register online at [DevNet - Cisco's Developer Program](http://developer.cisco.com), 
and go through the [Cloud Collaboration Learning Track](https://learninglabs.cisco.com/tracks/collab-cloud) which gathers all labs above.







