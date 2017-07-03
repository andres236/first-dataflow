# Quickstart Dataflow Pipeline using Dataflow 2.0 SDK

This is a Simple Word Count example build using the latest Dataflow 2.0 SDK. https://cloud.google.com/dataflow/docs/quickstarts/quickstart-java-maven

# Prerequisite 

## Install Cloud SDK shell
Cloud SDK is a set of tools that you can use to manage resources and applications hosted on Google Cloud Platform. These include the gcloud, gsutil, and bq command line tools.

## Install Apache Maven & Java 

Not going to cover the specifics here, just google jdk + maven installation for your specific platform.

# Run your first Dataflow Pipeline
Build and run the example pipeline locally using the direct runner by using the mvn compile exec:java command in your shell or terminal window. For the --output arguments specify a local file path.

```bash
 mvn compile exec:java \
      -Dexec.mainClass=com.example.WordCount \
      -Dexec.args="--output=./output/"
```
