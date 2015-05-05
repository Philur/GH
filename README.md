# GH
Git Hook test

/usr/bin/curl --user JENKINS_USER:PASSWORD -s \
curl "http://ec2-54-154-86-151.eu-west-1.compute.amazonaws.com/job/GH-test/build?token=TOKEN_NAME&cause=Commit+By+USER_NAME&delay=15sec"


https://jenkins/job/Sandbox/buildWithParameters?delay=0sec&Test=foo


 JENKINS_URL/job/GH-test/build?token=TOKEN_NAME or /buildWithParameters?token=TOKEN_NAME
 
http://ec2-54-154-86-151.eu-west-1.compute.amazonaws.com/job/GH-test/build?token=TOKEN_NAME&cause=Cause+CommitByPhilur&delay=15sec
 
Optionally append &cause=Cause+Text to provid

Updated pre-push hook locally - with curl and username/password