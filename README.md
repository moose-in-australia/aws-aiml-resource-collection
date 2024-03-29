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
- [Amazon Forecast](#amazon-forecast)
- [Amazon Fraud Detector](#amazon-fraud-detector)
- [Amazon Kendra](#amazon-kendra)
- [Amazon Lex](#amazon-lex)
- [Amazon Lookout for Metrics](#amazon-lookout-for-metrics)
- [AWS Panorama](#aws-panorama)
- [Amazon Personalize](#amazon-personalize)
- [Amazon Rekognition](#amazon-rekognition)
- [Amazon Textract](#amazon-textract)
- [Amazon Transcribe](#amazon-transcribe)
- [Amazon Translate](#amazon-translate)
- [Sustainability](#sustainability)

---
## Amazon SageMaker

### MLOps

* [Blog](#mlops-blog)
* [Code Sample](#mlops-code-sample)
* [Solution](#mlops-solution)
* [Video](#mlops-video)
* [Whitepaper](#mlops-whitepaper)
* [Workshop](#mlops-workshop)

#### MLOps Blog

\[Blog, 07/22\] [**Track your ML experiments end to end with Data Version Control and Amazon SageMaker Experiments**](https://aws.amazon.com/blogs/machine-learning/track-your-ml-experiments-end-to-end-with-data-version-control-and-amazon-sagemaker-experiments/)
This post walks you through an example of how to track your experiments across code, data, artifacts, and metrics by using Amazon SageMaker Experiments in conjunction with Data Version Control (DVC). We show how you can use DVC side by side with Amazon SageMaker processing and training jobs.

\[Blog, 06/22\] [**MLOps foundation roadmap for enterprises with Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/mlops-foundation-roadmap-for-enterprises-with-amazon-sagemaker/)
In this post, you learn about the key phases of building an MLOps foundations, how multiple personas work together on this foundation, and the Amazon SageMaker purpose-built tools and built-in integrations with other AWS services that can accelerate the adoption of ML across an enterprise business.

\[Blog, 06/22\] [**Improve ML developer productivity with Weights & Biases: A computer vision example on Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/improve-ml-developer-productivity-with-weights-biases-a-computer-vision-example-on-amazon-sagemaker/)
In this post, we train a model to identify objects for an autonomous vehicle use case using Weights & Biases (W&B) and Amazon SageMaker. We showcase how the joint solution reduces manual work for the ML developer, creates more transparency in the model development process, and enables teams to collaborate on projects.

\[Blog, 06/22\] [**Automate vending Amazon SageMaker notebooks with Amazon EventBridge and AWS Lambda**](https://aws.amazon.com/blogs/machine-learning/automate-vending-amazon-sagemaker-notebooks-with-amazon-eventbridge-and-aws-lambda/)
This post demonstrates how to centralize the management of SageMaker instance notebooks using AWS services including AWS CloudFormation, AWS Serverless Application Model (AWS SAM), AWS Service Catalog, Amazon EventBridge, AWS Systems Manager Parameter Store, Amazon API Gateway, and AWS Lambda. We walk through how to use these AWS services to automate the process of vending SageMaker notebooks to end-users.

\[Blog, 06/22\] [**Control access to Amazon SageMaker Feature Store offline using AWS Lake Formation**](https://aws.amazon.com/blogs/machine-learning/control-access-to-amazon-sagemaker-feature-store-offline-using-aws-lake-formation/)
In this post, we provide an overview of how to implement granular access control to feature groups and features stored in an offline feature store using Amazon SageMaker Feature Store and AWS Lake Formation.

\[Blog, 05/22\] [**How to Create Reusable R Containers for SageMaker Jobs**](https://towardsdatascience.com/how-to-create-reusable-r-containers-for-sagemaker-jobs-a3d481daf5cd)
SageMaker is famous for its flexibility and python support but it is not always straightforward to use for other programming languages. This guide can help your customers create reusable R containers for all their R needs. 

\[Blog, 04/22\] **How NatWest Group built a scalable, secure, and sustainable MLOps platform [(Part 1)](https://aws.amazon.com/blogs/machine-learning/part-1-how-natwest-group-built-a-scalable-secure-and-sustainable-mlops-platform/) [(Part 2)](https://aws.amazon.com/blogs/machine-learning/part-2-how-natwest-group-built-a-secure-compliant-self-service-mlops-platform-using-aws-service-catalog-and-amazon-sagemaker/) [(Part 3)](https://aws.amazon.com/blogs/machine-learning/part-3-how-natwest-group-built-auditable-reproducible-and-explainable-ml-models-with-amazon-sagemaker/) [(Part 4)](https://aws.amazon.com/blogs/machine-learning/part-4-how-natwest-group-migrated-ml-models-to-amazon-sagemaker-architectures/)**
This is a four-part series detailing how NatWest Group, a major financial services institution, partnered with AWS to build a scalable, secure, and sustainable machine learning operations (MLOps) platform. 

\[Blog, 02/22\] [**Implement MLOps using AWS pre-trained AI Services with AWS Organizations**](https://aws.amazon.com/blogs/machine-learning/implement-mlops-using-aws-pre-trained-ai-services-with-aws-organizations/)
The AWS Machine Learning Operations (MLOps) framework is an iterative and repetitive process for evolving AI models over time. Like DevOps, practitioners gain efficiencies promoting their artifacts through various environments (such as quality assurance, integration, and production) for quality control. In parallel, customers rapidly adopt multi-account strategies through AWS Organizations and AWS Control Tower to create secure, isolated environments. This combination can introduce challenges for implementing MLOps with AWS pre-trained AI Services, such as Amazon Rekognition Custom Labels. This post discusses design patterns for reducing that complexity while still maintaining security best practices.

\[Blog, 03/22\] [**Enhance your SaaS offering with a data science workbench powered by Amazon SageMaker Studio**](https://aws.amazon.com/blogs/machine-learning/enhance-your-saas-offering-with-a-data-science-workbench-powered-by-amazon-sagemaker-studio/)
Many software as a service (SaaS) providers across various industries are adding machine learning (ML) and artificial intelligence (AI) capabilities to their SaaS offerings to address use cases like personalized product recommendation, fraud detection, and accurate demand protection. Some SaaS providers want to build such ML and AI capabilities themselves and deploy them in a multi-tenant environment. However, others who have more advanced customers want to allow their customers to build ML models themselves and use them to augment the SaaS with additional capabilities or override the default implementation of certain functionality. In this post, we discuss how to enhance your SaaS offering with a data science workbench powered by Amazon SageMaker Studio.

\[Blog, 01/22\] [**Detect NLP data drift using custom Amazon SageMaker Model Monitor**](https://aws.amazon.com/blogs/machine-learning/detect-nlp-data-drift-using-custom-amazon-sagemaker-model-monitor/)
In this post, we discuss the types of data quality drift that are applicable to text data. We also present an approach to detecting data drift in text data using Model Monitor.

\[Blog, 01/22\] [**Take advantage of advanced deployment strategies using Amazon SageMaker deployment guardrails**](https://aws.amazon.com/blogs/machine-learning/take-advantage-of-advanced-deployment-strategies-using-amazon-sagemaker-deployment-guardrails/)
In this post, we show you how to use the new deployment guardrail capabilities to deploy your model versions using both a canary and linear deployment strategy.

\[Blog, 11/21\] [**Design a compelling record filtering method with Amazon SageMaker Model Monitor**](https://aws.amazon.com/blogs/machine-learning/design-a-compelling-record-filtering-method-with-amazon-sagemaker-model-monitor/)
In this post, we present how to build a record filtering method based on sets of business criteria as part of the preprocessing step in Model Monitor. The goal is to ensure that only the actual production records are sent to Model Monitor for analysis, reflecting the actual usage of the production endpoint.

\[Blog, 11/21\] [**Automate model retraining with Amazon SageMaker Pipelines when drift is detected**](https://aws.amazon.com/blogs/machine-learning/automate-model-retraining-with-amazon-sagemaker-pipelines-when-drift-is-detected/)
Training your machine learning (ML) model and serving predictions is usually not the end of the ML project. The accuracy of ML models can deteriorate over time, a phenomenon known as model drift. Many factors can cause model drift, such as changes in model features. The accuracy of ML models can also be affected by concept drift, the difference between data used to train models and data used during inference. In this post, we discuss how to automate retraining with pipelines in SageMaker when model drift is detected.

\[Blog, 10/21\] [**Enhance your machine learning development by using a modular architecture with Amazon SageMaker projects**](https://aws.amazon.com/blogs/machine-learning/enhance-your-machine-learning-development-by-using-a-modular-architecture-with-amazon-sagemaker-projects/)
This post walks you through the implementation of a custom SageMaker project. We discuss how to do the following: Create a project with your resources, Understand the project lifecycle, View project resources, Create a Studio domain and deploy a product portfolio, Work with the project and run a data transformation and ingestion pipeline

\[Blog, 10/21\] [**Build Custom SageMaker Project Templates – Best Practices**](https://aws.amazon.com/blogs/machine-learning/build-custom-sagemaker-project-templates-best-practices/)
SageMaker Projects give organizations the ability to easily setup and standardize developer environments for data scientists and CI/CD systems for MLOps Engineers. This post describes how SageMaker Project templates can be customized to fit any organization’s use case.

\[Blog, 10/21\] [**Industrializing an ML platform with Amazon SageMaker Studio**](https://towardsdatascience.com/industrializing-an-ml-platform-with-amazon-sagemaker-studio-91b597802afe)
Overview of steps and considerations when setting up Amazon SageMaker Studio as your ML platform. Contains many links to other, more detailed resources. 

\[Blog, 10/21\] [**Create a cross-account machine learning training and deployment environment with AWS Code Pipeline**](https://aws.amazon.com/blogs/machine-learning/create-a-cross-account-machine-learning-training-and-deployment-environment-with-aws-code-pipeline/)
A CI/CD pipeline helps you automate steps in your ML applications and improves security, agility and resilience. In this post, learn how to set up the right cross-accounts IAM roles and trust relationships to create a cross-account pipeline while encrypting your central ML artifact store. Read this if you want to understand how to manually set up an environment similar to SageMaker Projects.

\[Blog, 09/21\] [**Customize Amazon SageMaker Studio using Lifecycle Configurations**](https://aws.amazon.com/blogs/machine-learning/customize-amazon-sagemaker-studio-using-lifecycle-configurations/)
Previously, customizations to Amazon SageMaker Studio environments were possible but needed to be reapplied manually every time apps were deleted or recreated. We’re excited to announce Lifecycle Configuration for Studio, a new capability that enables developers to automate customization for your Studio development environments.

\[Blog, 09/21\] [**Model and data lineage in machine learning experimentation**](https://aws.amazon.com/blogs/machine-learning/model-and-data-lineage-in-machine-learning-experimentation/)
Reproducibility in the ML research space is a challenging and multi-faceted topic, and quantitative finance is a prominent use case. By working with our customers across industry verticals, AWS is leading the way towards a holistic solution set in this field.

\[Blog, 09/21\] [**Scale ML feature ingestion using Amazon SageMaker Feature Store**](https://aws.amazon.com/blogs/machine-learning/scale-ml-feature-ingestion-using-amazon-sagemaker-feature-store/)
In this post, we provide an overview of ingestion options for Feature Store, and the benefits and use cases for each one. We also provide a GitHub repo that demonstrates several of these approaches, so you can try them out in your own AWS account.

\[Blog, 09/21\] [**Define and run Machine Learning pipelines on Step Functions using Python, Workflow Studio, or States Language**](https://aws.amazon.com/blogs/machine-learning/define-and-run-machine-learning-pipelines-on-step-functions-using-python-workflow-studio-or-states-language/)
In this post, we discuss how to author end-to-end ML pipelines in Step Functions using Python, drag and drop (using the new Step Functions Workflow Studio) and JSON.

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

\[Blog, 05/21\] [**Automating the Setup of SageMaker Studio Custom Images**](https://towardsdatascience.com/automating-the-setup-of-sagemaker-studio-custom-images-4a3433fd7148)
In most large enterprises, ML platform administrators will manage those custom images to ensure only approved libraries are used by the Studio users. This can represent operational overhead for admins, if done manually. In this post I show how you can implement simple continuous delivery for Studio custom images to automate your Studio domain setup.

\[Blog, 04/21\] [**Ingesting Historical Feature Data into SageMaker Feature Store**](https://towardsdatascience.com/ingesting-historical-feature-data-into-sagemaker-feature-store-5618e41a11e6#f950-d5882f6deacb) & [**Q&A for Ingesting Historical Data into SageMaker Feature Store**](https://towardsdatascience.com/q-a-for-ingesting-historical-data-into-sagemaker-feature-store-239e918ec594)
How to backfill the SageMaker Offline Feature Store by writing directly into S3.

\[Blog, 03/21\] [**Enable feature reuse across accounts and teams using Amazon SageMaker Feature Store**](https://aws.amazon.com/blogs/machine-learning/enable-feature-reuse-across-accounts-and-teams-using-amazon-sagemaker-feature-store/)
This post captures the essential cross-account architecture patterns for Feature Store that can be implemented in an organization with many data engineering and data science teams operating in different AWS accounts.

\[Blog, 01/21\] [**Managing your machine learning lifecycle with MLflow and Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/managing-your-machine-learning-lifecycle-with-mlflow-and-amazon-sagemaker/)
During the initial phase of an ML project, data scientists collaborate and share experiment results in order to find a solution to a business need. During the operational phase, you also need to manage the different model versions going to production and your lifecycle. In this post, we’ll show how the open-source platform MLflow helps address these issues.

\[Blog, 01/21\] [**Building, automating, managing, and scaling ML workflows using Amazon SageMaker Pipelines**](https://aws.amazon.com/blogs/machine-learning/building-automating-managing-and-scaling-ml-workflows-using-amazon-sagemaker-pipelines/)
This post focuses on using an MLOps template to bootstrap your ML project and establish a CI/CD pattern from sample code. We show how to use the built-in build, train, and deploy project template as a base for a customer churn classification example. This base template enables CI/CD for training ML models, registering model artifacts to the model registry, and automating model deployment with manual approval and automated testing.

\[Blog, 01/21\] [**Multi-account model deployment with Amazon SageMaker Pipelines**](https://aws.amazon.com/blogs/machine-learning/multi-account-model-deployment-with-amazon-sagemaker-pipelines/)
In this post, you learn how to use Pipelines to implement your own multi-account ML pipeline. First, you learn how to configure your environment and prepare it to use a predefined template as a SageMaker project for training and deploying a model in two different accounts: staging and production. Then, you see in detail how this custom template was created and how to create and customize templates for your own SageMaker projects.

\[Blog, 11/20\] [**Bringing your own custom container image to Amazon SageMaker Studio notebooks**](https://aws.amazon.com/blogs/machine-learning/bringing-your-own-custom-container-image-to-amazon-sagemaker-studio-notebooks/)
A step-by-step guide on creating a custom data science environment for SageMaker Studio using a Docker container.

#### MLOps Code Sample

\[Code Sample, 02/22\] [**MLflow (Open Machine Learning Platform) on AWS**](https://github.com/aws-samples/aws-mlflow-sagemaker-cdk)
In this project, we show how to deploy MLflow on AWS Fargate with basic authentication and use it during your ML project with Amazon SageMaker.

\[Code Sample, 02/21\] [**SageMaker custom studio image providing magic cells for a simplified experience in a notebook**](https://github.com/aws-samples/sagemaker-studio-notebook-magic-cell)
This solution provides a magic cell for a Jupyter Notebook to simplify the SageMaker training and SageMaker processing function by customizing a kernel and using Bring-Your-Own Image in SageMaker Studio.

#### MLOps Solution

\[Solution, 08/21\] [**AWS MLOps Framework**](https://aws.amazon.com/solutions/implementations/aws-mlops-framework/?did=sl_card&trk=sl_card)
The AWS MLOps Framework solution helps you streamline and enforce architecture best practices for machine learning (ML) model productionization. This solution is an extendable framework that provides a standard interface for managing ML pipelines for AWS ML services and third-party services. The solution’s template allows customers to upload their trained models (also referred to as bring your own model), configure the orchestration of the pipeline, and monitor the pipeline's operations. This solution increases your team’s agility and efficiency by allowing them to repeat successful processes at scale.

\[Solution, 01/21\] [**Amazon SageMaker with Guardrails on AWS**](https://aws.amazon.com/quickstart/architecture/amazon-sagemaker-with-guardrails/)
This Quick Start deployment of Amazon SageMaker adds guardrails so you can build, train, and deploy machine learning (ML) models in a more secure environment. Guardrails are high-level rules that provide ongoing governance for your overall AWS environment. AWS provides additional security by using AWS PrivateLink, Amazon CloudWatch, AWS Identity and Access Management (IAM), AWS Key Management Service (AWS KMS), and other native services.

#### MLOps Video

\[Video, 08/21\] [**Implement MLOps practices with Amazon SageMaker**](https://www.youtube.com/watch?v=iNoeULI7nB4)
MLOps practices help data scientists and IT operations professionals collaborate and manage the production ML workflow, including data preparation and building, training, deploying, and monitoring models. This session explores the breadth of features in Amazon SageMaker that help you increase automation and improve the quality of your end-to-end workflows.

#### MLOps Whitepaper

\[Whitepaper, 09/21\] [**Machine Learning Best Practices
for Public Sector Organizations**](https://d1.awsstatic.com/whitepapers/machine-learning-best-practices-for-public-sector-organizations.pdf)
This whitepaper outlines some of the challenges for US public sector agencies in adoption and implementation of ML, and provides best practices to address these challenges. The target audience for this whitepaper includes executive leaders and agency IT Directors. 

\[Whitepaper, 05/21\] [**Build a Secure Enterprise Machine Learning Platform on AWS**](https://docs.aws.amazon.com/whitepapers/latest/build-secure-enterprise-ml-platform/build-secure-enterprise-ml-platform.html?did)
This whitepaper helps cloud engineers, security engineers, Machine Learning Ops (MLOps) engineers, and data scientists understand the various components of building a secure enterprise machine learning (ML) platform. It provides prescriptive guidance on building a secure ML platform on Amazon Web Services (AWS).

#### MLOps Workshop

\[Workshop, 09/21\] [**SageMaker Feature Store Workshop**](https://github.com/aws-samples/amazon-sagemaker-feature-store-end-to-end-workshop)
GitHub repo forms the basis of this workshop demonstrating SageMaker Feature Store, showing end-to-end examples. Multiple notebooks walk the user through feature group creation, single and parallel ingest, model training and hosting, plus Data Wrangler integration to feature store. The sample shows how to trigger SageMaker Pipelines from S3 file event.

\[Workshop, 01/21\] [**Launch Amazon SageMaker Studio using AWS Service Catalog and AWS SSO in AWS Control Tower Environment**](https://github.com/aws-samples/aws-service-catalog-sagemaker-studio-domain)
Workshop to launch Amazon SageMaker Studio domain using AWS Service Catalog and AWS SSO in the AWS Control Tower environment, using AWS CloudFormation templates and lambda functions.

### Security

* [Blog](#security-blog)
* [Video](#security-video)
* [Whitepaper](#security-whitepaper)
* [Workshop](#security-workshop)

#### Security Blog

\[Blog, 06/22\] **Secure Amazon SageMaker Studio presigned URLs Part 1: Foundational infrastructure** ([**Part 1**](https://aws.amazon.com/blogs/machine-learning/secure-amazon-sagemaker-studio-presigned-urls-part-1-foundational-infrastructure/)) ([**Part 2**](https://aws.amazon.com/blogs/machine-learning/secure-amazon-sagemaker-studio-presigned-urls-part-2-private-api-with-jwt-authentication/))
You can access Amazon SageMaker Studio notebooks from the Amazon SageMaker console via AWS Identity and Access Management (IAM) authenticated federation from your identity provider (IdP), such as Okta. When a Studio user opens the notebook link, Studio validates the federated user’s IAM policy to authorize access, and generates and resolves the presigned URL for the user. These posts describe how to secure these presigned URLs.

\[Blog, 06/22\] [**Amazon SageMaker Notebook Instances now support configuring and restricting IMDS versions**](https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-notebook-instances-now-support-configuring-and-restricting-imds-versions/)
In this post, we show you how to configure your SageMaker notebooks with IMDSv2 only support. We also share the support plan for IMDSv1, and how you can enforce IMDSv2 on your notebooks.

\[Blog, 04/22\] [**Secure AWS CodeArtifact access for isolated Amazon SageMaker notebook instances**](https://aws.amazon.com/blogs/machine-learning/secure-aws-codeartifact-access-for-isolated-amazon-sagemaker-notebook-instances/)
In this post, we demonstrate how to securely connect to AWS CodeArtifact from an Internet-disabled SageMaker Notebook Instance. This post is for network and security architects that support decentralized data science teams on AWS.

\[Blog, 03/22\] [**Secure Amazon S3 access for isolated Amazon SageMaker notebook instances**](https://aws.amazon.com/blogs/machine-learning/secure-amazon-s3-access-for-isolated-amazon-sagemaker-notebook-instances/)
In this post, we will demonstrate how to securely launch notebook instances in a private subnet of an Amazon Virtual Private Cloud (Amazon VPC), with internet access disabled, and to securely connect to Amazon Simple Storage Service (Amazon S3) using VPC endpoints. This post is for network and security architects that support decentralized data science teams on AWS.

\[Blog, 01/22\] [**Secure access to Amazon SageMaker Studio with AWS SSO and a SAML application**](https://aws.amazon.com/blogs/machine-learning/secure-access-to-amazon-sagemaker-studio-with-aws-sso-and-a-saml-application/)
A popular use case is to restrict access to the Studio IDE to only users from inside a specified network CIDR range or a designated VPC. Many customers use AWS SSO to enable centralized workforce identity control and provide a consistent user sign-in experience. This post shows how to implement this use case while keeping AWS SSO capabilities to access Studio.

\[Blog, 11/21\] [**Implementing SaaS Tenant Isolation Using Amazon SageMaker Endpoints and IAM**](https://aws.amazon.com/blogs/apn/implementing-saas-tenant-isolation-using-amazon-sagemaker-endpoints-and-iam/)
In this post, we’ll focus on how tenant isolation of machine learning services can be achieved using AWS Identity and Access Management (IAM). We’ll look at how the integration between IAM, Amazon SageMaker, and many other AWS services provide developers with a rich set of mechanisms that can be applied to realize tenant isolation goals.

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

\[Blog, 08/20\] [**Secure deployment of Amazon SageMaker resources**](https://aws.amazon.com/blogs/security/secure-deployment-of-amazon-sagemaker-resources/)
Provides details on several security features to use with SageMaker, including IAM, KMS, CloudFormation, Service Catalog, Lambda, and CloudWatch Events.

#### Security Video

\[Video, 05/20\] [**Secure and compliant machine learning workflows with Amazon SageMaker**](https://www.youtube.com/watch?v=HlSEUvApDZE&feature=youtu.be)
A video presentation on the topics covered in the whitepaper on Machine Learning for Financial Services.

\[Video, 06/19\] [**Building Secure Machine Learning Environments Using Amazon SageMaker - AWS Online Tech Talks**](https://www.youtube.com/watch?v=txr6CR87GXI&feature=youtu.be)
Covers various security features and best practices when using
SageMaker.

#### Security Whitepaper

\[Whitepaper, 11/21\] [**Machine Learning Best Practices in Healthcare and Life Sciences**](https://docs.aws.amazon.com/whitepapers/latest/ml-best-practices-healthcare-life-sciences/ml-best-practices-healthcare-life-sciences.html)
This whitepaper describes how AWS approaches machine learning (ML) in a regulated environment and provides guidance on good ML practices using AWS products. This whitepaper takes into consideration the principles described in the Proposed Regulatory Framework for Modifications to Artificial Intelligence/Machine Learning (AI/ML)-Based Software as a Medical Device (SaMD discussion paper. 

\[Whitepaper, 10/21\] [**AWS Well-Architected Framework: Machine Learning Lens**](https://docs.aws.amazon.com/wellarchitected/latest/machine-learning-lens/machine-learning-lens.html)
This whitepaper provides you with a set of established cloud and technology agnostic best practices. You can apply this guidance and architectural principles when designing your ML workloads, or after your workloads have entered production as part of continuous improvement. The paper includes guidance and resources to help you implement these best practices on AWS. 

\[Whitepaper, 06/20\] [**Machine Learning Best Practices in Financial Services**](https://d1.awsstatic.com/whitepapers/machine-learning-in-financial-services-on-aws.pdf)
Provides guidance on security and model governance considerations for financial institutions, although this advice also applies to other industries.

#### Security Workshop

\[Workshop, 2020\] **Amazon SageMaker: [Building Secure Environments](https://sagemaker-workshop.com/security_for_sysops.html) and [Using Secure Environments](https://sagemaker-workshop.com/security_for_users.html)**
This workshop walks the participant through the process of building and using secure environments with SageMaker, using Service Catalog, CloudFormation, and other AWS services. Related links: [GitHub](https://github.com/aws-samples/secure-data-science-reference-architecture)

### Cost Control

* [Blog](#cost-control-blog)
* [Code Sample](#cost-control-code-sample)

#### Cost Control Blog

\[Blog, 02/22\] [**Reduce costs and complexity of ML preprocessing with Amazon S3 Object Lambda**](https://aws.amazon.com/blogs/machine-learning/reduce-costs-and-complexity-of-ml-preprocessing-with-amazon-s3-object-lambda/)
This post demonstrates a design pattern for reducing costs, complexity, and centrally managing preprocessing. It uses the concrete example of image processing, though the approach broadly applies to any workload. The economic benefits are also most pronounced when the transformation step doesn’t require GPU, but the AI algorithm does.

\[Blog, 06/21\] [**Save costs by automatically shutting down idle resources within Amazon SageMaker Studio**](https://aws.amazon.com/blogs/machine-learning/save-costs-by-automatically-shutting-down-idle-resources-within-amazon-sagemaker-studio/)
In this post, learn how to detect and stop idle resources that are incurring costs within Amazon SageMaker Studio and Amazon SageMaker Data Wrangler using an auto-shutdown Jupyter extension.

\[Blog, 01/21\] [**Shutting down Amazon SageMaker Studio Apps on a scheduled basis with Amazon EventBridge, AWS Lambda, and Boto3**](https://sofian-hamiti.medium.com/shutting-down-amazon-sagemaker-studio-kernelgateways-automatically-with-aws-lambda-41e93afef06b)
Currently, although you can install the Sagemaker-Studio-Autoshutdown-Extension in Studio, the installation needs to be done for every user profile. This post shows how you can shut down all Studio Apps on your account on a scheduled basis with AWS Lambda and Amazon EventBridge.

\[Blog, 12/20\] [**Identify bottlenecks, improve resource utilization, and reduce ML training costs with the deep profiling feature in Amazon SageMaker Debugger**](https://aws.amazon.com/blogs/machine-learning/identify-bottlenecks-improve-resource-utilization-and-reduce-ml-training-costs-with-the-new-profiling-feature-in-amazon-sagemaker-debugger/)

\[Blog, 12/20\] [**Identifying training bottlenecks and system resource under-utilization with Amazon SageMaker Debugger**](https://aws.amazon.com/blogs/machine-learning/identifying-training-bottlenecks-and-system-resource-under-utilization-with-amazon-sagemaker-debugger/)
Shows how to use features from SageMaker Debugger to improve the utilization and cost control for training.

\[Blog, 10/20\] [**Optimizing costs for machine learning with Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/optimizing-costs-for-machine-learning-with-amazon-sagemaker/)
Provides best practices for using various SageMaker features to optimize the cost of your workload.

#### Cost Control Code Sample

\[Code Sample, 12/20\] [**Sagemaker-Studio-Autoshutdown-Extension**](https://github.com/aws-samples/sagemaker-studio-auto-shutdown-extension)
This JupyterLab extension automatically shuts down Kernels and Apps in Sagemaker Studio when they are idle for a stipulated period of time. You will be able to configure an idle time limit using the user interface this extension provides

### Inference

\[Blog, 05/22\] [**Achieve hyperscale performance for model serving using NVIDIA Triton Inference Server on Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/achieve-hyperscale-performance-for-model-serving-using-nvidia-triton-inference-server-on-amazon-sagemaker/)
In this post, we look at best practices for deploying transformer models at scale on GPUs using Triton Inference Server on SageMaker. First, we start with a summary of key concepts around latency in SageMaker, and an overview of performance tuning guidelines. Next, we provide an overview of Triton and its features as well as example code for deploying on SageMaker. Finally, we perform load tests using SageMaker Inference Recommender and summarize the insights and conclusions from load testing of a popular transformer model provided by Hugging Face.

\[Blog, 04/22\] [**Host Hugging Face transformer models using Amazon SageMaker Serverless Inference**](https://aws.amazon.com/blogs/machine-learning/host-hugging-face-transformer-models-using-amazon-sagemaker-serverless-inference/)
In this post, we explore how to use SageMaker Serverless Inference to deploy Hugging Face transformer models and discuss the inference performance and cost-effectiveness in different scenarios.

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

### Responsible AI

* [Blog](#responsible-ai-blog)
* [Whitepaper](#responsible-ai-whitepaper)

#### Responsible AI Blog

\[Blog, 06/21\] [**ML model explainability with Amazon SageMaker Clarify and the SKLearn pre-built container**](https://aws.amazon.com/blogs/machine-learning/use-amazon-sagemaker-clarify-with-the-sklearn-pre-built-container/)
In this post, learn about explainability in ML models with Amazon SageMaker Clarify. You can use Clarify with the scikit-learn pre-built container.

\[Blog, 06/21\] [**Human-in-the-loop review of model explanations with Amazon SageMaker Clarify and Amazon A2I**](https://aws.amazon.com/blogs/machine-learning/human-in-the-loop-review-of-model-explanations-with-amazon-sagemaker-clarify-and-amazon-a2i/)
In this post, we use Amazon SageMaker Clarify to provide explanations of individual predictions and Amazon Augmented AI (Amazon A2I) to create a human-in-the-loop workflow and validate specific outcomes below a threshold on an income classification use case.

#### Responsible AI Whitepaper

\[Whitepaper, 04/22\] [**Amazon AI Fairness and Explainability Whitepaper**](https://pages.awscloud.com/rs/112-TZM-766/images/Amazon.AI.Fairness.and.Explainability.Whitepaper.pdf)
This whitepaper is a technical reference for AWS customers who use features from Amazon SageMaker Clarify to help identify potential bias in machine learning models and to help explain how these models make predictions.

\[Whitepaper, 04/22\] [**Responsible Use of Machine Learning**](https://d1.awsstatic.com/responsible-machine-learning/responsible-use-of-machine-learning-guide.pdf)
The Responsible Use of Machine Learning guide provides considerations and recommendations for responsibly developing and using ML systems across three major phases of their lifecycles: (1) design and development; (2) deployment; and (3) ongoing use.

### Edge

* [Blog](#edge-blog)
* [Code Sample](#edge-code-sample)
* [Whitepaper](#edge-whitepaper)
* [Workshop](#edge-workshop)

#### Edge Blog

\[Blog, 06/22\] [**Demystifying machine learning at the edge through real use cases**](https://aws.amazon.com/blogs/machine-learning/demystifying-machine-learning-at-the-edge-through-real-use-cases/)
Although ML@Edge can address many use cases, there are complex architectural challenges that need to be solved in order to have a secure, robust, and reliable design. In this post, you learn some details about ML@Edge, related topics, and how to use AWS services to overcome these challenges and implement a complete solution for your ML at the edge workload.

\[Blog, 03/22\] [**Anomaly detection with Amazon SageMaker Edge Manager using AWS IoT Greengrass V2**](https://aws.amazon.com/blogs/machine-learning/anomaly-detection-with-amazon-sagemaker-edge-manager-using-aws-iot-greengrass-v2/)
This post shows how to train and deploy an anomaly detection ML model to a simulated fleet of wind turbines at the edge using features of SageMaker and AWS IoT Greengrass V2.

\[Blog, 09/21\] [**Build machine learning at the edge applications using Amazon SageMaker Edge Manager and AWS IoT Greengrass V2**](https://aws.amazon.com/blogs/machine-learning/build-machine-learning-at-the-edge-applications-using-amazon-sagemaker-edge-manager-and-aws-iot-greengrass-v2/)
Running machine learning (ML) models at the edge can be a powerful enhancement for Internet of Things (IoT) solutions that must perform inference without a constant connection back to the cloud. Learn how to integrate Amazon SageMaker Edge Manager and AWS IoT Greengrass to build robust ML applications that are targeted specifically for edge use cases.

#### Edge Code Sample

\[Code Sample, 05/21\] [**ML@Edge with SageMaker - Getting Started Examples**](https://github.com/aws-samples/ml-edge-getting-started)
This repository contains examples of different models, showing how they can be built using Amazon SageMaker and prepared for deployment at the edge.

#### Edge Whitepaper

\[Whitepaper, 12/21\] [**Hybrid Machine Learning**](https://d1.awsstatic.com/whitepapers/hybrid-machine-learning.pdf?did=wp_card&trk=wp_card)
The purpose of this whitepaper is to outline known considerations, design patterns, and solutions that customers can leverage today when considering hybrid dimensions of the Amazon Web Services (AWS) artificial intelligence/machine learning (AI/ML) stack across the entire ML lifecycle.

#### Edge Workshop

\[Workshop, 11/21\] [**ML@Edge with SageMaker Edge Manager**](https://github.com/aws-samples/amazon-sagemaker-edge-manager-workshop)
In this workshop you will create an end-to-end solution that shows how to detect anomalies in the components of wind turbines. We'll use Amazon SageMaker to prepare a Machine Learning (ML) model and Amazon SageMaker Edge Manager to deploy and run this model to an edge device (small computer).

\[Workshop, 09/21\] [**End-to-end AIoT w/ SageMaker and Greengrass 2.0 on NVIDIA Jetson Nano**](https://github.com/aws-samples/aiot-e2e-sagemaker-greengrass-v2-nvidia-jetson)
Hands-on lab from ML model training to model compilation to edge device model deployment on the AWS Cloud. It covers the detailed method of compiling SageMaker Neo for the target device, including cloud instance and edge device, and how to write and deploy Greengrass-v2 components from scratch.

### Other

* [Blog](#other-blog)
* [Workshop](#other-workshop)

#### Other Blog

\[Blog, 07/22\] **Build and train ML models using a data mesh architecture on AWS** ([**Part 1**](https://aws.amazon.com/blogs/machine-learning/part-1-build-and-train-ml-models-using-a-data-mesh-architecture-on-aws/)) ([**Part 2**](https://aws.amazon.com/blogs/machine-learning/part-2-build-and-train-ml-models-using-a-data-mesh-architecture-on-aws/))
In this two-part series, we provide guidance on how organizations can build a modern data architecture using a data mesh design pattern on AWS and enable an analytics and ML CoE to build and train ML models with data across multiple LoBs.

\[Blog, 06/22\] [**Amazon SageMaker Studio and SageMaker Notebook Instance now come with JupyterLab 3 notebooks to boost developer productivity**](https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-studio-and-sagemaker-notebook-instance-now-come-with-jupyterlab-3-notebooks-to-boost-developer-productivity/)
In this post, we showcase some of the exciting new features built into SageMaker notebooks and call attention to some of our favorite open-source extensions that improve the developer experience when using SageMaker to build, train, and deploy your ML models.

\[Blog, 05/22\] [**3 + 1 ways of running R on Amazon SageMaker**](https://towardsdatascience.com/3-1-ways-of-running-r-on-amazon-sagemaker-13034a8f3686)
In this post we briefly describe the main ways of running your R workloads on the cloud, making use of Amazon SageMaker, the end-to-end Machine Learning cloud offering of AWS. AWS is infamous for providing options and flexibility on how developers and scientists can use their products, so don’t be surprised that this is also true for SageMaker.

\[Blog, 04/22\] [**Detect adversarial inputs using Amazon SageMaker Model Monitor and Amazon SageMaker Debugger**](https://aws.amazon.com/blogs/machine-learning/detect-adversarial-inputs-using-amazon-sagemaker-model-monitor-and-amazon-sagemaker-debugger/)
In this post, we walk you through how to detect adversarial inputs using Amazon SageMaker Model Monitor and Amazon SageMaker Debugger for an image classification model hosted on Amazon SageMaker.

\[Blog, 03/22\] **Set up a text summarization project with Hugging Face Transformers** ([Part 1](https://aws.amazon.com/blogs/machine-learning/part-1-set-up-a-text-summarization-project-with-hugging-face-transformers/)) ([Part 2](https://aws.amazon.com/blogs/machine-learning/part-2-set-up-a-text-summarization-project-with-hugging-face-transformers/))
This two-part series, proposes a practical guide for organizations so you can assess the quality of text summarization models for your domain.

\[Blog, 03/22\] [**Local Mode Training and Inference in SageMaker Studio**](https://medium.com/@sam.edwards1976/local-mode-training-and-inference-in-sagemaker-studio-3062d10ae603)
In SageMaker, ML jobs are managed and run by AWS, which is great for production as you do not have to worry about managing the underlying resources and it is easy to scale. However, when you are in development stage, running a job on SageMaker, means you have less access to the job resources. Which makes it less productive from debug and troubleshooting perspectives. This is where SageMaker Python SDK ‘Local Mode’ shines. ‘Local Mode’ allows you replicate same job on your local development environment and therefore have full access to the job resources while you are in development stage. It pulls images from ECR and setup containers to run in your local environment just as it would be done in SageMaker.

\[Blog, 03/22\] [**Amazon SageMaker JumpStart models and algorithms now available via API**](https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-jumpstart-models-and-algorithms-now-available-via-api/)
Previously, all JumpStart content was available only through Amazon SageMaker Studio, which provides a user-friendly graphical interface to interact with the feature. Today, we’re excited to announce the launch of easy-to-use JumpStart APIs as an extension of the SageMaker Python SDK. These APIs allow you to programmatically deploy and fine-tune a vast selection of JumpStart-supported pre-trained models on your own datasets. 

\[Blog, 02/22\] [**Choose the best data source for your Amazon SageMaker training job**](https://aws.amazon.com/blogs/machine-learning/choose-the-best-data-source-for-your-amazon-sagemaker-training-job/)
This post helps you choose the best data source for your SageMaker ML training use case. We introduce the data sources options that SageMaker training jobs support natively. For each data source and input mode, we outline its ease of use, performance characteristics, cost, and limitations.

\[Blog, 01/22\] [**Label text for aspect-based sentiment analysis using SageMaker Ground Truth**](https://aws.amazon.com/blogs/machine-learning/labeling-text-for-aspect-based-sentiment-analysis-using-sagemaker-ground-truth/)
The Amazon Machine Learning Solutions Lab (MLSL) recently created a tool for annotating text with named-entity recognition (NER) and relationship labels using Amazon SageMaker Ground Truth. Annotators use this tool to label text with named entities and link their relationships, thereby building a dataset for training state-of-the-art natural language processing (NLP) machine learning (ML) models. Most importantly, this is now publicly available to all AWS customers.

\[Blog, 12/21\] [**Use deep learning frameworks natively in Amazon SageMaker Processing**](https://aws.amazon.com/blogs/machine-learning/use-deep-learning-frameworks-natively-in-amazon-sagemaker-processing/)
This post shows you how SageMaker Processing has simplified running machine learning (ML) preprocessing and postprocessing tasks with popular frameworks such as PyTorch, TensorFlow, Hugging Face, MXNet, and XGBoost.

\[Blog, 12/21\] [**Build GAN with PyTorch and Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/build-gan-with-pytorch-and-amazon-sagemaker/)
This post walks you through building your first GAN model using Amazon SageMaker. This is a journey of learning GAN from the perspective of practical engineering experiences, as well as opening a new AI/ML domain of generative models.

\[Blog, 12/21\] **Create and manage Amazon EMR Clusters from SageMaker Studio to run interactive Spark and ML workloads** ([Part 1](https://aws.amazon.com/blogs/machine-learning/part-1-create-and-manage-amazon-emr-clusters-from-sagemaker-studio-to-run-interactive-spark-and-ml-workloads/)) ([Part 2](https://aws.amazon.com/blogs/machine-learning/part-2-create-and-manage-amazon-emr-clusters-from-sagemaker-studio-to-run-interactive-spark-and-ml-workloads/))
We recently introduced the ability to visually browse and connect to Amazon EMR clusters right from the Studio notebook. Starting today, you can now monitor and debug your Spark jobs running on Amazon EMR from Studio notebooks with just a single click. Additionally, you can now discover, connect to, create, stop, and manage EMR clusters directly from Studio. We demonstrate these newly introduced capabilities in this two-part post.

\[Blog, 11/21\] [**Run distributed hyperparameter and neural architecture tuning jobs with Syne Tune**](https://aws.amazon.com/blogs/machine-learning/run-distributed-hyperparameter-and-neural-architecture-tuning-jobs-with-syne-tune/)
Today we announce the general availability of Syne Tune, an open-source Python library for large-scale distributed hyperparameter and neural architecture optimization. It provides implementations of several state-of-the-art global optimizers, such as Bayesian optimization, Hyperband, and population-based training. Additionally, it supports constrained and multi-objective optimization, and allows you to bring your own global optimization algorithm.

\[Blog, 11/21\] [**Host RStudio Connect and Package Manager for ML development in RStudio on Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/host-rstudio-connect-and-package-manager-for-ml-development-in-rstudio-on-amazon-sagemaker/)
In this post, we first show you how to architect and deploy RStudio Connect and RStudio Package Manager with a well-architected solution in AWS. We then show you how to use RStudio Connect and RStudio Package Manager from RStudio on SageMaker. We use an UCI breast cancer dataset to build out several types of ML content in R language in RStudio on SageMaker. The ML content we demonstrate in the post includes R Markdown and an R Shiny application.

\[Blog, 10/21\] [**Field Notes: Build a Cross-Validation Machine Learning Model Pipeline at Scale with Amazon SageMaker**](https://aws.amazon.com/blogs/architecture/field-notes-build-a-cross-validation-machine-learning-model-pipeline-at-scale-with-amazon-sagemaker/)
In this blog post, we are going to walk through the steps for building a highly scalable, high-accuracy, machine learning pipeline, with the k-fold cross-validation method, using Amazon Simple Storage Service (Amazon S3), Amazon SageMaker Pipelines, SageMaker automatic model tuning, and SageMaker training at scale.

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

#### Other Workshop

\[Workshop, 01/22\] [**Amazon SageMaker Canvas Immersion Day**](https://catalog.us-east-1.prod.workshops.aws/workshops/80ba0ea5-7cf9-4b8c-9d3f-1cd988b6c071/en-US/)
The Immersion Day for Amazon SageMaker Canvas is a self-paced or instructor-led lab that allows customers and partners to enable themselves or other into using no-code Machine Learning and Amazon SageMaker Canvas to solve real-world challenges based on publicly available datasets. 

\[Workshop, 04/21\] **Amazon Sagemaker Immersion Day**
\[[Website](https://sagemaker-immersionday.workshop.aws/)\]
\[[GitHub](https://github.com/aws-samples/amazon-sagemaker-immersion-day)\]
An Amazon SageMaker Immersion Day provides our customers with hands-on experience to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high quality models. It is specifically designed to help us accelerate a customer opportunity for Machine-learning workload in AWS.

---
## Amazon Comprehend

* [Blog](#comprehend-blog)
* [Workshop](#comprehend-workshop)

### Comprehend Blog

\[Blog, 03/22\] [**Extract granular sentiment in text with Amazon Comprehend Targeted Sentiment**](https://aws.amazon.com/blogs/machine-learning/extract-granular-sentiment-in-text-with-amazon-comprehend-targeted-sentiment/)
This post provides an overview of how you can get started with Amazon Comprehend targeted sentiment, demonstrates what you can do with the output, and walks through three common targeted sentiment use cases.

### Comprehend Workshop

\[Workshop, 03/22\] [**Intelligent Document Processing with AWS AI Services**](https://catalog.us-east-1.prod.workshops.aws/workshops/c2af04b2-54ab-4b3d-be73-c7dd39074b20/en-US/)
In this workshop, we will dive deep into each of the phases of an IDP workflow with solutions on how to implement each step using AWS AI services. With the hands-on labs, you will familiarize yourself with AWS AI services such as Amazon Textract, Amazon Comprehend, and Amazon Augmented AI (A2I). You will learn how these services can work together to help you build an end-to-end IDP solution.

\[Workshop, 01/22\] [**Comprehend Immersion Day**](https://catalog.us-east-1.prod.workshops.aws/workshops/b54ae619-4779-409c-9bde-6e9c00edcf0f/en-US/)
This Comprehend Immersion Day provides customers with hands-on experience with Amazon Comprehend demonstrating how they can build natural language processing (NLP) use cases, and is specifically designed to help us accelerate a customer opportunity.

---
## Amazon Forecast

* [Blog](#forecast-blog)
* [Solution](#forecast-solution)

### Forecast Blog

\[Blog, 06/22\] [**Continuously monitor predictor accuracy with Amazon Forecast**](https://aws.amazon.com/blogs/machine-learning/continuously-monitor-predictor-accuracy-with-amazon-forecast/)
Forecast now automatically tracks predictor accuracy over time as new data is imported. You can now quantify your predictor’s deviation from initial quality metrics and systematically evaluate model quality by visualizing trends, and make more informed decisions about keeping, retraining, or rebuilding your models as new data comes in.

\[Blog, 11/21\] [**Understand drivers that influence your forecasts with explainability impact scores in Amazon Forecast**](https://aws.amazon.com/blogs/machine-learning/understand-drivers-that-influence-your-forecasts-with-explainability-impact-scores-in-amazon-forecast/)
Amazon Forecast now provides explainability, which gives you item-level insights across your preferred time duration. Having a certain level of understanding on why a particular forecast value is high or low at a particular time is helpful for decision-making and building trust and confidence in your ML solutions.

\[Blog, 09/21\] [**Measuring forecast model accuracy to optimize your business objectives with Amazon Forecast**](https://aws.amazon.com/blogs/machine-learning/measuring-forecast-model-accuracy-to-optimize-your-business-objectives-with-amazon-forecast/)
This blog has been updated to include three recently launched accuracy metrics in Amazon Forecast and the ability to select an accuracy metric to optimize AutoML.

### Forecast Solution

\[Solution, 05/21\] [**Improving Forecast Accuracy with Machine Learning**](https://aws.amazon.com/solutions/implementations/improving-forecast-accuracy-with-machine-learning/)
The Improving Forecast Accuracy with Machine Learning solution helps organizations generate accurate forecasts from diverse datasets. You can use this solution to configure and upload your datasets, generate forecasts, and visualize your results. This solution reduces overhead costs for organizations developing new forecasts and optimizes their existing forecasting processes by standardizing tasks and saving developer time.

---
## Amazon Fraud Detector

* [Blog](#fraud-detector-blog)
* [Code Sample](#fraud-detector-code-sample)

### Fraud Detector Blog

\[Blog, 06/22\] [**Diagnose model performance before deployment for Amazon Fraud Detector**](https://aws.amazon.com/blogs/machine-learning/diagnose-model-performance-before-deployment-for-amazon-fraud-detector/)
This post will help you to diagnose model performance and pick the right model for deployment. We walk through the metrics provided by Amazon Fraud Detector, help you diagnose potential issues, and provide suggestions to improve model performance. The approaches are applicable to both Online Fraud Insights (OFI) and Transaction Fraud Insights (TFI) model templates.

\[Blog, 10/21\] [**Build and visualize a real-time fraud prevention system using Amazon Fraud Detector**](https://aws.amazon.com/blogs/machine-learning/build-and-visualize-a-real-time-fraud-prevention-system-using-amazon-fraud-detector/)
The solution in this post provides two use cases that are built on top of a Transaction Fraud Insights model. The first use case demonstrates fraud prevention by identifying fraudulent transactions, flagging them to be blocked, and sending an alert notification. The second, writes all transactions in real time to Amazon OpenSearch Service, this enables real-time transaction reporting using OpenSearch Dashboards.

\[Blog, 10/21\] [**Train models faster with an automated data profiler for Amazon Fraud Detector**](https://aws.amazon.com/blogs/machine-learning/train-models-faster-with-an-automated-data-profiler-for-amazon-fraud-detector/)
In this post, we present an automated data profiler for Amazon Fraud Detector. It can generate an intuitive and comprehensive report of your dataset, which includes suggested Amazon Fraud Detector variable types for each variable in the dataset, and data quality issues that may potentially fail model training or hurt model performance. The data profiler also provides an option to reformat and transform the dataset to satisfy requirements in Amazon Fraud Detector, which can avoid some potential validation errors in model training.

\[Blog, 09/21\] [**Manage your Amazon Fraud Detector resources in an automated and secure manner using AWS CloudFormation**](https://aws.amazon.com/blogs/machine-learning/manage-your-amazon-fraud-detector-resources-in-an-automated-and-secure-manner-using-aws-cloudformation/)
With AWS CloudFormation, you can make changes to any number of Amazon Fraud Detector resources at once and easily repeat those changes across Regions and accounts with minimal additional effort. This post walks you through how to use AWS CloudFormation to create a stack of sample Amazon Fraud Detector resources and how to update that stack.

\[Blog, 06/21\] [**Event-based fraud detection with direct customer calls using Amazon Connect**](https://aws.amazon.com/blogs/machine-learning/event-based-fraud-detection-with-direct-customer-calls-using-amazon-connect/)
Read this blog post to learn how to build, train, and deploy a fraud detection model and rules using Amazon Fraud Detector and integrate predictions with Amazon Connect in order to connect with customers in real time.

### Fraud Detector Code Sample

\[Code Sample, 07/21\] [**Amazon Fraud Detector End-to-End**](https://github.com/aws-samples/amazon-fraud-detector-end-to-end)
This repository contains a collection of example Jupyter notebooks that interact with the Amazon Fraud Detector APIs and make use of numerous SageMaker features to prepare data, develop an Amazon Fraud Detector model, create a custom container image with necessary dependencies and use SageMaker pipelines to automate end to end flow.

---
## Amazon Kendra

* [Blog](#kendra-blog)
* [Workshop](#kendra-workshop)

### Kendra Blog

\[Blog, 06/22\] [**Take your intelligent search experience to the next level with Amazon Kendra hierarchical facets**](https://aws.amazon.com/blogs/machine-learning/take-your-intelligent-search-experience-to-the-next-level-with-amazon-kendra-hierarchical-facets/)
In a search solution with a growing number of documents, simple faceting or filtering isn’t always sufficient to enable users to really pinpoint documents with the information they’re looking for. Amazon Kendra now features hierarchical facets, with a more granular view of the scope of the search results. In this post, we demonstrate what hierarchical facets in Amazon Kendra can do. We first ingest a set of documents, along with their metadata, into an Amazon Kendra index. 

\[Blog, 04/22\] [**Enable Amazon Kendra search for a scanned or image-based text document**](https://aws.amazon.com/blogs/machine-learning/enable-amazon-kendra-search-for-a-scanned-or-image-based-text-document/)
Amazon Kendra supports a variety of document formats, such as Microsoft Word, PDF, and text. While working with a leading Edtech customer, we were asked to build an enterprise search solution that also utilizes images and PPT files. This post focuses on extending the document support in Amazon Kendra so you can preprocess text images and scanned documents (JPEG, PNG, or PDF format) to make them searchable. 

\[Blog, 03/22\] [**Improve search accuracy with Spell Checker in Amazon Kendra**](https://aws.amazon.com/blogs/machine-learning/improve-search-accuracy-with-spell-checker-in-amazon-kendra/)
In this post, we explore how to use Amazon Kendra Spell Checker on the AWS Management Console, as well as how to enable Spell Checker in an Amazon Kendra-powered search application through the AWS Command Line Interface (AWS CLI) and AWS SDK.

\[Blog, 11/21\] [**Process and add additional file formats to your Amazon Kendra Index**](https://aws.amazon.com/blogs/machine-learning/process-and-add-additional-file-formats-to-your-amazon-kendra-index/)
As of September 2021, Amazon Kendra accepts the following document types: Plaintext, HTML, PDF, Microsoft PowerPoint, and Microsoft Word. In this post, we show how to add other formats, including RTF and markdown, to your Amazon Kendra indexes. In addition, we demonstrate how you can add additional file formats to your Amazon Kendra cluster.

\[Blog, 08/21\] [**Field Notes: How to Boost Your Search Results Using Relevance Tuning with Amazon Kendra**](https://aws.amazon.com/blogs/architecture/field-notes-how-to-boost-your-search-results-using-amazon-kendra-relevance-tuning/)
We will walk through how you can manually tune your index using boosting techniques to achieve the best results. This enables you to prioritize the results from a specific data source so your users get the most relevant results when they perform searches.

\[Blog, 08/21\] [**Scale your Amazon Kendra index**](https://aws.amazon.com/blogs/machine-learning/scale-your-amazon-kendra-index/)
Read this blog post to learn about the new Amazon Kendra capacity units and revised pricing launched in July. It also provides guidance and best practices around how to estimate capacity for your Amazon Kendra index.

\[Blog, 07/21\] [**Simplify secure search solutions with Amazon Kendra’s Principal Store**](https://aws.amazon.com/blogs/machine-learning/simplify-secure-search-solutions-with-the-new-principal-store-for-secure-search-in-amazon-kendra/)
The Principal Store feature provides an Application Programming Interface (API) to store the mapping between a user ID and the groups that it has access to. When a customer application issues a query to the Amazon Kendra index, the application only needs to send the user ID. Amazon Kendra looks up the user ID in the Principal Store and finds the corresponding groups. It then filters the results based on the groups the user has access to.

\[Blog, 05/21\] [**Automatically scale Amazon Kendra query capacity units with Amazon EventBridge and AWS Lambda**](https://aws.amazon.com/blogs/machine-learning/automatically-scale-amazon-kendra-query-capacity-units-with-amazon-eventbridge-and-aws-lambda/)
Learn how to automatically scale your Amazon Kendra index query and storage capacity around a time schedule using Amazon EventBridge and AWS Lambda. This solution will allow customers to increase capacity and avoid throttling during times of peak usage, while maintaining lower costs during periods of reduced activity.

\[Blog, 05/21\] [**Build an intelligent search solution with automated content enrichment**](https://aws.amazon.com/blogs/machine-learning/build-an-intelligent-search-solution-with-automated-content-enrichment/)
Metadata can help search users narrow down a list of relevant documents by filtering and faceting. If your original data doesn’t contain metadata, you can add it to enrich your search experience. This post outlines how you can automate and simplify metadata generation for your unstructured data, making it easier to search and discover.

\[Blog, 01/21\] [**Building a secure search application with access controls using Amazon Kendra**](https://aws.amazon.com/blogs/machine-learning/building-a-secure-search-application-with-access-controls-using-amazon-kendra/)
Illustrates how to build an Amazon Kendra-powered search application supporting access controls that reflect the security model of an example organization using token-based user access control with Open ID.

### Kendra Workshop

\[Workshop, 12/20\] [**Kendra Essentials+ Workshop**](https://kendra-essentials.workshop.aws/en/)
A step-by-step walkthrough of basic Kendra functionality with explanations.

---
## Amazon Lex

* [Blog](#lex-blog)
* [Workshop](#lex-workshop)

### Lex Blog

\[Blog, 07/22\] [**Drive efficiencies with CI/CD best practices on Amazon Lex**](https://aws.amazon.com/blogs/machine-learning/drive-efficiencies-with-ci-cd-best-practices-on-amazon-lex/)
Let’s say you have identified a use case in your organization that you would like to handle via a chatbot. You familiarized yourself with Amazon Lex, built a prototype, and did a few trial interactions with the bot. You liked the overall experience and now want to deploy the bot in your production environment, but aren’t sure about best practices for Amazon Lex. In this post, we review the best practices for developing and deploying Amazon Lex bots, enabling you to streamline the end-to-end bot lifecycle and optimize your operations.

\[Blog, 05/22\] [**Use Amazon Lex to capture street addresses**](https://aws.amazon.com/blogs/machine-learning/use-amazon-lex-to-capture-street-addresses/)
In this post, we’ll demonstrate how you can use Amazon Lex and the Amazon Location Service to provide an effective user experience for capturing their address via voice or text.

\[Blog, 04/22\] [**Integrate ServiceNow with Amazon Lex chatbot for ticket processing**](https://aws.amazon.com/blogs/machine-learning/integrate-servicenow-with-amazon-lex-chatbot-for-ticket-processing/)
In this post, we show you how to integrate an Amazon Lex chatbot with ServiceNow . The bot will make it easier for creation and tracking of tickets for day-to-day activities such as issuing new office equipment for new hires.

\[Blog, 03/22\] [**Enable conversational chatbots for telephony using Amazon Lex and the Amazon Chime SDK**](https://aws.amazon.com/blogs/machine-learning/enable-conversational-chatbots-for-telephony-using-amazon-lex-and-the-amazon-chime-sdk/)
In this post, we teach you how to build a conversational IVR system for a fictitious travel service that accepts reservations over the phone using Amazon Lex.

\[Blog, 11/21\] [**Monitor operational metrics for your Amazon Lex chatbot**](https://aws.amazon.com/blogs/machine-learning/monitor-operational-metrics-for-your-amazon-lex-chatbot/)
Designing a bot and deploying it in production is only the beginning of the journey. You want to analyze the bot’s performance over time to gather insights that can help you adapt the bot to your customers’ needs. A deeper understanding of key metrics such as trending topics, top utterances, missed utterances, conversation flow patterns, and customer sentiment help you enhance your bot to better engage with customers and improve their overall satisfaction. It then becomes crucial to have a conversational analytics dashboard to gain these insights from a single place. In this post, we look at deploying an analytics dashboard solution for your Amazon Lex bot. 

\[Blog, 09/21\] **How to approach conversation design [(Part 1)](https://aws.amazon.com/blogs/machine-learning/part-1-approach-conversation-design-the-basics/) [(Part 2)](https://aws.amazon.com/blogs/machine-learning/part-2-how-to-approach-conversation-design-getting-started-with-amazon-lex/)**
The first part of this multi-part series, discusses the basics of conversational design, including how to identify use cases for conversational AI, and crafting system personalities. The second part reviews high-level design best practices and how to use them when designing your conversational interfaces.

\[Blog, 08/21\] [**Build conversation flows with multi-valued slots in Amazon Lex**](https://aws.amazon.com/blogs/machine-learning/build-conversation-flows-with-multi-valued-slots-in-amazon-lex/)
Multiple pieces of information are often required to complete a task or to process a query. These pieces of information often take the form of lists in a conversation (i.e., Can you provide me insurance quotes for home, auto, boat, etc.). Previously, developers had to use multiple slots to capture each value in the list. Now, support for multi-valued slots exists in Amazon Lex.

\[Blog, 06/21\] [**Interact with an Amazon Lex V2 bot with the AWS CLI, AWS SDK for Python (Boto3), and AWS SDK for DotNet**](https://aws.amazon.com/blogs/machine-learning/interact-with-an-amazon-lex2v2-bot-with-the-aws-cli-aws-sdk-for-python-and-aws-sdk-dotnet/)
The Amazon Lex V2 console and APIs introduce a new method to build and interact with your bots. This post illustrates different methods to interact with a Amazon Lex V2 chatbot programmatically using the: AWS Command Line Interface, (AWS CLI), AWS SDK for Python (Boto3), and the AWS SDK for DotNet.

### Lex Workshop

\[Workshop, 05/21\] [**Amazon Lex Workshops**](https://amazonlex.workshop.aws/)
The new Amazon Lex V2 Console makes it easier to build, deploy, and manage bots. In this workshop you will learn about how to use the Amazon Lex Console and API, basic bot building concepts, and how to create some simple bots - all of these will be done using the Lex V2 console. 

---
## Amazon Lookout for Metrics

* [Blog](#lookout-for-metrics-blog)
* [Code Sample](#lookout-for-metrics-code-sample)
* [Workshop](#lookout-for-metrics-workshop)

### Lookout for Metrics Blog

\[Blog, 06/22\] [**Easily customize your notifications while using Amazon Lookout for Metrics**](https://aws.amazon.com/blogs/machine-learning/easily-customize-your-notifications-while-using-amazon-lookout-for-metrics/)
We are excited to announce that you can now add filters to alerts and also edit existing alerts while using Amazon Lookout for Metrics. In this post, we demonstrate how to create Alert with filters and how the configured filters publish alerts only for anomalies matching the filter criteria.

\[Blog, 08/21\] [**Simplify and automate anomaly detection in streaming data with Amazon Lookout for Metrics**](https://aws.amazon.com/blogs/machine-learning/simplify-and-automate-anomaly-detection-in-streaming-data-with-amazon-lookout-for-metrics/)
Amazon Lookout for Metrics does not currently have a native integration with Amazon Kinesis Data Streams to ingest streaming data and run anomaly detection on it. This blog can help customers solve this problem by using an AWS Glue Spark streaming ETL script to ingest and organize streaming data.

\[Blog, 08/21\] [**Detect anomalies in operational metrics using Dynatrace and Amazon Lookout for Metrics**](https://aws.amazon.com/blogs/machine-learning/detect-anomalies-in-operation-metrics-using-dynatrace-and-amazon-lookout-for-metrics/)
Learn how to set up anomaly detection within your operational metrics. This post demonstrates how you can connect to your IT operational infrastructure monitored by Dynatrace using Amazon AppFlow and set up an accurate anomaly detector across metrics and dimensions using Lookout for Metrics.

\[Blog, 07/21\] [**Smart city traffic anomaly detection using Amazon Lookout for Metrics and Amazon Kinesis Data Analytics Studio**](https://aws.amazon.com/blogs/machine-learning/smart-city-traffic-anomaly-detection-using-amazon-lookout-for-metrics-and-amazon-kinesis-data-analytics-studio/)
This post shows you how to use an integrated solution with Amazon Lookout for Metrics and Amazon Kinesis Data Analytics Studio (among other AWS services) to break these barriers by quickly and easily ingesting streaming data, aggregating and curating it, and subsequently detecting anomalies in the key performance indicators of your interest.

### Lookout for Metrics Code Sample

\[Code Sample, 02/22\] [**Amazon Lookout for Metrics Custom Connectors**](https://github.com/aws-samples/amazon-lookout-for-metrics-custom-connectors)
This repository serves as a guide and reference for reaching out to complex databases, performing desired ETL processes on data, then streaming it easily into S3 for use with L4M.

\[Code Sample, 10/21\] [**Visualize your Lookout for Metrics on QuickSight**](https://github.com/aws-samples/amazon-lookout-for-metrics-samples/blob/main/getting_started/5.UseQuicksightToVisualizeL4M.ipynb)
The notebook generates all the necessary resources to bring your inference results and live data from Amazon Lookout for Metrics (L4M) to Amazon Quickight to allow the building of visualizations.

### Lookout for Metrics Workshop

\[Workshop, 10/21\] [**Amazon Lookout for Metrics Workshop**](https://lookoutformetrics.workshop.aws/en/)
This workshop guides participants through the steps of setting up and using Amazon Lookout for Metrics. It consists of two sections: backtesting on historical data, and generating readable alerts from anomalies. 

---
## AWS Panorama

* [Blog](#panorama-blog)
* [Video](#panorama-video)

### Panorama Blog

\[Blog, 11/21\] [**Deploy an Object-Detector Model at the Edge on AWS Panorama**](https://towardsdatascience.com/deploy-an-object-detector-model-at-the-edge-on-aws-panorama-9b80ea1dd03a)
Learn how to deploy state-of-the-art computer vision models on AWS Panorama, a powerful edge device to realize online and cost-effective object detection.

### Panorama Video

\[Video, 11/21\] [**On Grid: AWS Panorama - Part I, unboxing, review and guided setup**](https://www.youtube.com/watch?v=xRxAWClUTZc&t=84s)
A short video showing the AWS Panorama device, with a longer part II going into more detail. The video shows the unboxing and setup of the device.

---
## Amazon Personalize

* [Blog](#personalize-blog)
* [Code Sample](#personalize-code-sample)
* [Solution](#personalize-solution)
* [Video](#personalize-video)
* [Workshop](#personalize-workshop)

### Personalize Blog

\[Blog, 10/21\] [**Amazon Personalize can now unlock intrinsic signals in your catalog to recommend similar items**](https://aws.amazon.com/blogs/machine-learning/amazon-personalize-can-now-unlock-intrinsic-signals-in-your-catalog-to-recommend-similar-items/)
This post shows you how to use our new recipe (aws-similar-items) and illustrates the difference compared to our collaborative filtering-based recipe (SIMS).


\[Blog, 08/21\] [**Optimize personalized recommendations for a business metric of your choice with Amazon Personalize**](https://aws.amazon.com/blogs/machine-learning/optimize-personalized-recommendations-for-a-business-metric-of-your-choice-with-amazon-personalize/)
Amazon Personalize now enables customers to optimize personalized recommendations for a business metric of choice such as revenue, profit margin, video watch time, or any other numerical attribute to optimize their recommendations.

\[Blog, 07/21\] [**Unlock information in unstructured text to personalize product and content recommendations with Amazon Personalize**](https://aws.amazon.com/blogs/machine-learning/unlock-information-in-unstructured-text-to-personalize-product-and-content-recommendations-with-amazon-personalize/)
This post shows you how to include unstructured text when using Amazon Personalize and the impact it can have on the relevance of the recommendations you generate with the service.

\[Blog, 07/21\] [**Use contextual information and third party data to improve your recommendations**](https://aws.amazon.com/blogs/machine-learning/use-contextual-information-and-third-party-data-to-improve-your-recommendations/)
In this post, we share a hands-on approach to include context when generating recommendations, by using data from our partners in the AWS Data Exchange. For this example, we use a subset of the temperatures and precipitation dataset provided by Weather Trends International, combined with a fictitious dataset representing a bottler company beverage catalog and a user demo dataset from the Retail Demo Store

\[Blog, 04/21\] [**Scale session-aware real-time product recommendations on Shopify with Amazon Personalize and Amazon EventBridge**](https://aws.amazon.com/blogs/machine-learning/scale-session-aware-real-time-product-recommendations-on-shopify-with-amazon-personalize-and-amazon-eventbridge/)
In this post, we describe the architectures used in our application for serving recommendations as well as synchronizing events and catalog updates in real time. We also share some of the results for session-based personalization from a customer using the application.

### Personalize Code Sample

\[Code Sample, 12/20\] [**Amazon Personalize Monitor**](https://github.com/aws-samples/amazon-personalize-monitor)
This project contains the source code and supporting files for deploying a serverless application that adds monitoring, alerting, and optimization capabilities for Amazon Personalize.

### Personalize Solution

\[Solution, 10/21\] [**Maintaining Personalized Experiences with Machine Learning**](https://aws.amazon.com/solutions/implementations/maintaining-personalized-experiences-with-ml/?did=sl_card&trk=sl_card.)
This solution streamlines and accelerates the development and deployment of your personalization workloads through end-to-end automation and scheduling of updates for resources within the Amazon Personalize service.

### Personalize Video

\[Video, 12/20\] [**Amazon Personalize Deep Dive Series**](https://www.youtube.com/playlist?list=PLhr1KZpdzukd9GSGRy329wahNO_8TkRo_)
In this video series you will get an introduction to Amazon Personalize and dive deeper into topics related to data, training, inference, and operations.

### Personalize Workshop

\[Workshop, 02/21\] [**Amazon Personalize Immersion Day**](https://personalization-immersionday.workshop.aws/en/)
This Immersion Day offers a deep-dive on Amazon Personalize, with a collection driven by hands-on labs based on specific domains (M&E, Retail, and CPG).

---
## Amazon Rekognition

\[Blog, 03/22\] [**Computer vision using synthetic datasets with Amazon Rekognition Custom Labels and Dassault Systèmes 3DEXCITE**](https://aws.amazon.com/blogs/machine-learning/computer-vision-using-synthetic-datasets-with-amazon-rekognition-custom-labels-and-dassault-systemes-3dexcite/)
In this post, we present a novel approach where highly specialized computer vision systems are created from design and CAD files. We start with the creation of visually correct digital twins and the generation of synthetic labeled images. Then we push these images to Amazon Rekognition Custom Labels to train a custom object detection model. By using existing intellectual property with software, we’re making computer vision affordable and relevant to a variety of industrial contexts.

\[Blog, 09/21\] [**Calculate inference units for an Amazon Rekognition Custom Labels model**](https://aws.amazon.com/blogs/machine-learning/calculate-inference-units-for-an-amazon-rekognition-custom-labels-model/)
Determining the number of inference units (IUs) required to optimally run inference on your Amazon Rekognition Custom Labels model can be tricky. In this post, learn how to calculate the IUs you need to meet your workload performance requirements at the lowest possible cost.

\[Blog, 09/21\] [**Explore image analysis results from Amazon Rekognition and store your findings in Amazon DocumentDB**](https://aws.amazon.com/blogs/machine-learning/explore-image-analysis-results-from-amazon-rekognition-and-store-your-findings-in-amazon-documentdb/)
In this post, we focus on the use case of enabling image search and exploration of a generic photo collection. We look at the JSON output of image analysis generated from Amazon Rekognition, which we ingest into Amazon DocumentDB, and then explore using Amazon SageMaker.

\[Blog, 07/21\] **Automate continuous model improvement with Amazon Rekognition Custom Labels and Amazon A2I ([Part 1](https://aws.amazon.com/blogs/machine-learning/part1-automate-continuous-model-improvement-with-amazon-rekognition-custom-labels-and-amazon-a2i/)) ([Part 2](https://aws.amazon.com/blogs/machine-learning/part2-automate-continuous-model-improvement-with-amazon-rekognition-custom-labels-and-amazon-a2i/))**
This post is the first in a two-part series that explains how to implement an automated Amazon Rekognition Custom Labels and Amazon Augmented AI (Amazon A2I) ML workflow that can provide continuous model improvement without requiring ML expertise.

\[Blog, 07/21\] [**Detect small shapes and objects within your images using Amazon Rekognition Custom Labels**](https://aws.amazon.com/blogs/machine-learning/detect-small-shapes-and-objects-within-your-images-using-amazon-rekognition-custom-labels/)
In this post, we demonstrate a preprocessing method to increase the size ratio of small objects with respect to an image and optimize the object detection capabilities of Amazon Rekognition Custom Labels, effectively solving the small object detection challenge.

---
## Amazon Textract

* [Blog](#textract-blog)
* [Workshop](#textract-workshop)

### Textract Blog

\[Blog, 06/22\] [**Merge cells and column headers in Amazon Textract tables**](https://aws.amazon.com/blogs/machine-learning/merge-cells-and-column-headers-in-amazon-textract-tables/)
In April 2022, Amazon Textract introduced a new capability of the table feature that automatically detects merged rows and columns as well as headers. This post walks you through a simple example of how to use the merged cells and headers features.

\[Blog, 05/22\] [**Create video subtitles with Amazon Transcribe using this no-code workflow**](https://aws.amazon.com/blogs/machine-learning/create-video-subtitles-with-amazon-transcribe-using-this-no-code-workflow/)
Subtitle creation on video content poses challenges no matter how big or small the organization. To address those challenges, Amazon Transcribe has a helpful feature that enables subtitle creation directly within the service. There is no machine learning (ML) or code writing required to get started. This post walks you through setting up a no-code workflow for creating video subtitles using Amazon Transcribe within your Amazon Web Services account.

\[Blog, 04/22\] [**Specify and extract information from documents using the new Queries feature in Amazon Textract**](https://aws.amazon.com/blogs/machine-learning/specify-and-extract-information-from-documents-using-the-new-queries-feature-in-amazon-textract/)
Amazon Textract now offers the flexibility to specify the data you need to extract from documents using the new Queries feature within the Analyze Document API. You don’t need to know the structure of the data in the document (table, form, implied field, nested data) or worry about variations across document versions and formats.

\[Blog, 03/22\] [**Automate digitization of transactional documents with human oversight using Amazon Textract and Amazon A2I**](https://aws.amazon.com/blogs/machine-learning/automate-digitization-of-transactional-documents-with-human-oversight-using-amazon-textract-and-amazon-a2i/)
In this post, we present a solution for digitizing transactional documents using Amazon Textract and incorporate a human review using Amazon Augmented AI (A2I). Our reference solution uses a highly resilient pipeline to coordinate the various document processing stages.

\[Blog, 11/21\] [**Postprocessing with Amazon Textract: Multi-page table handling**](https://aws.amazon.com/blogs/machine-learning/postprocessing-with-amazon-textract-multi-page-table-handling/)
Many developers expressed interest in merging Amazon Textract responses where tables exist across multiple pages. This post demonstrates how you can use the amazon-textract-response-parser utility to accomplish this and highlights a few tricks to optimize the process.

\[Blog, 10/21\] [**Bring structure to diverse documents with Amazon Textract and transformer-based models on Amazon SageMaker**](https://aws.amazon.com/blogs/machine-learning/bring-structure-to-diverse-documents-with-amazon-textract-and-transformer-based-models-on-amazon-sagemaker/)
In this in-depth blog post, learn different ways to use Amazon Textract and Amazon SageMaker to automate especially challenging document analysis tasks.

\[Blog, 06/21\] [**Improve newspaper digitalization efficacy with a generic document segmentation tool using Amazon Textract**](https://aws.amazon.com/blogs/machine-learning/improve-newspaper-digitalization-efficacy-with-a-generic-document-segmentation-tool-using-amazon-textract/)
Text extraction from newspapers is difficult because of different layouts, structures, and images. Learn how Amazon ML Solutions Lab was able to overcome this problem by developing a custom neural network-based document segmentation engine with Amazon SageMaker and Amazon Textract.

\[Blog, 03/21\] [**PDF document pre-processing with Amazon Textract: Visuals detection and removal**](https://aws.amazon.com/blogs/machine-learning/process-text-and-images-in-pdf-documents-with-amazon-textract/)
In many use cases, you need to extract and analyze documents with various visuals, such as logos, photos, and charts. These visuals contain embedded text that convolutes Amazon Textract output or isn’t required for your downstream process. For example, many real estate evaluation forms or documents contain pictures of houses or trends of historical prices. This information isn’t needed in downstream processes, and you have to remove it before using Amazon Textract to analyze the document. In this post, we illustrate two effective methods to remove these visuals as part of your preprocessing.

### Textract Workshop

\[Workshop, 03/22\] [**Intelligent Document Processing with AWS AI Services**](https://catalog.us-east-1.prod.workshops.aws/workshops/c2af04b2-54ab-4b3d-be73-c7dd39074b20/en-US/)
In this workshop, we will dive deep into each of the phases of an IDP workflow with solutions on how to implement each step using AWS AI services. With the hands-on labs, you will familiarize yourself with AWS AI services such as Amazon Textract, Amazon Comprehend, and Amazon Augmented AI (A2I). You will learn how these services can work together to help you build an end-to-end IDP solution.

---
## Amazon Transcribe

* [Blog](#transcribe-blog)
* [Video](#transcribe-video)

### Transcribe Blog

\[Blog, 02/22\] [**Live call analytics for your contact center with Amazon language AI services**](https://aws.amazon.com/blogs/machine-learning/live-call-analytics-for-your-contact-center-with-amazon-language-ai-services/)
Amazon Machine Learning (ML) services like Amazon Transcribe and Amazon Comprehend provide feature-rich APIs that you can use to transcribe and extract insights from your contact center audio at scale. Although you could build your own custom call analytics solution using these services, that requires time and resources. In this post, we introduce our new sample solution for live call analytics.

\[Blog, 12/21\] [**Post call analytics for your contact center with Amazon language AI services**](https://aws.amazon.com/blogs/machine-learning/post-call-analytics-for-your-contact-center-with-amazon-language-ai-services/)
Amazon Machine Learning (ML) services like Amazon Transcribe Call Analytics and Amazon Comprehend provide feature-rich APIs that you can use to transcribe and extract insights from your contact center audio recordings at scale. Although you could build your own custom call analytics solution using these services, that requires time and resources. In this post, we introduce our new sample solution for post call analytics.

\[Blog, 09/21\] [**Boost transcription accuracy of class lectures with custom language models for Amazon Transcribe**](https://aws.amazon.com/blogs/machine-learning/transcribe-class-lectures-accurately-using-amazon-transcribe-with-custom-language-models/)
When transcribing content that is more specialized or domain-specific such as biology, Amazon Transcribe offers custom language models (CLM). One common problem we see is the difficulty in accurately transcribing certain subjects. In this post, we show how you can harness readily available content to train a CLM in Amazon Transcribe and boost the transcription accuracy on scientific subjects like biology.

\[Blog, 09/21\] [**Now available in Amazon Transcribe: Automatic Redaction of Personally Identifiable Information**](https://aws.amazon.com/blogs/aws/now-available-in-amazon-transcribe-automatic-redaction-of-personally-identifiable-information/) & [**How to redact personally identifiable information from audio files with Amazon Transcribe**](https://aws.amazon.com/blogs/machine-learning/perform-audio-redaction-for-personally-identifiable-information-with-amazon-transcribe/)
These posts are about redacting PII in Amazon Transcribe and demonstrates an approach for redacting PII from both a text transcription and source audio file.

\[Blog, 05/21\] [**Improve the streaming transcription experience with Amazon Transcribe partial results stabilization**](https://aws.amazon.com/blogs/machine-learning/amazon-transcribe-now-supports-partial-results-stabilization-for-streaming-audio/)
We’re happy to announce that Amazon Transcribe now allows you to enable and configure partial results stabilization for streaming audio transcriptions. Amazon Transcribe is an automatic speech recognition (ASR) service that enables developers to add real-time speech-to-text capabilities into their applications for on-demand and streaming content. Instead of waiting for an entire sentence to be transcribed, you can now control the stabilization level of partial results. Transcribe offers 3 settings: High, Medium and Low. Setting the stabilization “High” allows a greater portion of the partial results to be fixed with only the last few words changing during the transcription process. This feature helps you have more flexibility in your streaming transcription workflows based on the user experience you want to create.

### Transcribe Video

\[Video, 01/22\] [**Using Custom Language Models (CLM) to supercharge transcription accuracy**](https://www.youtube.com/watch?v=iTkJoIqRrPU)
Amazon Transcribe is an automatic speech recognition (ASR) service that makes it easy for you to add speech-to-text capabilities to your applications. Unlike the Custom Vocabulary feature, which enhances speech recognition for a discrete list of out-of-lexicon terms, CLM allows you to leverage pre-existing data to build a custom speech engine tailored for your transcription use case. Amazon Transcribe customers who operate in domains as diverse as law, finance, hospitality, insurance, and media all stand to benefit.

\[Video, 10/21\] [**Amazon Transcribe video snacks: Use content redaction to identify & redact PII**](https://www.youtube.com/watch?v=4H8dQoeLkyM)
Amazon Transcribe is an automatic speech recognition (ASR) service that makes it easy to add speech to text capabilities to any application. Amazon Transcribe can help customers identify and redact sensitive personally identifiable information (PII) from transcripts in the supported languages. This provides customers with a toolkit to protect sensitive user data and comply with local privacy laws & regulations. In this video, we'll be seeing this feature in action for both streaming and batch transcriptions.

\[Video, 10/21\] [**Amazon Transcribe video snacks: Using vocabulary filters**](https://www.youtube.com/watch?v=TcpSqbr0FnI)
Amazon Transcribe is a automatic speech recognition service that can be used when you have audio and video that contains speech you want to convert to text. You can mask, remove, or tag words you don't want in your transcription results with vocabulary filtering. For example, you can use vocabulary filtering to prevent the display of offensive or profane terms. In the demo, I’ll customize Transcribe to mask swear words that I recently encountered in a famous play written by William Shakespeare.

\[Video, 08/21\] [**Amazon Transcribe video snacks: Using custom vocabulary**](https://www.youtube.com/watch?v=oBgSJ7bsP2U)
Amazon Transcribe is a automatic speech recognition service that can be used when you have audio and video that contains speech you want to convert to text. If your speech has domain-specific terms like proper nouns, brand names, or technical jargon, then you’ll want to use the custom vocabulary feature. This feature can help you enhance transcription accuracy by addressing these “custom terms” using a list of specific words or phrases that you want Transcribe to recognize. In the demo, I’ll customize Transcribe to recognize skateboarding trick names I saw during the Tokyo Olympics by creating two types of custom vocabulary lists, supporting both custom pronunciation and custom display. 

---
## Amazon Translate

* [Blog](#translate-blog)
* [Code Sample](#translate-code-sample)
* [Video](#translate-video)

### Translate Blog

\[Blog, 05/22\] [**Personalize your machine translation results by using fuzzy matching with Amazon Translate**](https://aws.amazon.com/blogs/machine-learning/personalize-your-machine-translation-results-by-using-fuzzy-matching-with-amazon-translate/)
In this post, you learn how to customize output from Amazon Translate according to translation memory fuzzy match quality scores.

\[Blog, 02/22\] [**Apply profanity masking in Amazon Translate**](https://aws.amazon.com/blogs/machine-learning/apply-profanity-masking-in-amazon-translate/)
Amazon Translate is a neural machine translation service that delivers fast, high-quality, affordable, and customizable language translation. This post shows how you can mask profane words and phrases with a grawlix string (“?\$#@$”).

\[Blog, 11/21\] [**Customize Amazon Translate output to meet your domain and organization specific vocabulary**](https://aws.amazon.com/blogs/machine-learning/customize-amazon-translate-output-to-meet-your-domain-and-organization-specific-vocabulary/)
When you translate from one language to another, you want your machine translation to be accurate, fluent, and most importantly contextual. Customization is key in keeping your machine translation contextual. Amazon Translate provides multiple capabilities for customization to achieve the best machine translation. One such capability is custom terminology. Custom terminology enables you to customize your translation output such that your domain and organization specific vocabulary such as brand names, character names, model names, and other unique content (named entities) are translated exactly the way you need. In this post, we walk you through the step-by-step process of how to use custom terminology and get a customized machine translated output securely.

### Translate Code Sample

\[Code Sample, 02/21\] [**Translating Captions files (VTT, SRT) using Amazon Translate**](https://github.com/aws-samples/amazon-translate-video-subtitles-captions-translation)
This project contains source code and supporting files for a serverless pipeline for translating Caption files in VTT and SRT formats using Amazon Translate that you can deploy with the SAM CLI. 

### Translate Video

\[Video, 03/21\] [**Amazon Translate | Deep Dive Video Series**](https://www.youtube.com/playlist?list=PLhr1KZpdzukePPoSt1BZUNYQ6r5BdNm-1)
A collection of videos covering the functionality of Amazon Translate and several solutions addressing specific use cases. 

---
## Sustainability

\[Blog, 02/22\] **Optimize AI/ML workloads for sustainability ([Part 1](https://aws.amazon.com/blogs/architecture/optimize-ai-ml-workloads-for-sustainability-part-1-identify-business-goals-validate-ml-use-and-process-data/)) ([Part 2](https://aws.amazon.com/blogs/architecture/optimize-ai-ml-workloads-for-sustainability-part-2-model-development/))**
In this series of three blog posts, we’ll provide guidance from the Sustainability Pillar of the AWS Well-Architected Framework to reduce the carbon footprint of your AI/ML workloads.