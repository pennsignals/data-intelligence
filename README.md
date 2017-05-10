| Name           | Title                 |
|----------------|-----------------------|
| Jason Walsh    | Data Engineer         |
| Michael Becker | Senior Data Scientist |

Penn Signals is an award-winning (https://goo.gl/MHqwVv) microservices software platform for processing real-time clinical data from a variety of systems. This talk demonstrates how the data science team at Penn Medicine has combined open source technologies that allow data scientists and researchers to create and use predictive applications to support improvements in health care.

### Intro (5 mins)

- Who we are (2.5 mins)
- Penn Signals (2.5 mins)

### Problem (10 mins)

- Healthcare data standards or lack thereof
 - HL7
 - Clinical database solutions
 - "RESTful" APIs `/s`
- Various types of healthcare data issues
 - Timestamps, latency, time zones (data from the future!)
 - Pipeline availability (where's my freakin' data?)
 - Patient identifier inconsistency (80-year-old newborns?!)
 - Multiple fields referring to the same types of data (heart rate, pulse, etc.)
 - AND MORE!
- Delivering products to clinicians
 - Security
 - Ease of use
 - Integrating with the Electronic Medical Record (EMR)
 - Providing actionable insights

### Solution (10 mins)

- Open source software (5 mins):
 - [Docker](https://www.docker.com/)
 - [ZeroMQ](http://zeromq.org/)
 - [Consul](https://www.consul.io/)
 - [Vault](https://www.vaultproject.io/)
 - [Jupyter](http://jupyter.org/)
 - [PySpark](https://spark.apache.org/docs/0.9.0/python-programming-guide.html)
- Putting it all together (5 mins)

### Demo (5 mins)

- Demonstrate ingesting data from a remote source and serializing it into Apache Avro format (2.5 mins)
- Using pyspark with Jupyter Notebook to query serialized data (2.5 mins)

### Q & A

| [![Jason Walsh](https://avatars3.githubusercontent.com/u/2184329?v=3&s=460)](#)                                                                                                        | [![Michael Becker](https://avatars0.githubusercontent.com/u/1069047?v=3&s=460)](#)                                                                                                                                             |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A Data Engineer working on the Predictive Healthcare team at Penn Medicine. His interests include microservices architecture, automation, and the Python and Go programming languages. | A Senior Data Scientist at Penn Medicine where he is building machine learning systems to improve patient outcomes. Michael organizes the DataPhilly Meetup group, and regularly presents at community events and conferences. |
| [Jason Walsh](https://github.com/rightlag)                                                                                                                                             | [Michael Becker](http://beckerfuffle.com/)                                                                                                                                                                                     |
