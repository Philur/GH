# GH
Git Hook test

/usr/bin/curl --user JENKINS_USER:PASSWORD -s \
curl "http://JENKINS_URL/job/GH-test/build?token=TOKEN_NAME&cause=Commit+By+USER_NAME&delay=15sec"
or /buildWithParameters?token=TOKEN_NAME
