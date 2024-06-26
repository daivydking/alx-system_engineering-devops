Postmortem: Web Application Outage
Summary
On June 15, 2024, our web application experienced a significant outage lasting from 09:00 AM UTC to 12:30 PM UTC. During this period, users were unable to access the application, receiving a 503 Service Unavailable error. This outage impacted 100% of our user base.

The root cause of the outage was identified as a memory leak in a recently updated third-party library, which caused the application server to exhaust its memory resources. The issue was detected through monitoring alerts and was resolved by rolling back the library update and restarting the application server.

To prevent similar incidents in the future, we plan to enhance our monitoring systems, establish stricter testing protocols for third-party updates, and improve our incident response procedures.

For a detailed account of the incident, including the timeline, root cause analysis, and corrective measures, please refer to the full incident documentation.

https://docs.google.com/document/d/1ewk7n2opraOIoDH3hIOsz7m-sUeK9FcmDd8I5lKQJ14/edit?usp=sharing

https://docs.google.com/document/d/1nixPrpE05VSVamSQg6_IXhMpcDJe38L5_yRK-cYoeEo/edit?usp=sharing





