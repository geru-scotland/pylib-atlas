<div align="center">
  <h1>Pylib Atlas</h1>
</div>
<div align="center">
  <img src="images/py-atlas.png" width="400" alt="PyAtlas">
</div>

## Welcome to my Python toolbox!

This repository is dedicated to organizing and documenting useful Python programming tools and libraries across various categories, as well as other noteworthy resources. It is still a work in progress. 


Initially, this list started as a personal collection—a way for me to keep track of references and tools that I found invaluable in my coding journey. As the list grew and evolved, I decided to make it public with help from ChatGPT in hopes that it could serve as a resource for other developers. 

Whether you're a seasoned developer or just starting out, I hope you find this repository useful. 

As I continue to discover and learn about new tools and libraries, I plan to extend this list, making it an ever-growing resource for the programming community.


## Table of Contents

- [Web Frameworks](#-web-frameworks)
- [Machine Learning and AI](#-machine-learning-and-ai)
- [Data Science and analysis](#-data-science-and-analysis)
- [Image processing and computer vision](#%EF%B8%8F-image-processing-and-computer-vision)
- [Networking and communication](#-networking-and-communication)
- [GUI Development](#%EF%B8%8F-gui-development)
- [Database and ORM](#%EF%B8%8F-database-and-orm)
- [Security and authentication](#-security-and-authentication)
- [Data Parsing and serialization](#-data-parsing-and-serialization)
- [Testing and QA](#-testing-and-qa)
- [Async and concurrency](#-async-and-concurrency)
- [Cryptography and hashing](#-cryptography-and-hashing)
- [CLI Utilities](#%EF%B8%8F-cli-utilities)
- [Web scraping](#%EF%B8%8F-web-scraping)
- [Caching and in-memory databases](#-caching-and-in-memory-databases)
- [Code quality and linters](#-code-quality-and-linters)
- [File and data manipulation](#-file-and-data-manipulation)
- [Environment and configuration management](#-environment-and-configuration-canagement)
- [Game development](#-game-development)
- [Framework extensions and plugins](#%EF%B8%8F-framework-extensions-and-plugins)
- [Databases and time-series data](#%EF%B8%8F-databases-and-time-series-data) 
- [Stream processing](#-stream-processing) 
- [Documentation tools](#-documentation-tools)
- [Cloud, infraestructure, DevOps and deployment](#%EF%B8%8F-cloud-and-infrastructure--devops-and-ci-cd) 



---

## 🌐 Web Frameworks

| Library      | Description                                                                                                                                                                                                 | Stars    | GitHub                                           |
|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|--------------------------------------------------|
| **Flask**    | A lightweight WSGI web application framework in Python, designed for quick and easy web development.                                                                                                        | ⭐`66k`   | [Flask](https://github.com/pallets/flask)        |
| **Django**   | A high-level Python web framework that encourages rapid development and clean, pragmatic design.                                                                                                            | ⭐`76.2k` | [Django](https://github.com/django/django)       |
| **Pyramid**  | A lightweight Python web framework aimed at taking small web apps into big web apps. It is known for its flexibility and fine-grained control.                                                              | ⭐`3.9k`  | [Pyramid](https://github.com/Pylons/pyramid)     |
| **Tornado**  | A Python web framework and asynchronous networking library, originally developed at FriendFeed. It is designed to handle asynchrony, enabling the development of real-time web applications.                | ⭐`21.5k` | [Tornado](https://github.com/tornadoweb/tornado) |
| **FastAPI**  | A modern, fast (high-performance) web framework for building APIs with Python 3.7+ based on standard Python type hints, offering automatic Swagger UI documentation.                                        | ⭐`69.4k` | [FastApi](https://github.com/tiangolo/fastapi)   |
| **Bottle**   | A fast, simple, and lightweight WSGI micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the Python Standard Library.                              | ⭐`8.3k`  | [Bottle](https://github.com/bottlepy/bottle)     |
| **CherryPy** | A minimalist Python web framework, making it easy to build web applications much like you would build any other object-oriented Python program. This results in smaller source code developed in less time. | ⭐`1.8k`  | [CherryPy](https://github.com/cherrypy/cherrypy) |


---

## 🤖 Machine Learning and AI

| Library                       | Description                                                                                                                                                                                                                                                                                                                                           | Stars    | GitHub                                                                   |
|-------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|--------------------------------------------------------------------------|
| **TensorFlow**                | An end-to-end open source platform for machine learning that enables researchers and developers to easily build and deploy ML powered applications.                                                                                                                                                                                                   | ⭐`181k`  | [TensorFlow](https://github.com/tensorflow/tensorflow)                   |
| **PyTorch**                   | An open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing.                                                                                                                                                                                                    | ⭐`76.7k` | [PyTorch](https://github.com/pytorch/pytorch)                            |
| **Scikit-learn**              | A free software machine learning library for the Python programming language. It features various classification, regression, and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy. | ⭐`57.7k` | [Scikit-learn](https://github.com/scikit-learn/scikit-learn)             |
| **Keras**                     | An open-source software library that provides a Python interface for artificial neural networks. Keras acts as an interface for the TensorFlow library.                                                                                                                                                                                               | ⭐`60.7k` | [Keras](https://github.com/keras-team/keras)                             |
| **XGBoost**                   | A scalable, portable and distributed gradient boosting library, designed to efficiently perform the gradient boosting decision tree algorithm, popular for structured or tabular data.                                                                                                                                                                | ⭐`25.4k` | [XGBoost](https://github.com/dmlc/xgboost)                               |
| **LightGBM**                  | A gradient boosting framework that uses tree-based learning algorithms. It is designed for distributed and efficient training, particularly for high-dimensional data.                                                                                                                                                                                | ⭐`15.9k` | [LightGBM](https://github.com/microsoft/LightGBM)                        |
| **CatBoost**                  | An open-source gradient boosting on decision trees library with categorical feature support out of the box, for machine learning. It yields state-of-the-art results without extensive data training typically required by other machine learning methods.                                                                                            | ⭐`7.7k`  | [CatBoost](https://github.com/catboost/catboost)                         |
| **spaCy**                     | An open-source library for advanced Natural Language Processing (NLP) in Python. It's designed specifically for production use and helps you build applications that process and "understand" large volumes of text.                                                                                                                                  | ⭐`28.5k` | [spaCy](https://github.com/explosion/spaCy)                              |
| **NLTK**                      | A leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries.                                                                                                                       | ⭐`12.9k` | [NLTK](https://github.com/nltk/nltk)                                     |
| **Hugging Face Transformers** | A library for natural language processing (NLP) that provides thousands of pre-trained models to perform tasks on texts such as classification, information extraction, question answering, and more, implemented in TensorFlow and PyTorch.                                                                                                          | ⭐`122k`  | [Hugging Face Transformers](https://github.com/huggingface/transformers) |


---

## 📊 Data Science and analysis

| Library        | Description                                                                                                                                                                                                                                                                        | Stars    | GitHub                                                 |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|--------------------------------------------------------|
| **Pandas**     | An open source data analysis and manipulation tool, built on top of the Python programming language.                                                                                                                                                                               | ⭐`41.6k` | [Pandas](https://github.com/pandas-dev/pandas)         |
| **NumPy**      | A fundamental package for scientific computing with Python, providing support for large, multi-dimensional arrays and matrices.                                                                                                                                                    | ⭐`26.1k` | [NumPy](https://github.com/numpy/numpy)                |
| **Matplotlib** | A plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications.                                                                                                    | ⭐`19k`   | [Matplotlib](https://github.com/matplotlib/matplotlib) |
| **SciPy**      | An open-source Python library used for scientific computing and technical computing. It builds on NumPy and provides a large number of higher-level functions that operate on numpy arrays and are useful for different types of scientific and engineering applications.          | ⭐`12.3k` | [SciPy](https://github.com/scipy/scipy)                |
| **Seaborn**    | A Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.                                                                                                                           | ⭐`11.8k` | [Seaborn](https://github.com/mwaskom/seaborn)          |
| **Plotly**     | An open-source graphing library that makes interactive, publication-quality graphs online. Offers over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases.                                                 | ⭐`15k`   | [Plotly](https://github.com/plotly/plotly.py)          |
| **Bokeh**      | A Python interactive visualization library that targets modern web browsers for presentation. Its goal is to provide elegant, concise construction of versatile graphics, and to extend this capability with high-performance interactivity over very large or streaming datasets. | ⭐`18.7k` | [Bokeh](https://github.com/bokeh/bokeh)                |
| **Dask**       | An open-source library for parallel computing written in Python. Designed to scale from a single computer to a cluster, Dask provides advanced parallelism for analytics, enabling performance at scale for the tools you love.                                                    | ⭐`11.9k` | [Dask](https://github.com/dask/dask)                   |

---

---

## 🖼️ Image processing and computer vision

| Tool             | Description                                                                                                                                                                                                                                  | Stars    | GitHub                                                       |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|--------------------------------------------------------------|
| **OpenCV**       | A robust library offering open-source computer vision and machine learning software. Designed to provide a common infrastructure for computer vision applications, OpenCV accelerates the use of machine perception in the commercial realm. | ⭐`78.4k` | [OpenCV](https://github.com/opencv/opencv)                   |
| **scikit-image** | Part of the SciPy ecosystem, this library presents a rich collection of image processing algorithms accessible in Python. It's aimed at researchers, educators, and industry professionals alike.                                            | ⭐`5.8k`  | [scikit-image](https://github.com/scikit-image/scikit-image) |
| **SimpleCV**     | Offering a straightforward framework for building computer vision applications, SimpleCV simplifies image acquisition, processing, and analysis through a consistent Python interface.                                                       | ⭐`2.7k`  | [SimpleCV](https://github.com/sightmachine/SimpleCV)         |
| **Mahotas**      | This library serves as a comprehensive toolkit for computer vision and image processing in Python, featuring numerous algorithms for segmentation, feature extraction, and more.                                                             | ⭐`824`   | [Mahotas](https://github.com/luispedro/mahotas)              |

---

## 🛜 Networking and communication

| Library              | Description                                                                                                                                                                                                | Stars    | GitHub                                                                   |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|--------------------------------------------------------------------------|
| **Requests**         | A simple, yet elegant HTTP library for Python, built for human beings.                                                                                                                                     | ⭐`51.2k` | [Requests](https://github.com/psf/requests)                              |
| **aiohttp**          | An asynchronous HTTP client/server framework for asyncio and Python.                                                                                                                                       | ⭐`14.5k` | [aiohttp](https://github.com/aio-libs/aiohttp)                           |
| **HTTPx**            | A fully featured HTTP client for Python 3, which provides synchronous and asynchronous APIs, and support for HTTP/2.                                                                                       | ⭐`6.6k`  | [HTTPx](https://github.com/projectdiscovery/httpx)                       |
| **urllib3**          | A powerful, user-friendly HTTP client for Python. Much of the Python ecosystem uses urllib3 and makes HTTP requests. It brings many critical features that are missing from the Python standard libraries. | ⭐`3.6k`  | [urllib3](https://github.com/urllib3/urllib3)                            |
| **gRPC**             | A high performance, open-source universal RPC framework that uses HTTP/2 as transport protocol, enabling client and server applications to communicate transparently and build connected systems.          | ⭐`40.4k` | [gRPC](https://github.com/grpc/grpc)                                     |
| **WebSocket-client** | A WebSocket client for Python with a focus on correctness and simplicity, providing easy access to WebSocket services.                                                                                     | ⭐`3.4k`  | [WebSocket-client](https://github.com/websocket-client/websocket-client) |
| **Paramiko**         | A Python implementation of the SSHv2 protocol, providing both client and server functionality. It allows for easy SSH connections to remote servers.                                                       | ⭐`8.8k`  | [Paramiko](https://github.com/paramiko/paramiko)                         |
| **Netmiko**          | A multi-vendor library to simplify Paramiko SSH connections to network devices. It's used extensively in network automation scripts.                                                                       | ⭐`3.4k`  | [Netmiko](https://github.com/ktbyers/netmiko)                            |
| **Scapy**            | A powerful Python program that enables the user to send, sniff, dissect and forge network packets. This capability allows for a wide range of networking tasks.                                            | ⭐`9.9k`  | [Scapy](https://github.com/secdev/scapy)                                 |
| **Twisted**          | An event-driven networking engine written in Python. Twisted runs on Python 2 and 3, and provides modules to deal with various protocols.                                                                  | ⭐`5.4k`  | [Twisted](https://github.com/twisted/twisted)                            |


---

## 🖥️ GUI Development

| Library           | Description                                                                                                                                                                          | Official Link                                                           |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **Tkinter**       | The standard GUI toolkit for Python, providing a powerful object-oriented interface to the Tk GUI toolkit.                                                                           | [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html) |
| **ttkbootstrap**  | A modern and themeable GUI library for Tkinter. ttkbootstrap extends Tkinter with a collection of widgets styled using Bootstrap themes for beautiful and responsive applications.   | [ttkbootstrap](https://ttkbootstrap.readthedocs.io/en/latest/)          |
| **customTkinter** | An extension to Tkinter that provides custom widgets with advanced styling capabilities and a more modern look, improving the visual appearance and user experience of applications. | [customTkinter](https://github.com/TomSchimansky/CustomTkinter)         |
| **PyQt**          | A set of Python bindings for The Qt Company’s Qt application framework, used for developing GUI applications.                                                                        | [PyQt](https://riverbankcomputing.com/software/pyqt/intro)              |
| **Kivy**          | An open-source Python library for developing multitouch application software with a natural user interface (NUI).                                                                    | [Kivy](https://kivy.org/)                                               |
| **wxPython**      | A cross-platform GUI toolkit for the Python language, allowing Python programmers to create programs with a robust, highly functional graphical user interface, simply and easily.   | [wxPython](https://www.wxpython.org/)                                   |
| **PyGTK**         | A set of Python wrappers for the GTK graphical user interface library, facilitating the creation of graphical interfaces in Python.                                                  | [PyGTK](https://pygtk.org/)                                             |
| **PySide**        | The official set of Python bindings for the Qt Company’s Qt application framework, similar to PyQt but under a more liberal license.                                                 | [PySide](https://www.qt.io/qt-for-python)                               |
| **Dear PyGui**    | A simple to use (but powerful) Python GUI framework. DPG is a GPU Accelerated Python GUI framework for making quick, but advanced GUI applications.                                  | [Dear PyGui](https://github.com/hoffstadt/DearPyGui)                    | |

---

## 🗃️ Database and ORM

| Library                   | Description                                                                                                                                                                            | Official Link                                                         |
|---------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| **SQLAlchemy**            | A SQL toolkit and Object-Relational Mapping (ORM) library for Python that provides a full suite of well known enterprise-level persistence patterns.                                   | [SQLAlchemy](https://www.sqlalchemy.org/)                             |
| **Django ORM**            | Django's Object-Relational Mapper; a powerful tool for bridging the gap between the high-level Python code and the low-level database query.                                           | [Django ORM](https://docs.djangoproject.com/en/3.0/topics/db/models/) |
| **Peewee**                | A small, expressive ORM that provides a simple and intuitive way to interact with databases using Python.                                                                              | [Peewee](http://docs.peewee-orm.com/en/latest/)                       |
| **SQLObject**             | A popular ORM that provides an object-oriented interface to your database, with tables as classes, rows as instances, and columns as attributes.                                       | [SQLObject](http://sqlobject.org/)                                    |
| **Tortoise ORM**          | An easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django, designed for use with asyncio and Python.                                                                    | [Tortoise ORM](https://tortoise.github.io)                            |
| **Pony ORM**              | A Python ORM that provides a generator-based interface to write queries. It translates Python functions into SQL syntax and is designed for ease of use.                               | [Pony ORM](https://ponyorm.org/)                                      |
| **MongoEngine**           | A Document-Object Mapper for working with MongoDB from Python. It uses a simple declarative API, similar to the Django ORM.                                                            | [MongoEngine](http://mongoengine.org/)                                |
| **Django REST Framework** | A powerful and flexible toolkit for building Web APIs on top of Django, including ORM capabilities for working with databases through RESTful APIs.                                    | [Django REST Framework](https://www.django-rest-framework.org/)       |
| **Alembic**               | A lightweight database migration tool for use with SQLAlchemy. It allows for version control for database schemas, enabling fine-grained and database-independent migration scripting. | [Alembic](https://alembic.sqlalchemy.org/en/latest/)                  |


---

## 🔒 Security and authentication

| Library                | Description                                                                                                                              | Official Link                                                              |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| **OAuthLib**           | A generic, spec-compliant, thorough implementation of the OAuth request-signing logic for Python.                                        | [OAuthLib](https://oauthlib.readthedocs.io/en/latest/)                     |
| **PyJWT**              | A Python library which allows you to encode and decode JSON Web Tokens (JWT).                                                            | [PyJWT](https://pyjwt.readthedocs.io/en/latest/)                           |
| **Authlib**            | A comprehensive, ready-to-use library for OAuth 1, OAuth 2, OpenID clients, JWT, and other authentication protocols.                     | [Authlib](https://authlib.org/)                                            |
| **python-social-auth** | A social authentication/registration mechanism with support for several frameworks and auth providers.                                   | [python-social-auth](https://python-social-auth.readthedocs.io/en/latest/) |
| **Passlib**            | A password hashing library for Python, providing over 30 schemes and a simple framework for managing existing password hashes.           | [Passlib](https://passlib.readthedocs.io/en/stable/)                       |
| **Paramiko**           | A module for Python 2.7/3.4+ that implements the SSHv2 protocol for secure (encrypted and authenticated) connections to remote machines. | [Paramiko](http://www.paramiko.org/)                                       |



---

## 📜 Data parsing and serialization

| Library            | Description                                                                                                                                                                         | Official Link                                                                      |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| **Beautiful Soup** | A library that makes it easy to scrape information from web pages, providing Pythonic idioms for iterating, searching, and modifying the parse tree.                                | [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)                   |
| **lxml**           | A powerful and Pythonic XML processing library combining libxml2/libxslt with the ElementTree API.                                                                                  | [lxml](https://lxml.de/)                                                           |
| **json**           | The built-in JSON library in Python for encoding and decoding JSON data.                                                                                                            | [json - Python Documentation](https://docs.python.org/3/library/json.html)         |
| **Pandas**         | While primarily a data analysis library, Pandas offers robust IO tools for reading and writing data in various formats, including CSV, Excel, JSON, HTML, and SQL databases.        | [Pandas IO Tools](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html) |
| **PyYAML**         | A YAML parser and emitter for Python, allowing for the serialization and deserialization of complex data structures to and from YAML, a human-friendly data serialization standard. | [PyYAML](https://pyyaml.org/)                                                      |
| **Marshmallow**    | An ORM/ODM/framework-agnostic library for converting complex data types, such as objects, to and from native Python datatypes.                                                      | [Marshmallow](https://marshmallow.readthedocs.io/en/stable/)                       |
| **Protobuf**       | Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data, similar to XML but smaller, faster, and simpler.                                 | [Protobuf](https://developers.google.com/protocol-buffers)                         |
| **pickle**         | The built-in Python library for serializing and deserializing Python object structures, turning Python objects into byte streams and vice versa.                                    | [pickle - Python Documentation](https://docs.python.org/3/library/pickle.html)     |

---

## 🧪 Testing and QA

| Library             | Description                                                                                                                                                                     | Official Link                                                                      |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| **pytest**          | A framework that makes it easy to write small tests, yet scales to support complex functional testing for applications and libraries.                                           | [pytest](https://pytest.org/)                                                      |
| **Selenium**        | A portable framework for testing web applications, providing a playback tool for authoring functional tests.                                                                    | [Selenium](https://www.selenium.dev/)                                              |
| **unittest**        | The built-in Python framework for writing and running tests, based on the xUnit pattern.                                                                                        | [unittest - Python Documentation](https://docs.python.org/3/library/unittest.html) |
| **nose2**           | The successor to nose, extends unittest to make testing easier. It's less popular now due to pytest's rise, but it's still a powerful tool.                                     | [nose2](https://docs.nose2.io/en/latest/)                                          |
| **Robot Framework** | A generic open source automation framework for acceptance testing, acceptance test-driven development (ATDD), and robotic process automation (RPA).                             | [Robot Framework](https://robotframework.org/)                                     |
| **Locust**          | An easy-to-use, distributed user load testing tool. It's intended for load testing web sites (or other systems) and figuring out how many concurrent users a system can handle. | [Locust](https://locust.io/)                                                       |
| **Tox**             | A generic virtualenv management and test command-line tool you can use for checking your package installs correctly with different Python versions and interpreters.            | [Tox](https://tox.readthedocs.io/en/latest/)                                       |
| **Hypothesis**      | A powerful, flexible, and easy-to-use library for property-based testing. It lets you write tests that are parameterized by a source of examples.                               | [Hypothesis](https://hypothesis.works/)                                            |
| **Behave**          | For behavior-driven development (BDD), Behave uses tests written in a natural language style, backed up by Python code.                                                         | [Behave](https://behave.readthedocs.io/en/stable/)                                 |

---

## ⚡ Async and concurrency

| Library                | Description                                                                                                                                               | Official Link                                                                   |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| **asyncio**            | The asyncio library is used to write concurrent code using the async/await syntax in Python.                                                              | [asyncio](https://docs.python.org/3/library/asyncio.html)                       |
| **gevent**             | A coroutine-based Python networking library that uses greenlet to provide a high-level synchronous API on top of the libev or libuv event loop.           | [gevent](http://www.gevent.org/)                                                |
| **concurrent.futures** | A high-level interface for asynchronously executing callables. It provides a framework for asynchronously executing functions using threads or processes. | [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) |
| **Twisted**            | An event-driven networking engine written in Python, which can be used for asynchronous programming.                                                      | [Twisted](https://twistedmatrix.com/trac/)                                      |
| **Tornado**            | A Python web framework and asynchronous networking library that can handle thousands of connections at the same time.                                     | [Tornado](https://www.tornadoweb.org/en/stable/)                                |
| **Celery**             | An asynchronous task queue/job queue based on distributed message passing. It is focused on real-time operation, but supports scheduling as well.         | [Celery](http://www.celeryproject.org/)                                         |

---

## 🔐 Cryptography and hashing

| Library              | Description                                                                                                                                                                                          | Official Link                                             |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| **cryptography**     | A package designed to expose cryptographic primitives and recipes to Python developers, offering both high-level recipes and low-level interfaces to common cryptographic algorithms.                | [cryptography](https://cryptography.io/en/latest/)        |
| **hashlib**          | A module that implements a common interface to many secure hash and message digest algorithms, including SHA1, SHA224, SHA256, SHA384, SHA512, and MD5.                                              | [hashlib](https://docs.python.org/3/library/hashlib.html) |
| **PyCryptodome**     | A self-contained Python package of low-level cryptographic primitives. It is a fork of PyCrypto that has been enhanced and is actively maintained, designed to replace PyCrypto.                     | [PyCryptodome](https://www.pycryptodome.org/)             |
| **Paramiko**         | While known for its SSH2 protocol support, Paramiko also includes cryptographic functions and utilities as part of its core.                                                                         | [Paramiko](http://www.paramiko.org/)                      |
| **NaCl (libsodium)** | A high-level cryptographic library that makes it easy to encrypt, decrypt, sign, and verify signatures without needing to manage nonces, keys, or other cryptographic details.                       | [NaCl (PyNaCl)](https://pynacl.readthedocs.io/en/latest/) |
| **OpenSSL**          | A robust, full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols. The `pyOpenSSL` library is a thin wrapper around (a subset of) the OpenSSL library. | [pyOpenSSL](https://www.pyopenssl.org/en/stable/)         |


## ⌨️ CLI Utilities

| Library      | Description                                                                                                                                                                                        | Official Link                                               |
|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Click**    | A Python package for creating beautiful command line interfaces in a composable way with as little code as necessary.                                                                              | [Click](https://click.palletsprojects.com/)                 |
| **argparse** | The argparse module makes it easy to write user-friendly command-line interfaces. The program defines what arguments it requires, and argparse will figure out how to parse those out of sys.argv. | [argparse](https://docs.python.org/3/library/argparse.html) |
| **Typer**    | A library for building CLI applications that users will love using and developers will love creating. Based on Python 3.6+ type hints.                                                             | [Typer](https://typer.tiangolo.com/)                        |
| **Docopt**   | Helps you define your command-line interfaces by parsing the help message that your program prints to the user.                                                                                    | [Docopt](http://docopt.org/)                                |
| **Fire**     | A library for automatically generating command line interfaces (CLIs) with a single line of code. It turns any Python module, class, or object into a CLI.                                         | [Fire](https://github.com/google/python-fire)               |
| **Plumbum**  | Plumbum: Shell Combinators and More. It offers local and remote command execution, including command piping, file and path manipulation, and more, aiming for a more Pythonic interface.           | [Plumbum](https://plumbum.readthedocs.io/en/latest/)        |
| **Rich**     | Although not exclusively a CLI library, Rich can be used to enhance the visual appeal of command line applications with rich text and beautiful formatting.                                        | [Rich](https://rich.readthedocs.io/en/latest/)              |

---

## 🕸️ Web Scraping

| Library                   | Description                                                                                                                                                                                                    | Official Link                                                      |
|---------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| **Scrapy**                | An open source and collaborative framework for extracting the data you need from websites in a fast, simple, yet extensible way.                                                                               | [Scrapy](https://scrapy.org/)                                      |
| **Beautiful Soup**        | A library for pulling data out of HTML and XML files. It provides idiomatic ways of navigating, searching, and modifying the parse tree.                                                                       | [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)   |
| **lxml**                  | While also a powerful XML and HTML processing library, lxml's speed and ease of use make it great for web scraping.                                                                                            | [lxml](https://lxml.de/)                                           |
| **Requests-HTML**         | An HTML parsing library designed to simplify the process of making requests and parsing HTML documents. It integrates functionality from requests and pyquery/pyppeteer for a comprehensive scraping solution. | [Requests-HTML](https://html.python-requests.org/)                 |
| **Selenium**              | Although primarily a tool for testing web applications, Selenium can be used for scraping dynamic content that other tools can't handle as it allows for rendering JavaScript.                                 | [Selenium](https://www.selenium.dev/)                              |
| **MechanicalSoup**        | A Python library for automating interaction with websites. It combines the Requests library and BeautifulSoup to simulate a browser without a graphical interface.                                             | [MechanicalSoup](https://mechanicalsoup.readthedocs.io/en/stable/) |
| **Puppeteer** (Pyppeteer) | A library for controlling headless Chrome or Chromium over the DevTools Protocol. Pyppeteer is the Python version, perfect for tasks requiring JavaScript rendering.                                           | [Pyppeteer](https://github.com/pyppeteer/pyppeteer)                |

---
## 💾 Caching and in-memory databases

| Library        | Description                                                                                                                                                                                                                                                                                 | Official Link                                          |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| **Memcached**  | A high-performance, distributed memory object caching system, intended for use in speeding up dynamic web applications by alleviating database load.                                                                                                                                        | [Memcached](https://memcached.org/)                    |
| **Redis**      | An open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker. It supports data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes with radius queries, and streams. | [Redis](https://redis.io/)                             |
| **pylibmc**    | A Python wrapper around the libmemcached interface, which is a client library for Memcached written in C. It's a fast and efficient way to interface with Memcached from Python.                                                                                                            | [pylibmc](https://pypi.org/project/pylibmc/)           |
| **diskcache**  | Python disk-backed cache (Django-compatible). Faster than Redis and Memcached. Pure Python.                                                                                                                                                                                                 | [diskcache](http://www.grantjenks.com/docs/diskcache/) |
| **beaker**     | A library for caching and sessions for use with web applications and stand-alone Python scripts and applications.                                                                                                                                                                           | [beaker](https://beaker.readthedocs.io/en/latest/)     |
| **hiredis**    | A minimalistic C client library for the Redis database. `hiredis-py` is a Python wrapper for the `hiredis` C library. It provides a way to communicate with Redis directly from Python, using the C client for speed.                                                                       | [hiredis-py](https://pypi.org/project/hiredis/)        |
| **aioredis**   | Asyncio (PEP 3156) Redis client library. It provides an async interface to Redis, built on top of `hiredis` and compatible with asyncio.                                                                                                                                                    | [aioredis](https://aioredis.readthedocs.io/)           |
| **pymemcache** | A comprehensive, fast, pure-Python memcached client.                                                                                                                                                                                                                                        | [pymemcache](https://pypi.org/project/pymemcache/)     |

---

## 🔍 Code quality and linters

| Tool       | Description                                                                                                                                            | Official Link                                    |
|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| **Flake8** | A python tool that glues together `pyflakes`, `pycodestyle`, and `mccabe` scripts to check the quality of Python code.                                 | [Flake8](https://flake8.pycqa.org/en/latest/)    |
| **Black**  | The uncompromising Python code formatter. By using it, you delegate the responsibility of code formatting to Black, keeping the code style consistent. | [Black](https://black.readthedocs.io/en/stable/) |
| **isort**  | A Python utility / library to sort imports alphabetically and automatically separate them into sections and by type.                                   | [isort](https://pycqa.github.io/isort/)          |
| **Pylint** | A tool that checks for errors in Python code, tries to enforce a coding standard, and looks for code smells.                                           | [Pylint](https://www.pylint.org/)                |
| **Mypy**   | An optional static type checker for Python, aiming to combine the benefits of dynamic (or "duck") typing and static typing.                            | [Mypy](http://mypy-lang.org/)                    |

---

## 📂 File and data manipulation

| Library       | Description                                                                                                                                                                                                                             | Official Link                                                                                   |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| **Pillow**    | The Python Imaging Library adds image processing capabilities to your Python interpreter. This library provides extensive file format support, an efficient internal representation, and fairly powerful image processing capabilities. | [Pillow](https://python-pillow.org/)                                                            |
| **CSV**       | A module that implements classes to read and write tabular data in CSV format. It allows programmers to write and read data in a format preferred by Excel, without knowing the precise details of the CSV format.                      | [CSV Documentation](https://docs.python.org/3/library/csv.html)                                 |
| **openpyxl**  | A Python library to read/write Excel 2010 xlsx/xlsm/xltx/xltm files.                                                                                                                                                                    | [openpyxl](https://openpyxl.readthedocs.io/en/stable/)                                          |
| **Pandas**    | Offers powerful data manipulation and analysis via its DataFrame object. It can read and write data in various formats, including CSV, Excel, JSON, HTML, and SQL databases.                                                            | [Pandas](https://pandas.pydata.org/)                                                            |
| **json**      | The built-in JSON library for Python. It can parse JSON from strings or files and can convert dictionaries into JSON strings.                                                                                                           | [json](https://docs.python.org/3/library/json.html)                                             |
| **PyPDF2**    | A library capable of splitting, merging together, cropping, and transforming the pages of PDF files.                                                                                                                                    | [PyPDF2](https://pypdf2.readthedocs.io/en/latest/)                                              |
| **xlrd/xlwt** | Libraries for reading data and formatting information from Excel files in the historic .xls format.                                                                                                                                     | [xlrd](https://xlrd.readthedocs.io/en/latest/) / [xlwt](https://xlwt.readthedocs.io/en/latest/) |

---

## 🌍 Environment and configuration canagement

| Tool           | Description                                                                                                                                                                                                              | Official Link                                       |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| **dotenv**     | Loads environment variables from a `.env` file into `process.env`, making it easy to manage environment-specific configurations.                                                                                         | [dotenv](https://pypi.org/project/python-dotenv/)   |
| **virtualenv** | A tool to create isolated Python environments. It can create environments with their own installation directories, that can have different Python versions and packages installed.                                       | [virtualenv](https://virtualenv.pypa.io/en/latest/) |
| **pipenv**     | Aims to bring the best of all packaging worlds to the Python world. It automatically creates and manages a virtualenv for your projects and adds/removes packages from your `Pipfile` as you install/uninstall packages. | [pipenv](https://pipenv.pypa.io/en/latest/)         |
| **Poetry**     | A tool for dependency management and packaging in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.                                               | [Poetry](https://python-poetry.org/)                |
| **Conda**      | An open-source package management system and environment management system that runs on Windows, macOS, and Linux. Conda quickly installs, runs, and updates packages and their dependencies.                            | [Conda](https://conda.io/)                          |

---

## 🎮 Game development

| Library      | Description                                                                                                                                                                                                                                                                                | Official Link                                |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------|
| **Pygame**   | A set of Python modules designed for writing video games. It includes computer graphics and sound libraries designed to be used with the Python programming language.                                                                                                                      | [Pygame](https://www.pygame.org/)            |
| **Arcade**   | A modern Python framework for crafting games with compelling graphics and sound. Open source and easy to use, it's geared towards teaching programming concepts through game development.                                                                                                  | [Arcade](https://arcade.academy/)            |
| **Panda3D**  | An open-source, completely free-to-use engine for realtime 3D games, visualizations, simulations, experiments — you name it! Its rich feature set readily tailors to your specific workflow and development needs.                                                                         | [Panda3D](https://www.panda3d.org/)          |
| **PyOpenGL** | The most common cross platform Python binding to OpenGL and related APIs. It provides access to the OpenGL library for creating 2D and 3D graphics.                                                                                                                                        | [PyOpenGL](http://pyopengl.sourceforge.net/) |
| **Kivy**     | An open source Python library for developing multitouch applications. It's cross-platform (Linux/OS X/Windows/Android/iOS) and released under the MIT license. Though not exclusively for games, it's used widely in game development due to its extensive support for gestures and touch. | [Kivy](https://kivy.org/)                    |
| **Ren'Py**   | A visual novel engine that helps you use words, images, and sounds to tell interactive stories that run on computers and mobile devices. It's great for both beginning and professional creators, and it supports easy creation of visual novels and life simulation games.                | [Ren'Py](https://www.renpy.org/)             |

---

## 🛠️ Framework extensions and plugins

| Library                   | Description                                                                                                                                                                                                                                              | Official Link                                                            |
|---------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| **Flask-Login**           | Provides user session management for Flask. It handles the common tasks of logging in, logging out, and remembering your users' sessions over extended periods of time.                                                                                  | [Flask-Login](https://flask-login.readthedocs.io/en/latest/)             |
| **Django REST Framework** | A powerful and flexible toolkit for building Web APIs. It's a lightweight extension to Django that works well with existing apps and comes bundled with a set of serialization that can be customized and extended.                                      | [Django REST Framework](https://www.django-rest-framework.org/)          |
| **Flask-RESTful**         | An extension for Flask that adds support for quickly building REST APIs. It is a lightweight abstraction that works with your existing ORM/libraries.                                                                                                    | [Flask-RESTful](https://flask-restful.readthedocs.io/en/latest/)         |
| **Flask-SQLAlchemy**      | Adds SQLAlchemy support to Flask. It simplifies the use of SQLAlchemy with Flask by providing useful defaults and extra helpers that make it easier to accomplish common tasks.                                                                          | [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/) |
| **Django-Allauth**        | Provides authentication, registration, account management as well as 3rd party (social) account authentication.                                                                                                                                          | [Django-Allauth](https://django-allauth.readthedocs.io/en/latest/)       |
| **React Router**          | While not a Python library, React Router is a powerful routing library for React that allows the creation of single page applications with dynamic page changes without the need to reload. Useful for Django or Flask backends serving React frontends. | [React Router](https://reactrouter.com/)                                 |
| **Vue Router**            | Similar to React Router but for Vue.js. It enables the development of powerful single-page web applications. This can be useful in projects that use Python backends.                                                                                    | [Vue Router](https://router.vuejs.org/)                                  |


---

## 🗄️ Databases and time-series data

| Tool           | Description                                                                                                                                                                                                                                | Official Link                               |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------|
| **Prometheus** | An open-source system monitoring and alerting toolkit originally built at SoundCloud, now part of the Cloud Native Computing Foundation. It's focused on reliability and scalability, handling multi-dimensional data collected over time. | [Prometheus](https://prometheus.io/)        |
| **InfluxDB**   | An open-source time series database designed to handle high write and query loads. It is a component of the TICK stack.                                                                                                                    | [InfluxDB](https://www.influxdata.com/)     |
| **SQLite**     | A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine. SQLite is the most used database engine in the world.                                                            | [SQLite](https://www.sqlite.org/index.html) |
| **PostgreSQL** | A powerful, open source object-relational database system with over 30 years of active development.                                                                                                                                        | [PostgreSQL](https://www.postgresql.org/)   |
| **MongoDB**    | A general purpose, document-based, distributed database built for modern application developers and for the cloud era.                                                                                                                     | [MongoDB](https://www.mongodb.com/)         |
| **GraphQL**    | A query language for APIs and a runtime for executing those queries by using a type system you define for your data. It enables declarative data fetching, allowing clients to specify exactly what data they need.	                       | [GraphQL](https://graphql.org)              |


---

## 🌊 Stream processing

| Tool              | Description                                                                                                                                                                                                                                                       | Official Link                                          |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| **Apache Kafka**  | A distributed event streaming platform capable of handling trillions of events a day. Initially conceived as a messaging queue, Kafka is based on an abstraction of a distributed commit log.                                                                     | [Apache Kafka](https://kafka.apache.org/)              |
| **RabbitMQ**      | An open-source message-broker software that originally implemented the Advanced Message Queuing Protocol (AMQP) and has since been extended with a plug-in architecture to support Streaming Text Oriented Messaging Protocol (STOMP), MQTT, and other protocols. | [RabbitMQ](https://www.rabbitmq.com/)                  |
| **Apache Pulsar** | A cloud-native, distributed messaging and streaming platform originally created at Yahoo! It's designed to provide a highly scalable, durable, and secure event streaming platform.                                                                               | [Apache Pulsar](https://pulsar.apache.org/)            |
| **Redis Streams** | A new data type introduced in Redis 5.0, which provides a series of features that make it possible to handle streams of data directly within Redis.                                                                                                               | [Redis Streams](https://redis.io/topics/streams-intro) |

---

## 📚 Documentation tools

| Tool                      | Description                                                                                                                                                                                                                                                                                               | Official Link                                                 |
|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| **Swagger (OpenAPI)**     | A set of tools for designing, building, and documenting RESTful APIs. It offers the Swagger Editor for designing API specifications, the Swagger UI for generating interactive API documentation, and the Swagger Codegen for generating server stubs and client libraries from an OpenAPI Specification. | [Swagger](https://swagger.io/)                                |
| **Sphinx**                | A tool that makes it easy to create intelligent and beautiful documentation for Python projects (or other documents consisting of multiple reStructuredText sources), originally created for the Python documentation.                                                                                    | [Sphinx](http://www.sphinx-doc.org/)                          |
| **MkDocs**                | A fast and simple static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.                                                                                                   | [MkDocs](https://www.mkdocs.org/)                             |
| **Read the Docs**         | A documentation hosting platform that automates the process of building and deploying your Sphinx or MkDocs documentation after each commit or daily. It integrates well with Git, GitHub, Bitbucket, and similar platforms.                                                                              | [Read the Docs](https://readthedocs.org/)                     |
| **Postman Documentation** | Postman allows you to generate and host beautiful, machine-readable documentation for your APIs. It offers dynamic examples and mock servers, making API testing and sharing easier.                                                                                                                      | [Postman](https://www.postman.com/product/api-documentation/) |
| **Docusaurus**            | A project for building, deploying, and maintaining open source project websites easily. It supports Markdown, documentation versioning, and features built specifically for documentation websites.                                                                                                       | [Docusaurus](https://docusaurus.io/)                          |
| **Redoc**                 | An open-source tool that can serve as an alternative to Swagger UI. It's React-based and offers a more customizable and visually appealing way to generate interactive API documentation from OpenAPI (Swagger) Definitions.                                                                              | [Redoc](https://github.com/Redocly/redoc)                     |

---

## ☁️ Cloud and infrastructure, 🚀 DevOps and CI-CD

| Tool                 | Description                                                                                                                                                                                                          | Official Link                                                      |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| **AWS CLI**          | The Amazon Web Services command line interface is a unified tool to manage your AWS services from a terminal session on your own client.                                                                             | [AWS CLI](https://aws.amazon.com/cli/)                             |
| **Google Cloud SDK** | A set of tools that you can use to manage resources and applications hosted on Google Cloud.                                                                                                                         | [Google Cloud SDK](https://cloud.google.com/sdk)                   |
| **Azure CLI**        | Designed to make scripting easy, flexible, and powerful, it provides the same capabilities as the portal, making it an essential tool for managing Azure resources.                                                  | [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/)           |
| **Kubernetes**       | An open-source system for automating deployment, scaling, and operations of application containers across clusters of hosts.                                                                                         | [Kubernetes](https://kubernetes.io/)                               |
| **OpenShift**        | A family of containerization software developed by Red Hat. It's an open source container application platform based on the Kubernetes container orchestrator for enterprise application development and deployment. | [OpenShift](https://www.openshift.com/)                            |
| **Puppet**           | A software configuration management tool which includes its own declarative language to describe system configuration.                                                                                               | [Puppet](https://puppet.com/)                                      |
| **Docker**           | An open platform for developing, shipping, and running applications, Docker enables you to separate your applications from your infrastructure so you can deliver software quickly.                                  | [Docker](https://www.docker.com/)                                  |
| **Docker Compose**   | A tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application's services.                                                                     | [Docker Compose](https://docs.docker.com/compose/)                 |
| **Kubernetes**       | An open-source system for automating deployment, scaling, and management of containerized applications.                                                                                                              | [Kubernetes](https://kubernetes.io/)                               |
| **Ansible**          | An open-source automation tool, or platform, used for IT tasks such as configuration management, application deployment, intra-service orchestration, and provisioning.                                              | [Ansible](https://www.ansible.com/)                                |
| **Fabric**           | A high-level Python library designed to execute shell commands remotely over SSH, facilitating application deployment and system administration tasks.                                                               | [Fabric](https://www.fabfile.org/)                                 |
| **Terraform**        | An open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services. Terraform codifies cloud APIs into declarative configuration files.                | [Terraform](https://www.terraform.io/)                             |
| **GitLab CI/CD**     | A tool built into GitLab for software development through the continuous methodologies: Continuous Integration (CI), Continuous Delivery (CD), and Continuous Deployment (CD).                                       | [GitLab CI/CD](https://docs.gitlab.com/ee/ci/)                     |
| **Jenkins**          | An open-source automation server that enables developers around the world to reliably build, test, and deploy their software.                                                                                        | [Jenkins](https://www.jenkins.io/)                                 |
| **Python Jenkins**   | A Python wrapper for the Jenkins REST API which allows you to access Jenkins servers. This can be used to automate Jenkins server management, job configuration, and job execution.                                  | [Python Jenkins](https://python-jenkins.readthedocs.io/en/latest/) |
| **Minikube**         | Minikube is a tool that makes it easy to run Kubernetes locally. Minikube runs a single-node Kubernetes cluster inside a VM on your laptop for users looking to try out Kubernetes or develop with it day-to-day.    | [Minikube](https://minikube.sigs.k8s.io/docs/)                     |
| **Helm**             | The package manager for Kubernetes. Helm helps you manage Kubernetes applications — Helm Charts help you define, install, and upgrade even the most complex Kubernetes application.                                  | [Helm](https://helm.sh/)                                           |


## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this repository better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

### Steps to contribute:

1. **Fork** the Project
2. Create your **Feature Branch** (`git checkout -b feature/amazing-feature`)
3. Commit your Changes (`git commit -m 'Add some amazing-feature'`)
4. Push to the Branch (`git push origin feature/amazing-feature`)
5. Open a **Pull Request**