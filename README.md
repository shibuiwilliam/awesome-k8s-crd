# Awesome Kubernetes CRD
A curated list of awesome Kubernetes custom resource definition, CRD, or operators with CRD.

## What is CRD?
Custom resource definition is your original extension of the Kubernetes API.

## Awesome tutorials

- [Official custom resource document](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)
- [Official custom resource definition document](https://kubernetes.io/docs/tasks/access-kubernetes-api/custom-resources/custom-resource-definitions/)
- [Official Kubernetes operator pattern](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)
- [Code generator for Kubernetes style API](https://github.com/kubernetes/code-generator)
- [Official sample controller](https://github.com/kubernetes/sample-controller)
- [Deep dive to code generator](https://www.openshift.com/blog/kubernetes-deep-dive-code-generation-customresources)
- [An example CRD programming](https://insujang.github.io/2020-02-13/programming-kubernetes-crd/)
- [An example CRD](https://insujang.github.io/2020-02-11/kubernetes-custom-resource/)
- [O'Reilly's `Programming Kubernetes`](https://www.oreilly.com/library/view/programming-kubernetes/9781492047094/ch04.html)
- [EKS workshop for CRD](https://eksworkshop.com/intermediate/270_custom_resource_definition/creating_crd/)
- [IBM Cloud document](https://developer.ibm.com/technologies/containers/tutorials/kubernetes-custom-resource-definitions/)

## Awesome awesomes
- [OperatorHub.io](https://operatorhub.io/)
- [awesome-operators](https://github.com/operator-framework/awesome-operators)

## Awesome CRD

| Name | Github | URL | Description |
| ------- | ------- | ------- | ------- |
|  Airflow  | https://github.com/GoogleCloudPlatform/airflow-operator | https://airflow.apache.org/  | Airflow is a platform to programmatically author, schedule and monitor workflows.  |
|  Andrdoid SDK Operator  | https://github.com/aerogear-attic/android-sdk-operator | -  |  Android SDK operator that watches changes in a configmap object to install/remove Android SDK packages in a Persistent Volume. |
|   Aqua | https://github.com/aquasecurity/aqua-operator | -  |  The aqua-operator is a group of controllers that runs within a Kubernetes or Openshift cluster that provides a means to deploy and manage Aqua Security cluster and Components |
|  Argo CD  | https://github.com/argoproj/argo-cd | https://argoproj.github.io/argo-cd/  |  Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes. |
| aws-operator   | https://github.com/giantswarm/aws-operator |  https://www.giantswarm.io/ |  The aws-operator manages Kubernetes clusters running on AWS. |
|  bank-vault  | https://github.com/banzaicloud/bank-vaults |  https://banzaicloud.com/products/bank-vaults/ | Bank-Vaults is an umbrella project which provides various tools for Vault to make using and operating Hashicorp Vault easier.  |
|   cert-manager | https://github.com/jetstack/cert-manager | https://cert-manager.io/docs/  |  cert-manager is a Kubernetes add-on to automate the management and issuance of TLS certificates from various issuing sources. |
| cert-operator   | https://github.com/giantswarm/cert-operator |  -  | Cert Operator creates/configure/manages certificates for Kubernetes clusters running on Giantnetes.  |
|  cf-operator  | https://github.com/cloudfoundry-incubator/quarks-operator | https://www.cloudfoundry.org/project-quarks/  | cf-operator enables the deployment of BOSH Releases, especially Cloud Foundry, to Kubernetes.  |
|  cloudformation-operator  | https://github.com/linki/cloudformation-operator |  - |  A Kubernetes operator for managing CloudFormation stacks via kubectl and a custom resource definition. |
|  Elastic Cloud on Kubernetes (ECK)  | https://github.com/elastic/cloud-on-k8s | https://www.elastic.co/guide/en/cloud-on-k8s/current/index.html  | Elastic Cloud on Kubernetes automates the deployment, provisioning, management, and orchestration of Elasticsearch, Kibana and APM Server on Kubernetes based on the operator pattern.  |
|   envoy-operator | https://github.com/solo-io/envoy-operator | -  | The Envoy Operator project is a Kubernetes Operator. Its purpose is to enable easy deployment of Envoy proxies using a high level declarative API.  |
|  flux  | https://github.com/fluxcd/flux | https://docs.fluxcd.io/  | Flux is a tool that automatically ensures that the state of a cluster matches the config in git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means you don't need a separate CD tool.  |
|  GateKeeper  | https://github.com/replicatedhq/gatekeeper |  - |  Gatekeeper is currently an implementation of a Kubernetes Operator for installing, configuring and managing Open Policy Agent to provide dynamic admission controllers in a cluster. |
|  Grafana  | https://github.com/integr8ly/grafana-operator | https://grafana.com/  |  A Kubernetes Operator based on the Operator SDK for creating and managing Grafana instances. |
|  influxDB  | https://github.com/influxdata/influxdb-operator | -  | The Kubernetes operator for InfluxDB and the TICK stack.  |
|  Istio  | https://github.com/istio/community | https://istio.io/  |  Istio is an open platform for providing a uniform way to integrate microservices, manage traffic flow across microservices, enforce policies and aggregate telemetry data.  |
|  jaeger  | https://github.com/jaegertracing/jaeger-operator |  https://www.jaegertracing.io/ |  open source, end-to-end distributed tracing |
|  Jenkins Operator  | https://github.com/jenkinsci/kubernetes-operator | https://jenkinsci.github.io/kubernetes-operator/  | The Jenkins Operator is a Kubernetes Native Operator which manages operations for Jenkins on Kubernetes.  |
|  Katib  |   https://github.com/kubeflow/katib  |   https://www.kubeflow.org/docs/components/hyperparameter-tuning/hyperparameter/  |  Katib is a Kubernetes-based system for Hyperparameter Tuning and Neural Architecture Search. |
| kiali  |  https://github.com/kiali/kiali |  https://kiali.io/ | Kiali is a management console for Istio-based service mesh. It provides dashboards, observability and lets you to operate your mesh with robust configuration and validation capabilities. |
|  knative  |  https://github.com/knative/operator/   |  https://knative.dev/   |   The Knative Operator defines custom resources for the Knative components, serving and eventing, enabling users to configure, install, upgrade and maintain these components over their lifecycle through a simple API. |
|  kopf  |  https://github.com/zalando-incubator/kopf   |  https://kopf.readthedocs.io/en/latest/   |  A Python framework to write Kubernetes operators in just few lines of code.  |
|   Kubeflow   |    https://github.com/kubeflow/kubeflow   |    https://www.kubeflow.org/  |  Kubeflow is a Cloud Native platform for machine learning based on Google’s internal machine learning pipelines. |
|  kubernetes dashboard  |  https://github.com/kubernetes/dashboard   |  https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/   |  Kubernetes Dashboard is a general purpose, web-based UI for Kubernetes clusters. It allows users to manage applications running in the cluster and troubleshoot them, as well as manage the cluster itself.  |
|  Kubernetes Elasticsearch Operator  |  https://github.com/side8/k8s-elasticsearch-operator   |  -   | A Kubernetes Elasticsearch Operator   |
|   KUDO |   https://github.com/kudobuilder/kudo  |   https://kudo.dev/docs/  |  Kubernetes Universal Declarative Operator (KUDO) provides a declarative approach to building production-grade Kubernetes Operators covering the entire application lifecycle.  |
|  Mattermost  |  https://github.com/mattermost/mattermost-operator   |   https://mattermost.com/  | Mattermost is a scalable, open source collaboration tool. It's written in Golang and React.   |
|   Memcached Operator |  https://github.com/ianlewis/memcached-operator   |  https://memcached.org/   |  memcached-operator is a Kubernetes Operator for deploying and managing a cluster of Memcached instances.  |
|  MongoDB  |  https://github.com/mongodb/mongodb-enterprise-kubernetes   |  https://docs.mongodb.com/kubernetes-operator/stable/configure-k8s-operator-for-mdb-resources/   |  MongoDB Enterprise Kubernetes Operator  |
|  MySQL  |   https://github.com/oracle/mysql-operator  |   -  |  The MySQL Operator creates, configures and manages MySQL InnoDB clusters running on Kubernetes. It is not for MySQL NDB Cluster.  |
|   navigator |  https://github.com/jetstack/navigator   |   https://navigator-dbaas.readthedocs.io/  |  Navigator is a Kubernetes extension for managing common stateful services on Kubernetes.   |
|  Crunchy PostgreSQL  |  https://github.com/CrunchyData/postgres-operator   |   https://www.crunchydata.com/  | The Crunchy PostgreSQL Operator automates and simplifies deploying and managing open source PostgreSQL clusters on Kubernetes and other Kubernetes-enabled Platforms by providing the essential features you need to keep your PostgreSQL clusters up and running   |
|  Zalando PostgreSQL  |   https://github.com/zalando/postgres-operator  |    https://postgres-operator.readthedocs.io/en/latest/ |  The Postgres Operator enables highly-available PostgreSQL clusters on Kubernetes (K8s) powered by Patroni. It is configured only through manifests to ease integration into automated CI/CD pipelines with no access to Kubernetes directly.  |
|  runtime component operator  |   https://github.com/application-stacks/runtime-component-operator  |  -   |  A generic Operator capable of deploying any runtime component image with enterprise QoS and bind it to other services  |
| Prometheus   |   https://github.com/coreos/prometheus-operator  |   https://github.com/coreos/kube-prometheus  |  Use Prometheus to monitor Kubernetes and applications running on Kubernetes  |
|  Redis  |  https://github.com/spotahome/redis-operator   |  -   |   Redis Operator creates/configures/manages redis-failovers atop Kubernetes. |
| Seldon-core   |   https://github.com/SeldonIO/seldon-core  |  https://docs.seldon.io/projects/seldon-core/en/latest/   | An open source platform to deploy your machine learning models on Kubernetes at massive scale.   |
|  spark-on-k8s-operator  |   https://github.com/GoogleCloudPlatform/spark-on-k8s-operator  |  -   |   Kubernetes operator for managing the lifecycle of Apache Spark applications on Kubernetes. |
|  splunk  |   https://github.com/splunk/splunk-operator  |   -  |  The Splunk Operator for Kubernetes (SOK) makes it easy for Splunk Administrators to deploy and operate Enterprise deployments in a Kubernetes infrastructure.   |
|  Strimzi kafka  |   https://github.com/strimzi/strimzi-kafka-operator  |  https://strimzi.io/   | Strimzi provides a way to run an Apache Kafka cluster on Kubernetes or OpenShift in various deployment configurations.   |
|  Sysdig  |   https://github.com/sysdiglabs/sysdig-operator/  |  https://sysdig.com/   |  Sysdig agent Operator configure Sysdig platform in your Kubernetes cluster  |
|  Velero  |  https://github.com/vmware-tanzu/velero   | https://velero.io/    |  Velero (formerly Heptio Ark) gives you tools to back up and restore your Kubernetes cluster resources and persistent volumes.  |
