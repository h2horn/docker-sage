docker-sage
===========

Dockerfile for [sagemath](http://sagemath.org/).

Starts as default the notebook web environment.

Run
---

First time run in interactive mode to enter default admin password and hostname.

	docker run -i -t -p 443:8080 --name sage cornu/sage

After that start container.

	docker start sage

