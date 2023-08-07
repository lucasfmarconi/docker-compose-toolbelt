#### Example cmd
Command line for running a single docker locust container:

```bash
docker run -p 8089:8089 -v $PWD:/mnt/locust locustio/locust -f /mnt/locust/locustfile.py
```

##### The locustfile.py is being ignored due to this file might have sensitive data added for the tests. Check the link if help is needed to write a new one https://docs.locust.io/en/2.16.0/quickstart.html#your-first-test