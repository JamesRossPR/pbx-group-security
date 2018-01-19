---
draft  : true
title  : Creating a Neo4J graph for the recruitment process
author : Dinis Cruz
notes:
  - english and structure needs fixing
---

Creating a Neo4J Graph for the Recruitment Process

A good way to think of our recruitment process is to picture it as a giant graph: On it, you have the candidates to commit the work for, the potential candidates, the jobs that we have, the skills that we need, the interaction that we have with them, and the connection with members of the team or with communities. 

I want to see if we can create a way in Neo4J (a graph database) to store, to capture and to visualize, sorry, to store and visualize these relationships. And if Neo4J is the property base graph, I can imagine something where the candidates are nodes, the skills are nodes, and the edges are our relationships and the connections between them. 

Another question I have is about how we will store the data -- ideally, the raw data to be stored. Ideally, it should be vault format, so that it's easy to maintain and easy to update. And, ideally, it should be on Github, which is then assumed and injected into a graph, so we can visualize this.

And the reason for this is so you can easily maintain it and make changes. It would allow us to scale easily, as well. Because the beauty of the graph is that you can evolve the scheme. As you go along, you can create this evolutionary design. The more you understand it, and the more data that arrives, the more you can create relationships. Eventually, you reach a stable state, where you have a perfect place to capture the information, and that's when you know it's working. You know it's working, when it's very easy to add news and relationships to the graph based on your data -- the actions. And that gives a feedback group on what actually is going on. This can drive your behavior. And that feedback loop can be extremely important. 

I'm wondering if we can use our current recruitment process as a way to visualize this. Can we use graphs in the recruitment process as a way to make it much more efficient and much more effective? We owe it to the candidates to create a great experience for them. We're also able to find, new and better, candidates and find exactly a great place to capture all the data that we already have, but when you look at it, it's already really complex, and if we don't do these, we actually get swamped. Even in basic things, when to reply? how to reply? how to note? how to put pressure? how to value? how to get feedback? So, we actually create a really powerful workflow.

My view is that a graph would serve us well for recruitment. So, a great challenge for a candidate would be to suggest a way to do this. Have them create a good example of a simple recruitment process using Neo4J.

