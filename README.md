A Google Pub-Sub for python 2.7 with PipEnv


# publish -
```
pipenv run python publisher.py <project-name> publish <topic-name>
pipenv run python publisher.py <project-name> publish-with-custom-attributes <topic-name>
```

# Subscriber
```
pipenv run python subscriber.py <project-name> receive <subscriber-name>
pipenv run python subscriber.py <project-name> receive_messages_with_custom_attributes <subscriber-name>
```