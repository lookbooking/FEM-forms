
# python-kafka
### Recipes Web Crawler Using Kafka and Python

##### Requirements:
1 - Kafka

Mac:
```Mac OS X
brew install kafka
```

Or direct by Apache Kafka: https://kafka.apache.org/downloads

2 - Change the ``kafka/server.properties`` to the following configuration section:

```buildoutcfg
listeners=PLAINTEXT://localhost:9092
```

3 - Create a virtalenv for Python3 `python3 -m venv env` and then `source env/bin/activate`

4 - Install the dependencies from requirements.txt, run `pip install -r requirements.txt`