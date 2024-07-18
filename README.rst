Network Pipeline Datasets
=========================

This repository holds csv datasets from captured network traffic during ZAP scans on web applications. I hope these datasets can help you build, train and tune defensive machine learning models to defend your applications.

I generated these datasets with the `Network Pipeline`_ capture framework. With the capture framework running, I ran `ZAP simulations`_ that scanned targeted web applications.

.. image:: https://www.owasp.org/images/1/11/Zap128x128.png
    :align: center

.. _Network Pipeline: https://github.com/jay-johnson/network-pipeline
.. _ZAP simulations: https://github.com/jay-johnson/network-pipeline/tree/master/simulations#network-traffic-simulations

Captured datasets from application servers running on an Ubuntu 17.10 vm:
    
Python
------

- `Flask RESTplus example`_
- `Django 2.0`_ 

.. _Flask RESTplus example: https://github.com/frol/flask-restplus-server-example
.. _Django 2.0: https://github.com/jay-johnson/network-pipeline/tree/master/simulations#django-2.0

Node.js
-------

- `React + Redux example`_
- `Vue example`_

.. _React + Redux example: https://github.com/cornflourblue/react-redux-registration-login-example
.. _Vue example: https://github.com/petervmeijgaard/vue-2-boilerplate

Java
----

- `Spring Pet Clinic example in docker`_

.. _Spring Pet Clinic example in docker: https://github.com/anthonydahanne/terracotta-oss-docker
