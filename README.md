# Site-GDGND - An Amazing Website
Polymer based GDG New Delhi website

How to run on localhost
-----------------------
Install bower dependencies
```
[sudo] bower install
```
Now run a localhost server using Python 2.x
```
python -m SimpleHTTPServer
```
or using App Engine
```
gcloud app preview run .
```

How to publish on App Engine using release pipelines
----------------------------------------------------
1. [Make a project on app engine](http://console.developers.google.com/)
2. [Change the name of application in app.yaml](https://github.com/VikramTiwari/site-gdgnd/blob/master/app.yaml#L1)
2. [Install gcloud command line utils](https://cloud.google.com/sdk/gcloud/)
3. [Get authentication token](https://cloud.google.com/sdk/gcloud/#gcloud.auth)
4. [Install app engine component](https://cloud.google.com/sdk/gcloud/#gcloud.components)
5. [Initialize project and push-to-deploy](https://cloud.google.com/sdk/gcloud/#gcloud.init)

# Contributions
[Vikram Tiwari](http://google.com/+VikramTiwari)

Fork and build your own. Send a pull request to contribute.

# License
MIT
