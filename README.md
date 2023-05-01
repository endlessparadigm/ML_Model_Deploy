# ML_Model_Deploy
Deploying an ML Model to Production

Git
CI/CD
Azure, DataBricks, Spark

* Automate the deployment
* Scalability

Management of deployment dependencies between different systems, repos and development teams (release tags, integrative tests, delivery plans)

English and German?

0. Gather data
1. Training the data/model (apply algorithms)
2. Containerize the model (Docker or?) docker container for the model to run in with all its dependencies (such as libraries)
3. Validate (Output vs business expectations). Is it running slow, should it be different, etc.
4. Deploy the model in the cloud (often through an API), on an on-prem server
5. Monitor and retrain

Model registry - for version changing and control
Code management - code control
Dataset management - Dataset repositories
Shared environments - Reusability of models

ML Pipeline:
