---

copyright:
  years: 2015, 2018
lastupdated: "2018-01-24"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}

# Deployment overview

After you have configured your workspace and built a working dialog, you can deploy your application by connecting the workspace to the interface your customers will use. You can also connect your workspace to other services (including other {{site.data.keyword.watson}} services). There are various ways you can do this.

- [**Testing in Slack**](test-deploy.html): You can use the test deployment tool to quickly deploy a chat bot in a Slack channel, using your workspace and a prebuilt Slack app. This option is the fastest and easiest way to test your workspace, but it has limitations.

- [**Deploying to a channel with the {{site.data.keyword.conversationshort}} connector**](conversation-connector.html): You can use the {{site.data.keyword.conversationshort}} connector to deploy a chat bot to Slack or Facebook Messenger, using your workspace and your own Slack or Facebook app.

- [**Building a client application**](develop-app.html): You can use the {{site.data.keyword.watson}} SDK for the language of your choice to develop your own application front end. Your application can then use the {{site.data.keyword.conversationshort}} APIs to communicate with the service, while also integrating with third-party services and your own business systems.

- [**Building a bot with Botkit**](integrations.html): You can use the Botkit framework to integrate your workspace with social media and messaging channels.