# Agenda + Previous Talks

## Upcoming

2022

- Tuesday, November 15th 2022 - S02E03 - **KRUIZE HPO**
- Tuesday, November 29th 2022 - S02E04 - **apicurio**
- Tuesday, December 13th 2022 - ? - **tbd**
- Tuesday, December 27th 2022 - There will be no meetup due to public holidays in some countries.

2023

- Tuesday, January 10th 2023 - **tbd**
- Tuesday, January 24th 2023 - **AI4cloudop / Ray on MOC**

## Past Events

November 1nd 2022 - There will be no meetup due to public holidays in some countries.

October 18th 2022 - S02E02 - **The Backstage is yours.**

- Presented by Tom Coufal [@tumido](https://github.com/tumido)
- In this episode Tom Coufal is presenting his approach of using Backstage on Operate First.
- [Video Recording](https://op1.st/meetup-S02E02)

October 4th 2022 - S02E01 - **Let's go data-hunting with jaeger!**

- Presented by Sally O'Malley [@sallyom](https://github.com/sallyom)
- Senior software engineer Sally Ann O'Malley describes recent additions to the Operate First cloud that simplify the collection of OpenTelemetry data.
  Catch her on K8s slack or GitHub @sallyom

- Over the past few years, the open source project OpenTelemetry has advanced cloud-native observability.
  As modern software platforms have become more distributed and complex, observing application data has become more critical and also more difficult.
  OpenTelemetry is a collection of tools, APIs, standards, and SDKs to instrument, generate, collect, and export telemetry data (metrics, logs, and traces).
  With OpenTelemetry (OTLP), end-users and developers are empowered to choose a telemetry backend that suits their needs.
  It is vendor neutral, open source, and is supported by industry leaders in the observability space.
  This post describes recent additions to the Operate First community cloud that have made it easy for users to collect and analyze OTLP.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/S02E01_2022-10-04_Operate-First_MeetUp.pdf) and [Video Recording](https://youtu.be/5_IEpmOUhjs)
- Links
  - [Example from KubeCon](https://youtu.be/lQG6UKpTs6M)
  - [Smaug: Installed Operators](https://console-openshift-console.apps.smaug.na.operate-first.cloud/k8s/ns/otel-dev/operators.coreos.com~v1alpha1~ClusterServiceVersion)
  - [Smaug: otel-dev project](https://console-openshift-console.apps.smaug.na.operate-first.cloud/k8s/cluster/projects/otel-dev)
  - [ArgoCD otel-dev application](https://github.com/operate-first/apps/blob/master/argocd/overlays/moc-infra/applications/envs/moc/smaug/octo-otel-dev/hello-opentelemetry.yaml)
  - [hello-opentelemetry example instrumentation](https://github.com/sallyom/hello-opentelemetry)
  - [https://www.operate-first.cloud/blog/distributed-tracing](https://www.operate-first.cloud/blog/distributed-tracing)
  - [More interesting example application](https://developers.redhat.com/articles/2022/08/08/opentelemetry-quarkus-superheroes-demo-observability#analyzing_telemetry_data)

July 26th 2022 - #17 - **Future of the Operate First Data Science Community - Expanding the organizers of the meetup**

- Presented by Karsten Wade [@quaid](https://github.com/quaid)
- One of the first public faces of the Operate First project was the early iterations of the Operate First Data Science Community Meetup, and it has grown to be a popular and recognizable aspect of this community. Along the way, it has had multiple hands in front of and behind the camera to curate the meetup space. The managing, organizing, and running of the meetups is a fairly well-understood process that can be run by one or two people, but should it be run by one or two people? By scaling it beyond just one pair of hands, a group of people who care about the meetup can help steward it into the future, without the meetup being dependent on one person's evolving job role.
- Are you someone who cares about the Operate First Data Science Meetup? Can you lend some voice to the value this meetup has for you? Would you want to help make the meetup happen through a small time commitment and collaboration with a group of meetup organizers?
- Let's have an open discussion about how we can scale the meetup process so more of us can get the benefits of helping define and continue the Data Science Meetup. Karsten will give a brief overview of the Operate First project and how data science is central to the project's mission. He'll also talk about the value of connection points like meetups, and how and why you can participate in many ways to add to this meetup's success.
- [Video Recording](https://youtu.be/yH4bpglzJUA)

July 12th, 2022 - #16 - **CCO: a next generation cost optimizer for complex cloud workloads**

- Presented by Ilya Kolchinsky and Adi Yehoshua
- In this session, learn about CCO - a novel optimization engine for minimizing cloud (AWS, Azure, etc.) costs for complex workloads (i.e., with up to hundreds/thousands of applications and/or components).
- The goal of CCO is to calculate the best possible assignment of tasks or application components to cloud instances such that the total monetary cost is minimized or at the very least does not exceed a predefined budget. To that end, the engine periodically collects up-to-date resource prices and statistics, then utilizes advanced algorithmic approaches and machine learning to solve the optimization problem.
- This project is done jointly with the Technion, Israel Institute of Technology, as a part of a broader partnership.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup16.pdf) and [Video Recording](https://youtu.be/PxLbo1USjqU)

June 28th, 2022 - #15 - **The Future of the Operate First Data Science Community**

- Presented by Michael Clifford [@MichaelClifford](https://github.com/MichaelClifford)
- The presenter will be discussing some upcoming changes to the Operate First Data Science community at large. Specifically, it's transition from its current state to an official Special Interest Group (SIG) governed by the Operate First community. He will be explaining what becoming a SIG means, reviewing the community's goals and purposes, and presenting the draft SIG charter for which community input and feedback would be much appreciated.
- By the end of this talk, attendees will have a better grasp of how the Operate First Data Science community is growing as well has having the opportunity to share their opinions and provide feedback on its future direction.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup15.pdf) and [Video Recording](https://youtu.be/SsS5QvpDbdA)

June 14th, 2022 - #14 - **Project Thoth - Python Dependecy Management and Jupyter Notebook Extensions**

- Presented by Harshad Reddy Nalla [@harshad16](https://github.com/harshad16) and Maya Costantini [@mayaCostantini](https://github.com/mayaCostantini)
- The presenters will go over Python dependency management by Project Thoth and how to use the new extension in Jupyter Notebook experiences.
- By the end of this session, attendees will learn the importance of reproducibility, Thoth recommendation using the Thoth CLI Thamos and how to use the Thoth Jupyterlab extension for Python projects. We will be able to manage dependencies in an easy manner benefiting from Thoth recommendations in jupyterhub or in the command line. This session would include a presentation and a demo.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup14.pdf) and [Video Recording](https://youtu.be/ixSeFDXfPq4)

May 31st, 2022 - #13 - **copilot-ops: Go From Zero to DevOps Hero in Under 10 Seconds**

- By Oleg Silkin
- In the age of cloud-native computing, Kubernetes has taken the world by storm, forcing many of us to spend more time on Google than we should, just to become YAML experts. This ends up being a time-consuming process, as many of the YAMLs share a similar structure with differing values based on the specifics of your deployment.
- **copilot-ops** is a CLI tool which supercharges your DevOps capabilities by allowing the user to specify what needs to be created/changed, along with some files to provide context on what values the resulting YAML should use.
- By the end of this talk, attendees will know how to use copilot-ops to supercharge their DevOps capabilities and quickly generate or edit desired YAML files at a moment's notice. Attendees will also walk away with a basic understanding of how Generative Pre-Trained Transformer 3 (GPT-3) can be used for code-generation tasks.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup13.pdf) and [Video Recording](https://youtu.be/eB6JNAaWMUE)

May 17th, 2022 - #12 - **Bringing AI and Machine Learning into Operation**

- By Audrey Reznik
- As a Data Scientist it is often difficult to know where to start your project. Do I test and build my model in an IDE? If I build and test my model in an IDE, how do I connect to my resources such as streaming data or databases? How can I optimize my model inference performance? Once I have optimized my model how do I easily deploy and manage it? Plus what options are available for me to deploy onPrem or in a Hybrid cloud environment?
- In this session we will discuss an easy way to build, test, train and deploy high performant models using a variety of platforms and tools created for OpenShift.
- The attendees will learn about what is Open Datahub, Red Hat OpenShift Data Science and Managed Services.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup12.pdf) and [Video Recording](https://youtu.be/mHa2O116RS8)

May 3rd, 2022 - #11 - **Data Obfuscation Techniques**

- By Surya Prakash Pathak [@suppathak](https://github.com/suppathak)
- A common scenario encountered by data scientists is sharing confidential and sensitive data with others. A lot of data we collect today can easily be linked to an individual, household, or entity. What should we do when we need to share these data with others? One of the methods to anonymize personal and confidential data is by using data obfuscation techniques. Data obfuscation is the process of replacing sensitive information with data that looks like real production information, making it useless to malicious actors.
- In this talk, we will get introduced to different hashing techniques used for data obfuscation. In addition to this, we will also go over the obfuscation technique we used for obfuscating meetup attendees' data.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup11.pdf) and [Video Recording](https://youtu.be/aj-THe9fFIQ)

April 19th, 2022 - #10 - **Distributed ML workloads on OpenShift**

- By Selbi Nuryyeva
- As the datasets and models get bigger, the demand for more powerful and efficient GPUs is rapidly increasing. Oftentimes a single GPU is not adequate for an ML use case. An alternative to upgrading the GPU hardware is to distribute the ML workload either across several GPUs on one node, or across multiple nodes each containing one or several GPUs. The ability for the latter is especially preferred when a single machine can fit only so many GPUs.
- In this talk, we will explore how one can distribute a machine learning workflow across several nodes with GPU hardware in a cloud environment. We will use PyTorch to carry out the ML training and Kubeflow, Node Feature Discovery and GPU operators to distribute the ML workload.
- The attendees will understand how to overcome the GPU hardware limits of a single node training by taking advantage of GPUs on other machines, and therefore, maximizing the utilization of GPUs in an open cloud environment.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup10.pdf) and [Video Recording](https://youtu.be/rFaoM61dglM)

April 5th, 2022 - #09 - **AI4CI - Artificial Intelligence for Continuous Integration**

- By Aakanksha Duggal [@aakankshaduggal](https://github.com/aakankshaduggal), Hema Veeradhi [@hemajv](https://github.com/hemajv), Karan Chauhan, Oindrilla Chatterjee [@oindrillac](https://github.com/oindrillac) and Shrey Anand
- In this session, the speakers introduce AI4CI (Artificial Intelligence for Continuous Integration), a collection of open-source AIOps tools involving open operations data made available by Kubernetes testing and visualization platforms.
- The speakers will demonstrate how they developed a set of Jupyter Notebooks which are automated using Kubeflow Pipelines into repeatable processes that collect data from various open CI/CD data platforms, calculate and visualize key performance indicator metrics, build AI/ML services to support operations and create a reproducible workflow around these processes.
- In this session, attendees learn about a set of AIOps services deployed on Operate First that they can start using and get familiarized with how to use the set of tools available on the Operate First cloud to deploy their own workloads.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup9.pdf) and [Video Recording](https://youtu.be/M4thSVYdIT0)

March 22nd, 2022 - #08 - **Sandiego**

- By Cali Dolfi [@cdolfi](https://github.com/cdolfi)
- In this talk, get an overview of Project Sandiego out of Red Hat’s Open Source Program office.
- Get an understanding of the goals of the project, the tooling currently available, and what is currently in development.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup8.pdf) and [Video Recording](https://youtu.be/wuNfy4u64-g)

March 8th, 2022 - #07 - **Operate First Cluster Infrastructure**

- By Humair Khan
- In this talk, get an overview of the Operate-First Cloud Instance. The overview will cover all the clusters currently being managed by the Operate-First operations team.
- Learn how these services are deployed on the operate first cluster, how you can get access to them, and how to contribute and participate in the Operate First Operations.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup7.pdf) and [Video Recording](https://youtu.be/dBp0iYU70iE)

February 22nd, 2022 - #06 - **Anomaly detection using Hierarchical Temporal Memory (HTM) algorithm on operate first CPU data**

- By Surya Prakash Pathak
- In this talk, get introduced to the concept of HTM algorithm, followed by its application to anomaly detection on operate first CPU usage data.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup6.pdf) and [Video Recording](https://youtu.be/t7LeAYBNRKA)

February 8th, 2022 - #05 - **Using Operate First for OS-Climate NLP model inference**

- By Shrey Anand
- In this talk, learn how to use Open Data Hub services on the Operate First infrastructure to create an end to end inference pipeline for a Natural language processing model.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup5.pdf) and [Video Recording](https://youtu.be/p61yvqb_bKY)

January 25th, 2022 - #04 - **Create an AI pipeline on ODH using Elyra, Kubeflow and Tekton**

- By Oindrilla Chatterjee
- In this session, learn how you can automate your data science workflow and run your notebooks in an automated fashion by creating an AI pipeline using Elyra, Kubeflow and Tekton.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup4.pdf) and [Video Recording](https://youtu.be/M8s74HGeT7I)

December 14th, 2021 - #03 - **Build your own JupyterHub image with aicoe-ci**

- Presented by Karan Chauhan
- Learn how to package your own data science content into container images using a simple CI tool, aicoe-ci, and share it as a reproducible data science development environment on JupyterHub.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup3.pdf) and [Video Recording](https://youtu.be/vtyumrV-LgA)

November 30, 2021 - #02 - **Reproducibility and Dependencies for Jupyter Notebooks**

- Presented by Francesco Murdaca
- Learn about the existing open data science platform managed by the Operate First team and how to create and share reproducible notebooks with jupyterlab-requirements available on Open Data Hub images.
- Get a chance to perform a tutorial live on different common cases.
- [Slides](https://github.com/aicoe-aiops/operate-first-data-science-community/blob/main/docs/content/opfmeetup2.pdf) and [Video Recording](https://youtu.be/JqtZCsQPCKM)

November 16, 2021 - #01 - **Inaugural Meeting**

- Presented by Michael Clifford
- What is Operate First for Data Science?
- Deploy Jupyter Lab and Notebooks easily with Operate First.
- Learn how to get up and running with either a classic Jupyter notebook or a Jupyter lab instance with Operate First and start doing data science in the cloud!
- [Video Recording](https://youtu.be/v4mur-_ywBM)
