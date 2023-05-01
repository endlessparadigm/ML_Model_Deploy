# ML_Model_Deploy
Deploying, automating, and monitoring a Machine Learning Model to Production

## Summary
I have a repository and business case related to the average price of avocadoes for a made-up manufacturing company. The data scientists have provided us with a sample or copy of the dataset, and model - to be utilized in production. You can find this [here.](https://github.com/endlessparadigm/ML_Model_Dataset)

Let's cover a few things prior to setting up our CI/CD pipelines, versioning, repositories and more. 

> Let's review the dataset and understand what we're working with. Does the dataset contain unstructured data or uncommon filetype (such as a mainframe output file or X-ray imaging data). 

> Are we utilizing one dataset (like a CSV) or a collection of data such as a data lake for analytics. 

> Does the data contain personal or financial information (in which case are there any privacy or encryption protocols that need to be included)? Maybe the data is out of date, incorrect, or not being catalogued based on corporate expectations or metadata guidelines applied by the business.

It seems the dataset is a simple .CSV, with the associated models included in the folder.

[requirements.txt Add screenshot of such here]

> Requirements:

> Add Requirements.

> What other parameters or requirements has the business provided?

Included in our attachment is list of the following:

.txt - 
CI/CD Pipeline




At this point we want to upload the dataset and model(s) to the appropriate repositories and registries. This helps us keep a catalogue of all of our datasets and models, and helps the business to audit, discover, or access previous versions or editions of the aforementioned. For our demo, I have saved it in personal folders on my drive titled:
> /Projects/Datasets/ and /Projects/Models/.

## [Setting up the Repository]
## [Containerizing the Model]

## [CI/CD - Building our Pipeline]

Prior to creating our pipeline, we first need to create a repository.
Check on CI/CD pipelines on  Github.

## [CI/CD - Automating the Deployment]

1. Training the data/model (apply algorithms)
2. Containerize the model (Docker or?) docker container for the model to run in with all its dependencies (such as libraries)
3. Validate (Output vs business expectations). Is it running slow, should it be different, etc.
4. Deploy the model in the cloud (often through an API), on an on-prem server
5. Monitor and retrain

## [CI/CD - Monitoring and Auditing our Pipelines]

# Conclusion - Learning Outcomes

With this exercise we accomplished the following tasks:
> Model registry - for version changing and code control
> Dataset management - Dataset repositories, data quality standards, privacy and encryption protocols
> Shared environments (?) - Reusability of models
> Pipeline scheduling and job dependencies
> Automated deployment
> Scalability (?)
> Audit and monitoring (pipeline health)

ML Pipeline:

Git
CI/CD
Azure, DataBricks, Spark
