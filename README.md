# Welcome
A short introduction to the more technically inclined person...

All projects available upon request, please just send me your "Collaborator" user details => dean.greenwood@gmail.com

### Current Projects

#### C# Microservice Generating Market Data

Using ASP.NET to implement Producers and Consumers and generating market data that is persisted to Kafka topics and an underlying database implementation.

#### Fast String Parsers and Associated File/Pipeline writing/reading

Pushing the envelop to ensure we can read/parse and process data in ms.  Using Span&lt;char&gt; primarily to enable fast slicing and substring of data read from files.

Separation of Span&lt;T&gt; implementation and Memory&lt;T&gt; implementations to exploit higher-level abstractions such as Channel&lt;T&gt;/Pipelines, or via byte[] arrays streamed across the wire.

#### Complete End-to-End Projects

A collection of simple Templates for C# and Python, primarily; to use for base projects which include code-analysers, build, testing, auto-deployment.

Use of cdk tooling to build a target AWS environment, before enabling auto-deployment upon successful build/release cycle.

This is a change being made directly to 'main'
