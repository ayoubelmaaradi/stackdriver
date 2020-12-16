## Java connect to stackdriver
This java project connets to gcp projects an fetchs the logs from stackdriver of specific gce vm instance

you will need a service account which already created,
configure the path to the json file of iam credentials in my case (/home/ubuntu/Documents/gcp.json)""
in java code

    GoogleCredentials credentials = GoogleCredentials.fromStream(new FileInputStream("/home/ubuntu/Documents/gcp.json"))

The json file credentials is attached to the project

$by$Ayoub$
# stackdriver
