# awesome-devops

A curated list of awesome softwares for Devops.

## Toc

* [awesome-devops](#awesome-devops)
  * [Toc](#toc)
  * [SCM](#scm)
  * [CI & CD](#ci--cd)
  * [Container](#container)
  * [IDE & Editor](#ide--editor)
  * [Documents](#documents)
  * [Communication](#communication)
  * [Api Manager](#api-manager)
  * [Storage](#storage)
  * [Image Storage Service](#image-storage-service)
  * [Monitor](#monitor)
  * [Application Definition](#application-definition)
  * [Configure](#configure)
  * [APM](#apm)
  * [Cloud](#cloud)
  * [Logging](#logging)
  * [Service](#service)
  * [Service Management](#service-management)
  * [Bench Test](#bench-test)
  * [PM](#pm)
  * [Others](#others)

## SCM

* [Git](https://git-scm.com/) - Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
* [Github](https://github.com/) - The world's leading software development platform.
* [Gitlab](https://about.gitlab.com/) - GitLab is a web-based Git-repository manager with wiki, issue-tracking and CI/CD pipeline features, using an open-source license, developed by GitLab Inc.
* [Mercurial](https://www.mercurial-scm.org/) - Work easier. Work faster. Mercurial is a free, distributed source control management tool.
* [Gogs](https://gogs.io/) - A painless self-hosted Git service.
* [Gitea](https://gitea.io/en-us/) - Gitea - Git with a cup of tea. Fork of Gogs.

## CI & CD

* [Jenkins](https://jenkins.io/) - Jenkins is a self-contained Java-based program, ready to run out-of-the-box, with packages for Windows, Mac OS X and other Unix-like operating systems.
* [Gitlab-ci](https://about.gitlab.com/features/gitlab-ci-cd/) - GitLab has integrated CI/CD pipelines to build, test, deploy, and monitor your code.
* [Shippable](https://www.shippable.com/) - CI, CD, and DevOps automation platform with Docker support that simplifies provisioning, building, testing, and deploying any application anywhere.
* [Bamboo](https://www.atlassian.com/software/bamboo) - Bamboo is a continuous integration and deployment tool that ties automated builds, tests and releases together in a single workflow.
* [Deployer](https://deployer.org/) - A deployment tool written in PHP with support for popular frameworks out of the box.
* [Walle](http://www.walle-web.io/) - Stable online support for multi-project, multi-environment one-click deployment on-line, one-click quick rollback clear record online application, review, deployment, real-time operation log.
* [AWS CodePipeline](https://aws.amazon.com/codepipeline/) - AWS CodePipeline is a continuous delivery service you can use to model, visualize, and automate the steps required to release your software.
* [AWS CodeDeploy](https://aws.amazon.com/codedeploy/) - AWS CodeDeploy is a deployment service that automates application deployments to Amazon EC2 instances, on-premises instances, or serverless Lambda functions.
* [Drone](https://drone.io/) - Drone is a Continuous Delivery platform built on Docker, written in Go.
* [werf](https://werf.io/) - A CI/CD tool for delivering Docker images to Kubernetes via GitOps approach, integrates with any CI systems, written in Go.
* [GitLab Pipelines by puzl.cloud](https://gitlab-pipelines.puzl.cloud) - Blazing-fast, cost-effective execution layer for GitLab CI/CD pipeline jobs, offering per-second billing and k8s API for runner management.

## Container

* [Docker](https://www.docker.com/) - Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications, whether on laptops, data center VMs, or the cloud.
* [Podman](https://podman.io) - Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux System. Containers can either be run as root or in rootless mode.
* [Kubernetes](https://kubernetes.io/) - Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications.
* [Rancher](https://rancher.com/) - Rancher is open source software that combines everything an organization needs to adopt and run containers in production. Built on Kubernetes, Rancher makes it easy for DevOps teams to test, deploy and manage their applications.
* [Mesos](http://mesos.apache.org/) - Apache Mesos abstracts CPU, memory, storage, and other compute resources away from machines (physical or virtual), enabling fault-tolerant and elastic distributed systems to easily be built and run effectively.
* [Swarm](https://github.com/docker/swarm) - Swarm: a Docker-native clustering system.
* [Docker Compose](https://github.com/docker/compose) - Define and run multi-container applications with Docker.
* [Docker Machine](https://github.com/docker/machine) - Docker Machine is a tool that lets you install Docker Engine on virtual hosts, and manage the hosts with docker-machine commands.
* [Portainer](https://github.com/portainer/portainer) - Simple management UI for Docker [http://portainer.io](http://portainer.io)
* [Docker Registry](https://docs.docker.com/registry/) - Docker Trusted Registry (DTR) is a commercial product that enables complete image management workflow, featuring LDAP integration, image signing, security scanning, and integration with Universal Control Plane.
* [Meshery](https://github.com/meshery/meshery) - Meshery is a highly extensible CNCF project enabling collaborative design and operation of cloud-native infrastructure, with Kubernetes clusters management and visualization tools.
* [Kanvas](https://kanvas.new) - Kanvas is a collaborative designer and operator for cloud-native infrastructure, offering an intuitive interface to manage Kubernetes resources efficiently.

## IDE & Editor

* [Sublime Text](https://www.sublimetext.com/) - A sophisticated text editor for code, markup and prose
* [Visual Studio Code](https://code.visualstudio.com/) - Visual Studio Code is a lightweight but powerful source code editor.
* [Eclipse](https://www.eclipse.org/) - Eclipse is a platform that has been designed from the ground up for building integrated web and application development tooling.
* [PyCharm](https://www.jetbrains.com/pycharm/) - Python IDE for Professional Developers by JetBrains.
* [PhpStorm](https://www.jetbrains.com/phpstorm/) - Lightning-Smart IDE for PHP Programming by JetBrains.
* [IntelliJ IDEA](https://www.jetbrains.com/idea/) - The Java IDE for Professional Developers by JetBrains.
* [GoLand](https://www.jetbrains.com/go/) - A Clever IDE to Go by JetBrains.
* [CLion](https://www.jetbrains.com/clion/) - A Cross-Platform IDE for C and C++ by JetBrains.
* [WebStorm](https://www.jetbrains.com/webstorm/) - The Smartest JavaScript IDE by JetBrains.
* [Xcode](https://developer.apple.com/xcode/) - Xcode 10 includes everything you need to create amazing apps for all Apple platforms.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [Atom](https://atom.io/) - Atom is a free and open-source text and source code editor for MacOS, Linux, and Windows with support for plug-ins written in Node.js, and embedded Git Control, developed by GitHub.
* [Typora](https://typora.io/) - A markdown editor, markdown reader.
* [MWeb](https://www.mweb.im/) - Pro Markdown writing, note taking and static blog generator App.
* [MacDown](http://macdown.uranusjr.com/) - Markdown editor.
* [CodeLobster](https://codelobster.com/) - A free cross-platform IDE with many plug-ins for all popular frameworks.

## Documents

* [Confluence](https://www.atlassian.com/software/confluence) - Confluence is where you create, organize and discuss work with your team.
* [Dokuwiki](https://www.dokuwiki.org/) - DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database.
* [Shimo](https://shimo.im/) - Cloud documents and forms that can be collaborated by multiple people in real time.
* [Google Drive](https://www.google.com/drive/) - Get access to files anywhere through secure cloud storage and file backup for your photos, videos, files and more with Google Drive.

## Communication

* [Slack](https://slack.com/) - Slack is where work flows. It's where the people you need, the information you share, and the tools you use come together to get things done.
* [Dingtalk](https://www.dingtalk.com/) - DingTalk is a free and all-in-one enterprise communication and collaboration platform.

## Api Manager

* [Postman](https://www.getpostman.com/) - Postman is the only complete API development environment, for API developers, used by more than 5 million developers and 100000 companies worldwide.
* [Charles](https://www.charlesproxy.com/) - Charles is an HTTP proxy / HTTP monitor / Reverse Proxy that enables a developer to view all of the HTTP and SSL / HTTPS traffic between their machine and the Internet.
* [AWS Api Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
* [Apiary](https://apiary.io/) - Platform for API Design, Development & Documentation.
* [Swagger](https://swagger.io/) - Swagger aides in development across the entire API lifecycle, from design and documentation, to test and deployment.

## Storage

* [OwnCloud](https://owncloud.org/) - The leading OpenSource Cloud Collaboration Platform, free and open-source.
* [Dropbox](https://www.dropbox.com/) - Dropbox is a home for all your work. You can store and share files, collaborate on projects.
* [AWS S3](https://aws.amazon.com/s3/) - Object storage built to store and retrieve any amount of data from anywhere.
* [Qiniu kodo](https://www.qiniu.com/en/products/kodo) - Qiniu Cloud's object storage (KODO), a completely independent-researched core technology which is proven by repeated customer experience has occupied absolute leading market leader position. KODO can be widely applied to mass data management.

## Image Storage Service

* [Qiniu](https://www.qiniu.com/en) - Qiniu image processing service does various operations for image files on Qiniu Cloud.
* [ImgURL](https://github.com/helloxz/imgurl) - ImgURL is a simple, pure bed program developed with PHP + SQLite 3 that does not require complex configuration and works out of the box.

## Monitor

* [Netdata](https://www.netdata.cloud/) - Netdata is a free monitoring solution with an open source agent that collects real-time metrics from your systems and applications, helping you monitor and troubleshoot them with ease.
* [Zabbix](https://www.zabbix.com/) - Zabbix is a mature and effortless enterprise-class open source monitoring solution for network monitoring and application monitoring of millions of metrics.
* [Influxdb](https://www.influxdata.com/) - Open Source Time Series DB Platform for Metrics & Events (Time Series Data).
* [Grafana](https://grafana.com/) - Data visualization & Monitoring with support for Graphite, InfluxDB, Prometheus, Elasticsearch and many more databases.
* [Prometheus](https://prometheus.io/) - An open-source monitoring system with a dimensional data model, flexible query language, efficient time series database and modern alerting approach.
* [Node Exporter](https://prometheus.io/docs/guides/node-exporter/) - The Prometheus Node Exporter exposes a wide variety of hardware and kernel-related metrics.
* [cAdvisor](https://github.com/google/cadvisor) - cAdvisor (Container Advisor) provides container users an understanding of the resource usage and performance characteristics of their running containers.
* [Telegraf](https://www.influxdata.com/time-series-platform/telegraf/) - Telegraf is a server-based agent for collecting and sending all metrics and events from databases, systems, and IoT sensors. Telegraf is written in Go and compiles into a single binary with no external dependencies, and requires a very minimal memory footprint.
* [Splunk](https://www.splunk.com/) - Splunk's core offering collects and analyzes high volumes of machine-generated data. It uses an API to connect to applications and devices.
* [Middleware](https://middleware.io/) - A full-stack cloud observability platform to monitor your data with ease and get the right insights faster.

## Application Definition

* [Maven](https://maven.apache.org/) - Apache Maven is a software project management and comprehension tool.
* [Gradle](https://gradle.org/) - Accelerate developer productivity. Gradle helps teams build, automate and deliver better software, faster.
* [AWS CodeBuild](https://aws.amazon.com/codebuild/) - AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy.

## Configure

* [Ansible](https://www.ansible.com/) - Ansible is the simplest way to automate apps and IT infrastructure. Application Deployment + Configuration Management + Continuous Delivery.
* [Chef](https://www.chef.io/) - Automation for all of your technology. Overcome the complexity and rapidly ship your infrastructure and apps anywhere with automation.
* [Puppet](https://puppet.com/) - Automatically deliver and operate all of your software across its entire lifecycle — simply, securely and at scale — with Puppet's modern automation.
* [Salt](https://github.com/saltstack/salt) - Software to automate the management and configuration of any infrastructure or application at scale.
* [Rudder](https://www.rudder-project.org/) - Get the latest version of Rudder for your distribution: Get Rudder. Easy to use, web-driven, role-based solution for IT Infrastructure Automation & Compliance.

## APM

* [Zipkin](https://zipkin.io/) -Zipkin is a distributed tracing system. It helps gather timing data needed to troubleshoot latency problems in microservice architectures.

## Cloud

* [OpenStack](https://www.openstack.org/) - OpenStack software controls large pools of compute, storage, and networking resources throughout a datacenter, managed through a dashboard or via the OpenStack API.
* [AWS](https://aws.amazon.com/) - Amazon Web Services offers reliable, scalable, and inexpensive cloud computing services. Free to join, pay only for what you use.
* [Alibabacloud](https://www.alibabacloud.com/) - Alibaba Cloud offers reliable and secure cloud computing services and solutions at competitive prices. Try for Free.
* [Microsoft Azure](https://azure.microsoft.com/en-us/) - Microsoft Azure is an open, flexible, enterprise-grade cloud computing platform. Move faster, do more, and save money with IaaS + PaaS. Try for FREE.
* [Google Cloud Platform](https://cloud.google.com/) - Build, innovate, and scale with Google Cloud Platform. Collaborate and be more productive with G Suite. See what's possible with Google Cloud.
* [Tencent Cloud](https://intl.cloud.tencent.com/) - Empower your business with our high-performance cloud services.
* [Huawei Cloud](https://intl.huaweicloud.com/) - Comprehensive Range of Cloud Computing Services.
* [Kinsta](https://kinsta.com/application-hosting/) - Create and deploy web applications and databases in minutes.


## Logging

* [Elasticsearch](https://www.elastic.co/) - Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases.
* [LogStash](https://www.elastic.co/products/logstash) - Logstash is an open source, server-side data processing pipeline that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favorite "stash."
* [Kibana](https://www.elastic.co/products/kibana) - Kibana lets you visualize your Elasticsearch data and navigate the Elastic Stack.
* [Graylog](https://www.graylog.org/) - Graylog is a leading centralized log management solution built to open standards for capturing, storing, and enabling real-time analysis of terabytes of machine data.
* [Filebeat](https://www.elastic.co/guide/en/beats/filebeat/current/filebeat-overview.html) - Filebeat is a lightweight shipper for forwarding and centralizing log data.

## Service

* [Zookeeper](https://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.
* [Etcd](https://coreos.com/etcd/) - etcd is a distributed key value store that provides a reliable way to store data across a cluster of machines. It's open-source and available on GitHub.
* [Consul](https://www.consul.io/) - Consul is a distributed service mesh to connect, secure, and configure services across any runtime platform and public or private cloud.

## Service Management

* [gRPC](https://grpc.io/) - A high-performance, open-source universal RPC framework.
* [Nginx](https://www.nginx.com/) - NGINX accelerates content and application delivery, improves security, facilitates availability and scalability for the busiest web sites on the Internet.
* [Istio](https://istio.io/) - Connect, secure, control, and observe services.
* [Enovy](https://www.envoyproxy.io/) - Envoy is an open source edge and service proxy, designed for cloud-native applications.
* [Spring Cloud](http://cloud.spring.io/) - Spring Cloud provides tools for developers to quickly build some of the common patterns in distributed systems.
* [Dubbo](https://dubbo.apache.org/en/) - Dubbo |ˈdʌbəʊ| offers six key functionalities, which include transparent interface based RPC, intelligent load balancing, automatic service registration and discovery, high extensibility, runtime traffic routing, and visualized service governance.

## Bench Test

* [AB](https://httpd.apache.org/docs/2.4/programs/ab.html) - ab is a tool for benchmarking your Apache Hypertext Transfer Protocol (HTTP) server.
* [JMeter](https://jmeter.apache.org/) - The Apache JMeter™ application is open source software, a 100% pure Java application designed to load test functional behavior and measure performance.
* [LoadRunner](https://software.microfocus.com/en-us/products/loadrunner-load-testing/overview) - LoadRunner is a software testing tool from Micro Focus. It is used to test applications, measuring system behaviour and performance under load. LoadRunner can simulate thousands of users concurrently using application software, recording and later analyzing the performance of key components of the application.
* [TCPCopy](https://github.com/session-replay-tools/tcpcopy) - TCPCopy is a TCP stream replay tool to support real testing of Internet server applications.
* [Siege](https://www.joedog.org/siege-home/) - Siege is an http load testing and benchmarking utility.
* [Tsung](http://tsung.erlang-projects.org/) - Tsung is a high-performance benchmark framework for various protocols including HTTP, XMPP, LDAP, etc.
* [Wrk](https://github.com/wg/wrk) - Modern HTTP benchmarking tool.
* [Web Bench](http://home.tiscali.cz/~cz210552/webbench.html) - Web Bench is very simple tool for benchmarking WWW or proxy servers.
* [Http_load](https://acme.com/software/http_load/) - http_load runs multiple http fetches in parallel, to test the throughput of a web server.

## PM

* [Jira](https://www.atlassian.com/software/jira) - Plan, track, and manage your agile and software development projects in Jira. Customize your workflow, collaborate, and release great software.
* [Redmine](https://www.redmine.org/) - Redmine is a flexible project management web application. Written using the Ruby on Rails framework, it is cross-platform and cross-database.
* [Teambition](https://www.teambition.com/) - Teambition is a simple, efficient project collaboration tool where you can manage projects, track progress, store project files, and make your team work more efficient.
* [Trello](https://trello.com/) - Infinitely flexible. Incredibly easy to use. Great mobile apps. It's free. Trello keeps track of everything, from the big picture to the minute details.
* [FadeTask](https://app.fadetask.com) - It's free kanban, like trello, just support Chinese.

## Others

* [Splunk](https://www.splunk.com/) - Splunk Inc. turns machine data into answers with the leading platform to tackle the toughest IT, IoT and security challenges. Use Splunk to search, monitor, analyze and visualize machine data.
* [Logit.io](https://www.logit.io/) - Logit.io provides an affordable and scalable solution for hosting ELK, Grafana & Open Distro for metrics and log analysis.
* [Nagios](https://www.nagios.org/) - Nagios provides enterprise-class Open Source IT monitoring, network monitoring, server and applications monitoring.
* [Monit](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-monit) - Monit is a helpful program that automatically monitors and manages server programs to ensure that they not only stay online consistently, but that the file size, checksum, or permissions are always correct.
* [Supervisor](http://supervisord.org/) - Supervisor is a client/server system that allows its users to monitor and control a number of processes on UNIX-like operating systems.
* [Hipchat](https://www.hipchat.com/) - HipChat was a web service for internal private online chat and instant messaging.
* [Bitbucket](https://bitbucket.org/) - Collaborate on code with inline comments and pull requests. Manage and share your Git repositories to build and ship software, as a team.
* [Datadog](https://www.datadoghq.com/) - Datadog is a monitoring service for cloud-scale applications, providing monitoring of servers, databases, tools, and services, through a SaaS-based data analytics platform.
* [Statuspage](https://www.statuspage.io/) - StatusPage.io is the best way for web infrastructure, developer API, and SaaS companies to get set up with their very own status page in minutes.
* [Pendo](https://www.pendo.io/) - Pendo helps product teams understand and guide users to create product experiences that customers love.
* [Vagrant](https://www.vagrantup.com/) - Vagrant enables users to create and configure lightweight, reproducible, and portable development environments.
* [PagerDuty](https://www.pagerduty.com/) - PagerDuty is a cloud computing company that produces a SaaS incident response platform for IT departments.
* [Juju](https://jujucharms.com/) - Juju is an open source, application and service modelling tool from Ubuntu that helps you deploy, manage and scale your applications on any cloud.
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - PHP_CodeSniffer is a set of two PHP scripts; the main phpcs script that tokenizes PHP, JavaScript and CSS files to detect violations of a defined coding standard, and a second phpcbf script to automatically correct coding standard violations.
* [Swoole-Compiler](http://compiler.swoole.com/) - Compile the PHP program source code into binary instructions and encrypt them.
* [Phpspy](https://github.com/adsr/phpspy) - Low-overhead sampling profiler for PHP 7.
* [waifu2x](http://waifu2x.udp.jp/) - Single-Image Super-Resolution for Anime-Style Art using Deep Convolutional Neural Networks.
* [Carbon](https://carbon.now.sh/) - Create and share beautiful images of your source code.
* [CodeLF](https://github.com/unbug/codelf) - Search over projects from GitHub, Bitbucket, GitLab to find real-world usage and variable names.
* [Cloud 66](https://www.cloud66.com/) - DevOps as a service that helps to build, deploy and manage any application on any cloud or server.
* [InfraScan](https://infrascan.soldevelo.com) - An Advanced Infrastructure Auditor by SolDevelo. Comprehensive scans for AWS cost antipatterns, IaC security issues, and container vulnerabilities.
