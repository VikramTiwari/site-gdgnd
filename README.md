# Polymer-Seed
Polymer based seed website

How to run on localhost
-----------------------

1. Install bower dependencies
```
bower install
```

2. Deploy on a server
2.1 Using Python 2.x
```
python -m SimpleHTTPServer
```
2.2 Using App Engine
```
gcloud app preview run .
```

How to deploy on App Engine
---------------------------
1. [Make a project on app engine](http://console.developers.google.com/)
2. Update the application identifier in app.yaml
3. [Install gcloud command line utils](https://cloud.google.com/sdk/gcloud/)
4. [Get authentication token](https://cloud.google.com/sdk/gcloud/#gcloud.auth)
5. [Install app engine component](https://cloud.google.com/sdk/gcloud/#gcloud.components)
6. [Initialize project and push-to-deploy](https://cloud.google.com/sdk/gcloud/#gcloud.init)

# Contributions
[Vikram Tiwari](http://google.com/+VikramTiwari)

Fork and build your own. Send a pull request to contribute.

# License
MIT
