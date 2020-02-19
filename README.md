# Crime NER service

**Steps to start up this service**

1. Clone this repository
```
git clone https://github.com/abhishekr7/crime-extractor.git
cd crime-extractor
```

2. Start the service
```
rasa run --enable-api -m models/nlu-20200212-095836.tar.gz
```

3. If 2 doesn't work try running it in debug mode
```
rasa run -m models/nlu-20200212-095836.tar.gz --enable-api --cors '*' --debug
```
