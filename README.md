# awsconfig-events-data
An open source repository of production like awsconfig events.

The awsconfig events come from an account that creates and destroys infrastructure automatically and sends the awsconfig notifications to a SQS queue via SNS. The SQS messages and awsconfig events are periodically archived as a JSON array then get uploaded here as a release.

Check out the latest releases https://github.com/automoto/awsconfig-events-data/releases

The releases are named and tagged using the timestamp when they were created. Records in the data are generally an archive of awsconfig events from within the past few hours or the last 24 hours from the release being created.
