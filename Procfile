web:  locust --master --locustfile locustrunner.py  --host=http://206.189.52.11:5005 --port=$PORT
worker: locust --locustfile locustrunner.py  --slave  --port=$PORT --master-host=locusttestbot.herokuapp.com