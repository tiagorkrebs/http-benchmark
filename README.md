# http-benckmark

An open source load testing tool.

Define user behaviour with Python code, and swarm your system with millions of simultaneous users.

Based on http://locust.io

Install project
```console
$ git clone https://github.com/tiagorkrebs/http-benchmark.git
$ cd http-benchmark
$ virtualenv -p python3 venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Run locust
```console
$ locust --host=<insert your host here> -f locusfile.py

# example
$ locust --host=http://edg-bha-ovh001s:80 -f locusfile.py

Starting web monitor at http://*:8089
Starting Locust 0.13.5
```

Go to http://localhost:8089 and start the requests.

If you need a different behaviour make your own `locusfile.py`.
