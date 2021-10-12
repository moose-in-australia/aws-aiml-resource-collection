# AWS AI/ML Resources Collection
A personal collection of useful resources for AI/ML on AWS. Resources include workshops, whitepapers, blogs, solutions, and more. 

- [Amazon SageMaker](#amazon-sagemaker)
  - [MLOps](#mlops)
  - [Security](#security)
  - [Cost Control](#cost-control)
  - [Inference](#inference)
  - [Clarify](#clarify)
  - [Edge](#edge)
  - [Other](#other)
- [Amazon Personalize](#amazon-personalize)

---
## Amazon SageMaker

### MLOps

\[Blog, 10/21\] [**Create a cross-account machine learning training and deployment environment with AWS Code Pipeline**](https://aws.amazon.com/blogs/machine-learning/create-a-cross-account-machine-learning-training-and-deployment-environment-with-aws-code-pipeline/)
A CI/CD pipeline helps you automate steps in your ML applications and improves security, agility and resilience. In this post, learn how to set up the right cross-accounts IAM roles and trust relationships to create a cross-account pipeline while encrypting your central ML artifact store. Read this if you want to understand how to manually set up an environment similar to SageMaker Projects.

\[Blog, 09/21\] [**Customize Amazon SageMaker Studio using Lifecycle Configurations**](https://aws.amazon.com/blogs/machine-learning/customize-amazon-sagemaker-studio-using-lifecycle-configurations/)
Previously, customizations to Amazon SageMaker Studio environments were possible but needed to be reapplied manually every time apps were deleted or recreated. We’re excited to announce Lifecycle Configuration for Studio, a new capability that enables developers to automate customization for your Studio development environments.

\[Blog, 09/21\] [**Model and data lineage in machine learning experimentation**](https://aws.amazon.com/blogs/machine-learning/model-and-data-lineage-in-machine-learning-experimentation/)
Reproducibility in the ML research space is a challenging and multi-faceted topic, and quantitative finance is a prominent use case. By working with our customers across industry verticals, AWS is leading the way towards a holistic solution set in this field.

\[Blog, 09/21\] [**Scale ML feature ingestion using Amazon SageMaker Feature Store**](https://aws.amazon.com/blogs/machine-learning/scale-ml-feature-ingestion-using-amazon-sagemaker-feature-store/)
In this post, we provide an overview of ingestion options for Feature Store, and the benefits and use cases for each one. We also provide a GitHub repo that demonstrates several of these approaches, so you can try them out in your own AWS account.

\[Workshop, 09/21\] [**SageMaker Feature Store Workshop**](https://github.com/aws-samples/amazon-sagemaker-feature-store-end-to-end-workshop)
GitHub repo forms the basis of this workshop demonstrating SageMaker Feature Store, showing end-to-end examples. Multiple notebooks walk the user through feature group creation, single and parallel ingest, model training and hosting, plus Data Wrangler integration to feature store. The sample shows how to trigger SageMaker Pipelines from S3 file event.

\[Blog, 09/21\] [**Define and run Machine Learning pipelines on Step Functions using Python, Workflow Studio, or States Language**](https://aws.amazon.com/blogs/machine-learning/define-and-run-machine-learning-pipelines-on-step-functions-using-python-workflow-studio-or-states-language/)
In this post, we discuss how to author end-to-end ML pipelines in Step Functions using Python, drag and drop (using the new Step Functions Workflow Studio) and JSON.

\[Solution, 08/21\] [**AWS MLOps Framework**](https://aws.amazon.com/solutions/implementations/aws-mlops-framework/?did=sl_card&trk=sl_card)
The AWS MLOps Framework solution helps you streamline and enforce architecture best practices for machine learning (ML) model productionization. This solution is an extendable framework that provides a standard interface for managing ML pipelines for AWS ML services and third-party services. The solution’s template allows customers to upload their trained models (also referred to as bring your own model), configure the orchestration of the pipeline, and monitor the pipeline's operations. This solution increases your team’s agility and efficiency by allowing them to repeat successful processes at scale.

\[Blog, 08/21\] **Secure multi-account model deployment with Amazon SageMaker ([Part 1](https://aws.amazon.com/blogs/machine-learning/part-1-secure-multi-account-model-deployment-with-amazon-sagemaker/)) ([Part 2](https://aws.amazon.com/blogs/machine-learning/part-2-secure-multi-account-model-deployment-with-amazon-sagemaker/))**
This two part blog series offers guidance for implementing a production-grade ML platform and secure, automated, multi-account model deployment workflows. Such ML platforms and workflows can fulfill stringent security requirements for regulated industries such as financial services

\[Blog, 08/21\] [**Create Amazon SageMaker projects using third-party source control and Jenkins**](https://aws.amazon.com/blogs/machine-learning/create-amazon-sagemaker-projects-using-third-party-source-control-and-jenkins/)
Amazon SageMaker Pipelines, the first purpose-built CI/CD service for ML, is now integrated with popular third-party source code repositories such as GitHub and BitBucket; and software development automation tool - Jenkins.

\[Blog, 08/21\] [**Patterns for multi-account, hub-and-spoke Amazon SageMaker model registry**](https://aws.amazon.com/it/blogs/machine-learning/patterns-for-multi-account-hub-and-spoke-amazon-sagemaker-model-registry/)
When it comes to model deployment it often makes sense to have a central repository of approved models to keep track of what is being used for production-grade inference. In this post, learn how you can leverage SageMaker Model Registery to set up such a centralized repository.

\[Blog, 08/21\] [**Getting started with Amazon SageMaker Feature Store**](https://aws.amazon.com/blogs/machine-learning/getting-started-with-amazon-sagemaker-feature-store/)
Amazon SageMaker Feature Store provides a fully managed central repository for machine learning (ML) features. In this post, learn more about SageMaker Feature Store’s integrations with other features of Amazon SageMaker like Data Wrangler and Pipelines so that you can get started quickly.

\[Blog, 07/21\] [**Bring your own container to project model accuracy drift with Amazon SageMaker Model Monitor**](https://aws.amazon.com/blogs/machine-learning/bring-your-own-container-to-project-model-accuracy-drift-with-amazon-sagemaker-model-monitor/)
In this post, we present some techniques to detect covariate drift (one of the types of data drift) and demonstrate how to incorporate your own drift detection algorithms and visualizations with Model Monitor.

\[Blog, 07/21\] [**Orchestrate XGBoost ML Pipelines with Amazon Managed Workflows for Apache Airflow**](https://aws.amazon.com/blogs/machine-learning/orchestrate-xgboost-ml-pipelines-with-amazon-managed-workflows-for-apache-airflow/)
This post demonstrates the value of using Amazon Managed Workflows for Apache Airflow (Amazon MWAA) to orchestrate an ML pipeline using the popular XGBoost (eXtreme Gradient Boosting) algorithm.

\[Blog, 07/21\] [**MLOps with MLFlow and Amazon SageMaker Pipelines**](https://towardsdatascience.com/mlops-with-mlflow-and-amazon-sagemaker-pipelines-33e13d43f238)
This post shows how to use MLFlow together with Amazon SageMaker Pipelines.

\[Blog, 07/21\] [**Automate a centralized deployment of Amazon SageMaker Studio with AWS Service Catalog**](https://aws.amazon.com/blogs/machine-learning/automate-a-centralized-deployment-of-amazon-sagemaker-studio-with-aws-service-catalog/)
This post outlines the best practices for provisioning Amazon SageMaker Studio for data science teams and provides reference architectures and AWS CloudFormation templates to help you get started. We use AWS Service Catalog to provision a Studio domain and users. The AWS Service Catalog allows you to provision these centrally without requiring each user to obtain Amazon SageMaker access policies to provision Studio separately.

\[Blog, 06/21\] [**Automate Amazon SageMaker Studio setup using AWS CDK**](https://aws.amazon.com/blogs/machine-learning/automate-amazon-sagemaker-studio-setup-using-aws-cdk/)
In this post learn how to use the AWS Cloud Development Kit to set up Amazon SageMaker Studio and configure its access for data scientists and developers in your organization. With the AWS CloudFormation native resource to create a Studio domain and a user profile within the domain, you can automate the setup of Studio.

\[Blog, 06/21\] [**Build accurate ML training datasets using point-in-time queries with Amazon SageMaker Feature Store and Apache Spark**](https://aws.amazon.com/blogs/machine-learning/build-accurate-ml-training-datasets-using-point-in-time-queries-with-amazon-sagemaker-feature-store-and-apache-spark/)
In this post, we (the joint team of GoDaddy and AWS architects), explain how to use Feature Store and the processing power of Apache Spark to create accurate training datasets using point-in-time queries against reusable feature groups in a scalable fashion.

\[Blog, 05/21\] [**Automate feature engineering pipelines with Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/automate-feature-engineering-pipelines-with-amazon-sagemaker/)
In this post, we show you how a data scientist working on a new ML use case can use both Data Wrangler and Feature Store to create a set of feature transformations, perform them over a historical dataset, and then use SageMaker Pipelines to automatically transform and store features as new data arrives daily.

\[Whitepaper, 05/21\] [**Build a Secure Enterprise Machine Learning Platform on AWS**](https://docs.aws.amazon.com/whitepapers/latest/build-secure-enterprise-ml-platform/build-secure-enterprise-ml-platform.html?did)
This whitepaper helps cloud engineers, security engineers, Machine Learning Ops (MLOps) engineers, and data scientists understand the various components of building a secure enterprise machine learning (ML) platform. It provides prescriptive guidance on building a secure ML platform on Amazon Web Services (AWS).

\[Blog, 05/21\] [**Automating the Setup of SageMaker Studio Custom Images**](https://towardsdatascience.com/automating-the-setup-of-sagemaker-studio-custom-images-4a3433fd7148)
In most large enterprises, ML platform administrators will manage those custom images to ensure only approved libraries are used by the Studio users. This can represent operational overhead for admins, if done manually. In this post I show how you can implement simple continuous delivery for Studio custom images to automate your Studio domain setup.

\[Blog, 04/21\] [**Ingesting Historical Feature Data into SageMaker Feature Store**](https://towardsdatascience.com/ingesting-historical-feature-data-into-sagemaker-feature-store-5618e41a11e6#f950-d5882f6deacb) & [**Q&A for Ingesting Historical Data into SageMaker Feature Store**](https://towardsdatascience.com/q-a-for-ingesting-historical-data-into-sagemaker-feature-store-239e918ec594)
How to backfill the SageMaker Offline Feature Store by writing directly into S3.

\[Blog, 03/21\] [**Enable feature reuse across accounts and teams using Amazon SageMaker Feature Store**](https://aws.amazon.com/blogs/machine-learning/enable-feature-reuse-across-accounts-and-teams-using-amazon-sagemaker-feature-store/)
This post captures the essential cross-account architecture patterns for Feature Store that can be implemented in an organization with many data engineering and data science teams operating in different AWS accounts.

\[Code Sample, 02/21\] [**SageMaker custom studio image providing magic cells for a simplified experience in a notebook**](https://github.com/aws-samples/sagemaker-studio-notebook-magic-cell)
This solution provides a magic cell for a Jupyter Notebook to simplify the SageMaker training and SageMaker processing function by customizing a kernel and using Bring-Your-Own Image in SageMaker Studio.

\[Blog, 01/21\] [**Managing your machine learning lifecycle with MLflow and Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/managing-your-machine-learning-lifecycle-with-mlflow-and-amazon-sagemaker/)
During the initial phase of an ML project, data scientists collaborate and share experiment results in order to find a solution to a business need. During the operational phase, you also need to manage the different model versions going to production and your lifecycle. In this post, we’ll show how the open-source platform MLflow helps address these issues.

\[Solution, 01/21\] [**Amazon SageMaker with Guardrails on AWS**](https://aws.amazon.com/quickstart/architecture/amazon-sagemaker-with-guardrails/)
This Quick Start deployment of Amazon SageMaker adds guardrails so you can build, train, and deploy machine learning (ML) models in a more secure environment. Guardrails are high-level rules that provide ongoing governance for your overall AWS environment. AWS provides additional security by using AWS PrivateLink, Amazon CloudWatch, AWS Identity and Access Management (IAM), AWS Key Management Service (AWS KMS), and other native services.

\[Blog, 01/21\] [**Building, automating, managing, and scaling ML workflows using Amazon SageMaker Pipelines**](https://aws.amazon.com/blogs/machine-learning/building-automating-managing-and-scaling-ml-workflows-using-amazon-sagemaker-pipelines/)
This post focuses on using an MLOps template to bootstrap your ML project and establish a CI/CD pattern from sample code. We show how to use the built-in build, train, and deploy project template as a base for a customer churn classification example. This base template enables CI/CD for training ML models, registering model artifacts to the model registry, and automating model deployment with manual approval and automated testing.

\[Blog, 01/21\] [**Multi-account model deployment with Amazon SageMaker Pipelines**](https://aws.amazon.com/blogs/machine-learning/multi-account-model-deployment-with-amazon-sagemaker-pipelines/)
In this post, you learn how to use Pipelines to implement your own multi-account ML pipeline. First, you learn how to configure your environment and prepare it to use a predefined template as a SageMaker project for training and deploying a model in two different accounts: staging and production. Then, you see in detail how this custom template was created and how to create and customize templates for your own SageMaker projects.

\[Workshop, 01/21\] [**Launch Amazon SageMaker Studio using AWS Service Catalog and AWS SSO in AWS Control Tower Environment**](https://github.com/aws-samples/aws-service-catalog-sagemaker-studio-domain)
Workshop to launch Amazon SageMaker Studio domain using AWS Service Catalog and AWS SSO in the AWS Control Tower environment, using AWS CloudFormation templates and lambda functions.

\[Blog, 11/20\] [**Bringing your own custom container image to Amazon SageMaker Studio notebooks**](https://aws.amazon.com/blogs/machine-learning/bringing-your-own-custom-container-image-to-amazon-sagemaker-studio-notebooks/)
A step-by-step guide on creating a custom data science environment for SageMaker Studio using a Docker container.

### Security

\[Blog, 08/21\] [**Access an Amazon SageMaker Studio notebook from a corporate network**](https://aws.amazon.com/blogs/machine-learning/access-an-amazon-sagemaker-studio-notebook-from-a-corporate-network/)
Presigned URLs are commonly used to grant access to your Amazon SageMaker Studio domain to users within your organization. The use of public DNS for presigned URLs has a threat vector of undesired exposure. In this post, you can learn how to access a Studio notebook from a corporate network without traversing the internet to resolve the presigned URL domain name.

\[Blog, 07/21\] [**Setting up secure, well-governed machine learning environments on AWS**](https://aws.amazon.com/blogs/mt/setting-up-machine-learning-environments-aws/)
In this post, we’ll describe how you can organize, standardize, and expedite the provisioning of governed ML environments using recommended multi-account patterns on AWS.

\[Blog, 04/21\] [**Securing Amazon SageMaker Studio internet traffic using AWS Network Firewall**](https://aws.amazon.com/blogs/machine-learning/securing-amazon-sagemaker-studio-internet-traffic-using-aws-network-firewall/)
In this post, we show how you can use Network Firewall to build a secure and compliant environment by restricting and monitoring internet access, inspecting traffic, and using stateless and stateful firewall engine rules to control the network flow between Studio notebooks and the internet.

\[Blog, 02/21\] [**Building secure machine learning environments with Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/building-secure-machine-learning-environments-with-amazon-sagemaker/)
In this post, we introduce a series of hands-on workshops and associated code artifacts to help you build secure ML environments on top of Amazon SageMaker. These workshops are a summary of recommended practices from large enterprises and small and medium businesses.

\[Blog, 02/21\] [**Building secure Amazon SageMaker access URLs with AWS Service Catalog**](https://aws.amazon.com/blogs/mt/building-secure-amazon-sagemaker-access-urls-with-aws-service-catalog/)
In this blog post, we show you a how to connect to a private Amazon SageMaker notebook or Amazon SageMaker Studio without using the internet. For the purpose of this post, we provide a bastion host that emulates a VPN or similar connection. We provide all supporting code as AWS CloudFormation templates that can be easily deployed in an AWS account.

\[Blog, 01/21\] [**Hosting a private PyPI server for Amazon SageMaker Studio notebooks in a VPC**](https://aws.amazon.com/blogs/machine-learning/hosting-a-private-pypi-server-for-amazon-sagemaker-studio-notebooks-in-a-vpc/)
Detailed instructions for setting up a private PyPI server on an EC2 instance in a VPC and connecting to it from SageMaker Studio.

\[Blog, 12/20\] [**Controlling and auditing data exploration activities with Amazon SageMaker Studio and AWS Lake Formation**](https://aws.amazon.com/blogs/machine-learning/controlling-and-auditing-data-exploration-activities-with-amazon-sagemaker-studio-and-aws-lake-formation/)
Demonstrates how to use Studio roles and Lake Formation access control to create fine-grained data access permissions for different data scientists, along with logging of data access for audit purposes.

\[Blog, 11/20\] [**Private package installation in Amazon SageMaker running in internet-free mode**](https://aws.amazon.com/blogs/machine-learning/private-package-installation-in-amazon-sagemaker-running-in-internet-free-mode/)
Demonstrates how to set up a private package repository for both SageMaker notebooks and SageMaker Studio.

\[Blog, 11/20\] [**Configuring Amazon SageMaker Studio for teams and groups with complete resource isolation**](https://aws.amazon.com/blogs/machine-learning/configuring-amazon-sagemaker-studio-for-teams-and-groups-with-complete-resource-isolation/)
Shows how to configure access control for teams or groups within Amazon SageMaker Studio using attribute-based access control (ABAC).

\[Blog, 10/20\] [**Securing Amazon SageMaker Studio connectivity using a private VPC**](https://aws.amazon.com/blogs/machine-learning/securing-amazon-sagemaker-studio-connectivity-using-a-private-vpc/)
Detailed walkthrough for setting up SageMaker Studio with a VPC.

\[Blog, 08/20\] [**Machine learning best practices in financial services**](https://aws.amazon.com/blogs/machine-learning/machine-learning-best-practices-in-financial-services/)  
This blog accompanies a whitepaper with the same title. It provides guidance on security and model governance considerations for financial institutions, although this advice also applies to other industries.

\[Workshop, 2020\] **Amazon SageMaker: [Building Secure Environments](https://sagemaker-workshop.com/security_for_sysops.html) and [Using Secure Environments](https://sagemaker-workshop.com/security_for_users.html)**
This workshop walks the participant through the process of building and using secure environments with SageMaker, using Service Catalog, CloudFormation, and other AWS services. Related links: [GitHub](https://github.com/aws-samples/secure-data-science-reference-architecture)

\[Blog, 08/20\] [**Secure deployment of Amazon SageMaker resources**](https://aws.amazon.com/blogs/security/secure-deployment-of-amazon-sagemaker-resources/)
Provides details on several security features to use with SageMaker, including IAM, KMS, CloudFormation, Service Catalog, Lambda, and CloudWatch Events.

\[Whitepaper, 06/20\] [**Machine Learning Best Practices in Financial Services**](https://d1.awsstatic.com/whitepapers/machine-learning-in-financial-services-on-aws.pdf)
Provides guidance on security and model governance considerations for financial institutions, although this advice also applies to other industries.

\[Video, 05/20\] [**Secure and compliant machine learning workflows with Amazon SageMaker**](https://www.youtube.com/watch?v=HlSEUvApDZE&feature=youtu.be)
A video presentation on the topics covered in the whitepaper on Machine Learning for Financial Services.

\[Whitepaper, 04/20\] [**AWS Well-Architected Framework: Machine Learning Lens**](https://d1.awsstatic.com/whitepapers/architecture/wellarchitected-Machine-Learning-Lens.pdf)
A high-level overview of common ML scenarios and best practices for designing your ML workload.

\[Video, 06/19\] [**Building Secure Machine Learning Environments Using Amazon SageMaker - AWS Online Tech Talks**](https://www.youtube.com/watch?v=txr6CR87GXI&feature=youtu.be)
Covers various security features and best practices when using
SageMaker.

### Cost Control

\[Blog, 06/21\] [**Save costs by automatically shutting down idle resources within Amazon SageMaker Studio**](https://aws.amazon.com/blogs/machine-learning/save-costs-by-automatically-shutting-down-idle-resources-within-amazon-sagemaker-studio/)
In this post, learn how to detect and stop idle resources that are incurring costs within Amazon SageMaker Studio and Amazon SageMaker Data Wrangler using an auto-shutdown Jupyter extension.

\[Blog, 01/21\] [**Shutting down Amazon SageMaker Studio Apps on a scheduled basis with Amazon EventBridge, AWS Lambda, and Boto3**](https://sofian-hamiti.medium.com/shutting-down-amazon-sagemaker-studio-kernelgateways-automatically-with-aws-lambda-41e93afef06b)
Currently, although you can install the Sagemaker-Studio-Autoshutdown-Extension in Studio, the installation needs to be done for every user profile. This post shows how you can shut down all Studio Apps on your account on a scheduled basis with AWS Lambda and Amazon EventBridge.

\[Code Sample, 12/20\] [**Sagemaker-Studio-Autoshutdown-Extension**](https://github.com/aws-samples/sagemaker-studio-auto-shutdown-extension)
This JupyterLab extension automatically shuts down Kernels and Apps in Sagemaker Studio when they are idle for a stipulated period of time. You will be able to configure an idle time limit using the user interface this extension provides

\[Blog, 12/20\] [**Identify bottlenecks, improve resource utilization, and reduce ML training costs with the deep profiling feature in Amazon SageMaker Debugger**](https://aws.amazon.com/blogs/machine-learning/identify-bottlenecks-improve-resource-utilization-and-reduce-ml-training-costs-with-the-new-profiling-feature-in-amazon-sagemaker-debugger/)

\[Blog, 12/20\] [**Identifying training bottlenecks and system resource under-utilization with Amazon SageMaker Debugger**](https://aws.amazon.com/blogs/machine-learning/identifying-training-bottlenecks-and-system-resource-under-utilization-with-amazon-sagemaker-debugger/)
Shows how to use features from SageMaker Debugger to improve the utilization and cost control for training.

\[Blog, 10/20\] [**Optimizing costs for machine learning with Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/optimizing-costs-for-machine-learning-with-amazon-sagemaker/)
Provides best practices for using various SageMaker features to optimize the cost of your workload.

### Inference

\[Blog, 10/21\] [**Run computer vision inference on large videos with Amazon SageMaker asynchronous endpoints**](https://aws.amazon.com/blogs/machine-learning/run-computer-vision-inference-on-large-videos-with-amazon-sagemaker-asynchronous-endpoints/)
Customers are increasingly using computer vision models on large input payloads. These applications receive bursts of incoming traffic and require near-real-time processing. In this post, we show you how to serve a PyTorch CV model with SageMaker asynchronous inference to process a burst traffic of large input payload videos uploaded to Amazon S3.

\[Blog, 09/21\] [**Deploy multiple machine learning models for inference on AWS Lambda and Amazon EFS**](https://aws.amazon.com/blogs/machine-learning/deploy-multiple-machine-learning-models-for-inference-on-aws-lambda-and-amazon-efs/)
In this post, learn how to run an ML inference OCR application with a serverless, scalable, low-latency, and cost-effective architecture using AWS Lambda and Amazon EFS. You can extend this architecture to enable other ML use cases such as image classification, sentiment analysis, and search.

\[Blog, 08/21\] [**Deploy multiple serving containers on a single instance using Amazon SageMaker multi-container endpoints**](https://aws.amazon.com/blogs/machine-learning/deploy-multiple-serving-containers-on-a-single-instance-using-amazon-sagemaker-multi-container-endpoints/)
This post introduces SageMaker support for direct multi-container endpoints. This enables customers to run up to 15 different ML containers on a single endpoint and invoke them independently, thereby saving up to 90% in costs.

\[Blog, 06/21\] [**Build reusable, serverless inference functions for your Amazon SageMaker models using AWS Lambda layers and containers**](https://aws.amazon.com/blogs/machine-learning/build-reusable-serverless-inference-functions-for-your-amazon-sagemaker-models-using-aws-lambda-layers-and-containers/)
This post shows you how to use AWS Lambda to host an ML model for inference and explores several options to build layers and containers, including manually packaging and uploading a layer, and using AWS CloudFormation, AWS Serverless Application Model (AWS SAM), and containers.

\[Blog, 05/21\] [**Maximize TensorFlow performance on Amazon SageMaker endpoints for real-time inference**](https://aws.amazon.com/blogs/machine-learning/maximize-tensorflow-performance-on-amazon-sagemaker-endpoints-for-real-time-inference/)
In this post, we explored a few parameters that you can use to maximize the performance of a TensorFlow-based SageMaker real-time endpoint. These parameters are in essence overprovisioning serving processes and adjusting their parallel processing capabilities. As we saw in the tables, this overprovisioning and adjustment leads to better utilization of resources and higher throughput, sometimes an increase as much as 1,000%.

\[Blog, 02/21\] [**Using container images to run PyTorch models in AWS Lambda**](https://aws.amazon.com/blogs/machine-learning/using-container-images-to-run-pytorch-models-in-aws-lambda/)
This post shows you how to use any PyTorch model with Lambda for scalable inferences in production with up to 10 GB of memory. This allows us to use ML models in Lambda functions up to a few gigabytes. For the PyTorch example, we use the Huggingface Transformers, open-source library to build a question-answering endpoint.

### Clarify

\[Blog, 06/21\] [**ML model explainability with Amazon SageMaker Clarify and the SKLearn pre-built container**](https://aws.amazon.com/blogs/machine-learning/use-amazon-sagemaker-clarify-with-the-sklearn-pre-built-container/)
In this post, learn about explainability in ML models with Amazon SageMaker Clarify. You can use Clarify with the scikit-learn pre-built container.

\[Blog, 06/21\] [**Human-in-the-loop review of model explanations with Amazon SageMaker Clarify and Amazon A2I**](https://aws.amazon.com/blogs/machine-learning/human-in-the-loop-review-of-model-explanations-with-amazon-sagemaker-clarify-and-amazon-a2i/)
In this post, we use Amazon SageMaker Clarify to provide explanations of individual predictions and Amazon Augmented AI (Amazon A2I) to create a human-in-the-loop workflow and validate specific outcomes below a threshold on an income classification use case.

### Edge

\[Workshop, 09/21\] [**End-to-end AIoT w/ SageMaker and Greengrass 2.0 on NVIDIA Jetson Nano**](https://github.com/aws-samples/aiot-e2e-sagemaker-greengrass-v2-nvidia-jetson)
Hands-on lab from ML model training to model compilation to edge device model deployment on the AWS Cloud. It covers the detailed method of compiling SageMaker Neo for the target device, including cloud instance and edge device, and how to write and deploy Greengrass-v2 components from scratch.

\[Blog, 09/21\] [**Build machine learning at the edge applications using Amazon SageMaker Edge Manager and AWS IoT Greengrass V2**](https://aws.amazon.com/blogs/machine-learning/build-machine-learning-at-the-edge-applications-using-amazon-sagemaker-edge-manager-and-aws-iot-greengrass-v2/)
Running machine learning (ML) models at the edge can be a powerful enhancement for Internet of Things (IoT) solutions that must perform inference without a constant connection back to the cloud. Learn how to integrate Amazon SageMaker Edge Manager and AWS IoT Greengrass to build robust ML applications that are targeted specifically for edge use cases.

\[Code Sample, 05/21\] [**ML@Edge with SageMaker - Getting Started Examples**](https://github.com/aws-samples/ml-edge-getting-started)
This repository contains examples of different models, showing how they can be built using Amazon SageMaker and prepared for deployment at the edge.

### Other

\[Blog, 09/21\] [**Announcing the Amazon S3 plugin for PyTorch**](https://aws.amazon.com/blogs/machine-learning/announcing-the-amazon-s3-plugin-for-pytorch/)
Amazon S3 plugin for PyTorch is an open-source library which is built to be used with the deep learning framework PyTorch for streaming data from Amazon Simple Storage Service (Amazon S3). With this feature available in PyTorch Deep Learning Containers, you can take advantage of using data from S3 buckets directly with PyTorch dataset and dataloader APIs without needing to download it first on local storage.

\[Blog, 09/21\] [**Launch Amazon SageMaker Studio from external applications using presigned URLs**](https://aws.amazon.com/blogs/machine-learning/launch-amazon-sagemaker-studio-from-external-applications-using-presigned-urls/)
Using a presigned URL bypasses the console login, and allows you to open Amazon SageMaker Studio with just one click. In this post, learn how you can securely launch a Studio domain through a presigned URL by choosing a custom expiration time that can be as low as 5 seconds.

\[Blog, 08/21\] [**Dive deep into Amazon SageMaker Studio Notebooks architecture**](https://aws.amazon.com/blogs/machine-learning/dive-deep-into-amazon-sagemaker-studio-notebook-architecture/)
In this post, we take a closer look at how Studio notebooks have been designed to improve the productivity of data scientists and developers.

\[Blog, 08/21\] [**Run your TensorFlow job on Amazon SageMaker with a PyCharm IDE**](https://aws.amazon.com/blogs/machine-learning/run-your-tensorflow-job-on-amazon-sagemaker-with-a-pycharm-ide/)
In the post, learn how you can use SageMaker to manage your training jobs and experiments on AWS, using the Amazon SageMaker Python SDK with your local IDE.

\[Blog, 07/21\] [**Bring your own model with Amazon SageMaker script mode**](https://aws.amazon.com/blogs/machine-learning/bring-your-own-model-with-amazon-sagemaker-script-mode/)
In this post, we discuss three primary use cases for using script mode, and how script mode can accelerate your algorithm development and testing while simultaneously decreasing the amount of time, effort, and resources required to bring your custom algorithm to the cloud.

\[Blog, 05/21\] [**Creating an end-to-end application for orchestrating custom deep learning HPO, training, and inference using AWS Step Functions**](https://aws.amazon.com/blogs/machine-learning/orchestrate-custom-deep-learning-hpo-training-and-inference-using-aws-step-functions/)
Amazon SageMaker hyperparameter tuning provides a built-in solution for scalable training and hyperparameter optimization (HPO). However, for some applications (such as those with a preference of different HPO libraries or customized HPO features), we need custom machine learning (ML) solutions that allow retraining and HPO. This post offers a step-by-step guide to build a custom deep learning web application on AWS from scratch, following the Bring Your Own Container (BYOC) paradigm. We show you how to create a web application to enable non-technical end users to orchestrate different deep learning operations and perform advanced tasks such as HPO and retraining from a UI. You can modify the example solution to create a deep learning web application for any regression and classification problem.

\[Immersion Day, 04/21\] **Amazon Sagemaker Immersion Day**
\[[Website](https://sagemaker-immersionday.workshop.aws/)\]
\[[GitHub](https://github.com/aws-samples/amazon-sagemaker-immersion-day)\]
An Amazon SageMaker Immersion Day provides our customers with hands-on experience to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high quality models. It is specifically designed to help us accelerate a customer opportunity for Machine-learning workload in AWS.

\[Blog, 02/21\] [**Using genetic algorithms on AWS for optimization problems**](https://aws.amazon.com/blogs/machine-learning/using-genetic-algorithms-on-aws-for-optimization-problems/)
This post describes genetic algorithms (GAs) and demonstrates how to use them on AWS. GAs are unsupervised ML algorithms used to solve general types of optimization problems, including: 1) Optimal data orderings – Examples include creating work schedules, determining the best order to perform a set of tasks, or finding an optimal path through an environment, 2) Optimal data subsets – Examples include finding the best subset of products to include in a shipment, or determining which financial instruments to include in a portfolio, 3) Optimal data combinations – Examples include finding an optimal strategy for a task that is composed of many components, where each component is a choice of one of many options

\[Blog, 02/21\] [**Running multiple HPO jobs in parallel on Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/running-multiple-hpo-jobs-in-parallel-on-amazon-sagemaker/)
Amazon SageMaker provides a built-in HPO algorithm that removes the undifferentiated heavy lifting required to build your own HPO algorithm. This post shows how to batch your HPO jobs to maximize the number of jobs you can run in parallel, thereby reducing the total time it takes to effectively cover the desired parameter space and obtain the best-performing models.

\[Blog, 02/21\] [**Architect and build the full machine learning lifecycle with AWS: An end-to-end Amazon SageMaker demo**](https://aws.amazon.com/blogs/machine-learning/architect-and-build-the-full-machine-learning-lifecycle-with-amazon-sagemaker/)
In this tutorial, we will walk through the entire machine learning (ML) lifecycle and show you how to architect and build an ML use case end to end using Amazon SageMaker. Amazon SageMaker provides a rich set of capabilities that enable data scientists, machine learning engineers, and developers to prepare, build, train, and deploy ML models rapidly and with ease. For our use case, we have chosen an automobile claims fraud detection example.

\[Blog, 05/21\] [**Speed up YOLOv4 inference to twice as fast on Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/speed-up-yolov4-inference-to-twice-as-fast-on-amazon-sagemaker/)
In this post, we show you how to deploy a PyTorch YOLOv4 model on a SageMaker ML CPU-based instance. You download a pre-trained model artifact, compile your pre-trained model using Neo, set up a SageMaker endpoint for both compiled and uncompiled model versions, and benchmark performance to evaluate latency, comparing a compiled and uncompiled YOLOv4 model on the same instance.

\[Blog, 03/20\] [**Creating a machine learning-powered REST API with Amazon API Gateway mapping templates and Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/creating-a-machine-learning-powered-rest-api-with-amazon-api-gateway-mapping-templates-and-amazon-sagemaker/)
In this post, I show how API Gateway can be used to front an Amazon SageMaker inference endpoint as (part of) a REST API, by making use of an API Gateway feature called mapping templates. This feature makes it possible for the REST API to be integrated directly with an Amazon SageMaker runtime endpoint, thereby avoiding the use of any intermediate compute resource (such as AWS Lambda or Amazon ECS containers) to invoke the endpoint. The result is a solution that is simpler, faster, and cheaper to run.

---
## Amazon Personalize

\[Blog, 08/21\] [**Optimize personalized recommendations for a business metric of your choice with Amazon Personalize**](https://aws.amazon.com/blogs/machine-learning/optimize-personalized-recommendations-for-a-business-metric-of-your-choice-with-amazon-personalize/)
Amazon Personalize now enables customers to optimize personalized recommendations for a business metric of choice such as revenue, profit margin, video watch time, or any other numerical attribute to optimize their recommendations.

\[Blog, 07/21\] [**Unlock information in unstructured text to personalize product and content recommendations with Amazon Personalize**](https://aws.amazon.com/blogs/machine-learning/unlock-information-in-unstructured-text-to-personalize-product-and-content-recommendations-with-amazon-personalize/)
This post shows you how to include unstructured text when using Amazon Personalize and the impact it can have on the relevance of the recommendations you generate with the service.

\[Blog, 07/21\] [**Use contextual information and third party data to improve your recommendations**](https://aws.amazon.com/blogs/machine-learning/use-contextual-information-and-third-party-data-to-improve-your-recommendations/)
In this post, we share a hands-on approach to include context when generating recommendations, by using data from our partners in the AWS Data Exchange. For this example, we use a subset of the temperatures and precipitation dataset provided by Weather Trends International, combined with a fictitious dataset representing a bottler company beverage catalog and a user demo dataset from the Retail Demo Store

\[Blog, 04/21\] [**Scale session-aware real-time product recommendations on Shopify with Amazon Personalize and Amazon EventBridge**](https://aws.amazon.com/blogs/machine-learning/scale-session-aware-real-time-product-recommendations-on-shopify-with-amazon-personalize-and-amazon-eventbridge/)
In this post, we describe the architectures used in our application for serving recommendations as well as synchronizing events and catalog updates in real time. We also share some of the results for session-based personalization from a customer using the application.

\[Immersion Day, 02/21\] [**Amazon Personalize Immersion Day**](https://immersionday.com/amazon-personalize-immersion-day/)
This Immersion Day offers a deep-dive on Amazon Personalize, with a collection driven by hands-on labs based on specific domains (M&E, Retail, and CPG).

\[Videos, 12/20\] [**Amazon Personalize Deep Dive Series**](https://www.youtube.com/playlist?list=PLhr1KZpdzukd9GSGRy329wahNO_8TkRo_)
In this video series you will get an introduction to Amazon Personalize and dive deeper into topics related to data, training, inference, and operations.

\[Tool, 12/20\] [**Amazon Personalize Monitor**](https://github.com/aws-samples/amazon-personalize-monitor)
This project contains the source code and supporting files for deploying a serverless application that adds monitoring, alerting, and optimization capabilities for Amazon Personalize.