# Cloud Key Management Service

Google [Cloud Key Management Service](https://cloud.google.com/kms/) is a
cloud-hosted key management service that lets you manage encryption for your
cloud services the same way you do on-premise. You can generate, use, rotate and
destroy AES256 encryption keys. These sample Java applications demonstrate
how to access the KMS API using the Google Java API Client Libraries.

## Quickstart

Install [Maven](http://maven.apache.org/).

Build your project with:

    mvn clean compile assembly:single

You can run the quickstart with:

    java -cp target/kms-samples-1.0.0-jar-with-dependencies.jar \
        com.example.Quickstart [your-project-id]

and can see the available snippet commands with:

    java -cp target/kms-samples-1.0.0-jar-with-dependencies.jar \
        com.example.Snippets

For example:

    java -cp target/kms-samples-1.0.0-jar-with-dependencies.jar \
        com.example.Snippets createKeyRing -p <your-project-id> myFirstKeyRing
