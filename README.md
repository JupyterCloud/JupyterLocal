# JupyterLocal

Jupyter Notebooks are becoming integral part of software development life cycle and being used by Developers, Data Scientists, Data Engineers, Data cleaners and more. Jupyter Notebooks, and Dockers can be used together to do interactive computing along with preserving reproducible computing environments.(JuptyerHub, BinderHub and Jupyter Docker Stacks are few of the open source projects that are trying to achieve the above goals). Still there are few shortcomings in the existing opensource projects. This project tries to overcome those shortcomings. 

As a developer, it would be good to have the following features available in Jupyter Notebooks through a Web application or local application(which can be migrated easily to web application later once local testing passes).

- Reusable recipes from which anyone can launch a Jupyter environment where all dependencies are already readily installed(using dockers). [Docker Stacks](https://github.com/jupyter/docker-stacks) is such a project but it provides only support for popular languages(Python notebook, R notebook, etc.) or popular frameworks(Tensorflow notebook, PySpark notebook). Some examples are as following
  - Support for other languages like C#, C++, Java.
  - Jupyter Notebook with support for processing JSON, XML, Parquet files along with support for MySQL database or other SQL Systems. As Jupyter Notebooks are extensively used in Data Analytics environment, this will be very useful.
  - Support with Airflow or similar workflow management system with natively 

- Ability to schedule Jupyter notebooks. Some of the developers I knew had a practice of developing the entire logic in Jupyter notebooks and then copy that code into separate Python scripts/Scala code. Most of the times that code is scheduled for generating reports/outputs. So scheduling feature will be great to have. Also scheduling will allow the developer to push the heavy computing work to a remote machine, and run mutliple experiments with different parameters.

- Ability to share the Jupyter notebook with anyone. Developing software becomes increasingly collaborative in nature. If people are easily able to share the Jupyter notebooks along with other project files like Dockerfile, then people can instantly clone/modify/run those projects locally.

