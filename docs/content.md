# Agenda + Previous Talks 

## Upcoming 

May 31st, 2022

**copilot-ops: Go From Zero to DevOps Hero in Under 10 Seconds**

* By Oleg Silkin
* In the age of cloud-native computing, Kubernetes has taken the world by storm, forcing many of us to spend more time on Google than we should, just to become YAML experts. This ends up being a time-consuming process, as many of the YAMLs share a similar structure with differing values based on the specifics of your deployment. 
* **copilot-ops** is a CLI tool which supercharges your DevOps capabilities by allowing the user to specify what needs to be created/changed, along with some files to provide context on what values the resulting YAML should use.
* By the end of this talk, attendees will know how to use copilot-ops to supercharge their DevOps capabilities and quickly generate or edit desired YAML files at a moment's notice. Attendees will also walk away with a basic understanding of how Generative Pre-Trained Transformer 3 (GPT-3) can be used for code-generation tasks.

## Past Events

May 17th, 2022 - **Bringing AI and Machine Learning into Operation**

* By Audrey Reznik
* As a Data Scientist it is often difficult to know where to start your project.  Do I test and build my model in an IDE?  If I build and test my model in an IDE, how do I connect to my resources such as streaming data or databases?  How can I optimize my model inference performance?  Once I have optimized my model how do I easily deploy and manage it?  Plus what options are available for me to deploy onPrem or in a Hybrid cloud environment?
* In this session we will discuss an easy way to build, test, train and deploy high performant models using a variety of platforms and tools created for OpenShift.
* The attendees will learn about what is Open Datahub, Red Hat OpenShift Data Science and Managed Services.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup12.pdf) and [Video Recording](https://youtu.be/mHa2O116RS8)

May 3rd, 2022 - **Data Obfuscation Techniques**

* By Surya Prakash Pathak
* A common scenario encountered by data scientists is sharing confidential and sensitive data with others. A lot of data we collect today can easily be linked to an individual, household, or entity. What should we do when we need to share these data with others? One of the methods to anonymize personal and confidential data is by using data obfuscation techniques. Data obfuscation is the process of replacing sensitive information with data that looks like real production information, making it useless to malicious actors.
* In this talk, we will get introduced to different hashing techniques used for data obfuscation. In addition to this, we will also go over the obfuscation technique we used for obfuscating meetup attendees' data.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup11.pdf) and [Video Recording](https://youtu.be/aj-THe9fFIQ)

April 19th, 2022 - **Distributed ML workloads on OpenShift**

* By Selbi Nuryyeva
* As the datasets and models get bigger, the demand for more powerful and efficient GPUs is rapidly increasing. Oftentimes a  single GPU is not adequate for an ML use case. An alternative to upgrading the GPU hardware is to distribute the ML workload either across several GPUs on one node, or across multiple nodes each containing one or several GPUs. The ability for the latter is especially preferred when a single machine can fit only so many GPUs. 
* In this talk, we will explore how one can distribute a machine learning workflow across several nodes with GPU hardware in a cloud environment. We will use PyTorch to carry out the ML training and Kubeflow, Node Feature Discovery and GPU operators to distribute the ML workload.
* The attendees will understand how to overcome the GPU hardware limits of a single node training by taking advantage of GPUs on other machines, and therefore, maximizing the utilization of GPUs in an open cloud environment.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup10.pdf) and [Video Recording](https://youtu.be/rFaoM61dglM)

April 5th, 2022 - **AI4CI - Artificial Intelligence for Continuous Integration**

* By Aakanksha Duggal, Hema Veeradhi, Karan Chauhan, Oindrilla Chatterjee and Shrey Anand
* In this session, the speakers introduce AI4CI (Artificial Intelligence for Continuous Integration), a collection of open-source AIOps tools involving open operations data made available by Kubernetes testing and visualization platforms. 
* The speakers will demonstrate how they developed a set of Jupyter Notebooks which are automated using Kubeflow Pipelines into repeatable processes that collect data from various open CI/CD data platforms, calculate and visualize key performance indicator metrics, build AI/ML services to support operations and create a reproducible workflow around these processes.
* In this session, attendees learn about a set of AIOps services deployed on Operate First that they can start using and get familiarized with how to use the set of tools available on the Operate First cloud to deploy their own workloads.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup9.pdf) and [Video Recording](https://youtu.be/M4thSVYdIT0)

March 22nd, 2022 - **Sandiego**

* By Cali Dolfi
* In this talk, get an overview of Project Sandiego out of Red Hat’s Open Source Program office. 
* Get an understanding of the goals of the project, the tooling currently available, and what is currently in development.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup8.pdf) and [Video Recording](https://youtu.be/wuNfy4u64-g)

March 8th, 2022 - **Operate First Cluster Infrastructure**

* By Humair Khan
* In this talk, get an overview of the Operate-First Cloud Instance. The overview will cover all the clusters currently being managed by the Operate-First operations team.
* Learn how these services are deployed on the operate first cluster, how you can get access to them, and how to contribute and participate in the Operate First Operations.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup7.pdf) and [Video Recording](https://youtu.be/dBp0iYU70iE)


February 22nd, 2022 - **Anomaly detection using Hierarchical Temporal Memory (HTM) algorithm on operate first CPU data**

* By Surya Prakash Pathak
* In this talk, get introduced to the concept of HTM algorithm, followed by its application to anomaly detection on operate first CPU usage data.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup6.pdf) and [Video Recording](https://youtu.be/t7LeAYBNRKA)

February 8th, 2022 - **Using Operate First for OS-Climate NLP model inference**

* By Shrey Anand
* In this talk, learn how to use Open Data Hub services on the Operate First infrastructure to create an end to end inference pipeline for a Natural language processing model.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup5.pdf) and [Video Recording](https://youtu.be/p61yvqb_bKY)

January 25th, 2022 - **Create an AI pipeline on ODH using Elyra, Kubeflow and Tekton**

* By Oindrilla Chatterjee
* In this session, learn how you can automate your data science workflow and run your notebooks in an automated fashion by creating an AI pipeline using Elyra, Kubeflow and Tekton.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup4.pdf) and [Video Recording](https://youtu.be/M8s74HGeT7I)


December 14th, 2021 - **Build your own JupyterHub image with aicoe-ci**

* Presented by Karan Chauhan
* Learn how to package your own data science content into container images using a simple CI tool, aicoe-ci, and share it as a reproducible data science development environment on JupyterHub.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup3.pdf) and [Video Recording](https://youtu.be/vtyumrV-LgA)

November 30, 2021 - **Reproducibility and Dependencies for Jupyter Notebooks**

* Presented by Francesco Murdaca
* Learn about the existing open data science platform managed by the Operate First team and how to create and share reproducible notebooks with jupyterlab-requirements available on Open Data Hub images. 
* Get a chance to perform a tutorial live on different common cases.
* [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup2.pdf) and [Video Recording](https://youtu.be/JqtZCsQPCKM) 

November 16, 2021 - **Inaugural Meeting** 

* Presented by Michael Clifford
* What is Operate First for Data Science?
* Deploy Jupyter Lab and Notebooks easily with Operate First.
* Learn how to get up and running with either a classic Jupyter notebook or a Jupyter lab instance with Operate First and start doing data science in the cloud!
* [Video Recording](https://youtu.be/v4mur-_ywBM)
