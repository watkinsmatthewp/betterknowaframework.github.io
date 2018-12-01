---
layout: episode
title: "Event Tracing for Windows"
date: "2017-08-17"
episode_number: "1468"
episode_url: "https://www.dotnetrocks.com/?show=1468"
better_know_a_framework:
- title: "UWP Visual Layer"
  url: "https://docs.microsoft.com/en-us/windows/uwp/composition/visual-layer"
links:
- title: "Semantic Logging"
  url: "https://github.com/MicrosoftArchive/semantic-logging"
- title: "Event Tracing for Windows"
  url: "https://msdn.microsoft.com/en-us/library/windows/desktop/bb968803(v=vs.85).aspx"
- title: "TraceEvent Library"
  url: "https://www.nuget.org/packages/Microsoft.Diagnostics.Tracing.TraceEvent/"
- title: "System.Diagnostic.Tracing.EventSource"
  url: "https://msdn.microsoft.com/en-us/library/system.diagnostics.tracing.eventsource(v=vs.110).aspx"
---

How can ETW help you? While at NDC in Oslo, Carl and Richard talked to Dina Goldshtein about her work instrumenting applications. This leads to a conversation about Event Tracing for Windows, which Dina uses primarily to take measurements of different applications running on Windows machines - but you can have your app add to the ETW stream as well. Monitoring, profiling and debugging are all different tasks that can take advantage of the data provided by ETW, it depends on your needs at the time. Lots of discussion on the impact of measuring as well - nothing is free!
