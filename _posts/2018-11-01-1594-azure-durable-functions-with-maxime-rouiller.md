---
layout: episode
title: "Azure Durable Functions"
date: "2018-11-01"
episode_number: "1594"
episode_url: "https://www.dotnetrocks.com/?show=1594"
better_know_a_framework:
  title: "Responsinatior"
  url: "http://www.responsinator.com/"
links:
- title: "Durable Functions"
  url: "https://docs.microsoft.com/azure/azure-functions/durable-functions-overview"
- title: "Polly Project"
  url: "http://www.thepollyproject.org/"
- title: "Have I Been Pwned?"
  url: "https://haveibeenpwned.com/"
- title: "Durable Functions Samples"
  url: "http://aka.ms/durablefunctionssample"
- title: "Azure Logic Apps"
  url: "https://azure.microsoft.com/services/logic-apps/"
- title: "Azure Application Insights"
  url: "https://docs.microsoft.com/azure/application-insights/app-insights-overview"
- title: "Serverless Mix Tape"
  url: "http://aka.ms/serverlessmixtape"
- title: "Max's Blog"
  url: "https://maximerouiller.com/"
---

Functions are ephemeral and stateless - right? What if they weren't? Carl and Richard talk to Maxime Rouiller about durable functions in Azure. Maxime dives into the patterns that durable functions provide, starting with the chaining pattern, where you can declare a series (or chain) of function calls that only start when the previous function completes. And then onto the fan-out pattern that allows for an orchestrator to launch any number of simultaneous functions and then collect their results in whatever order they complete. There's more choices and a ton of possibilities in durable functions!
