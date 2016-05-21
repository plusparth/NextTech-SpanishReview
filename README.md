# NextTech-SpanishReview
Spanish Review Sheet for Ms. King for the sophomore year SMCS Software Engineering Project.

This code uses a lot of examples from Google App Engine sources.

## Running locally 
This example uses the
[Maven gcloud plugin](https://cloud.google.com/appengine/docs/java/managed-vms/maven).
To run this sample locally:

    $ mvn appengine:devserver

## Deploying
In the following command, replace YOUR-PROJECT-ID with your
[Google Cloud Project ID](https://developers.google.com/console/help/new/#projectnumber).

    $ mvn appengine:update

