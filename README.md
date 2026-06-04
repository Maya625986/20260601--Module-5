# 20260601--Module-5

# Monday PM Task-
Load the datasets
Clean them (thoroughly)
Measure at least 1 data engingeering metric in the data cleaning process (ie dropped rows)
MVP- output the clean files as a local csv

# Tuesday AM Task-
Focus on having at least one function like:
    dataEnrich():
        Calculate the days between the two date columns and add it as new col
    fileLoader
    duplicateCheck
    naCheck
    dataCleaner
    addToSQL

# Wednesday AM Task-
Level 1- Create your docker container with your cleaner app and date files. Your data must be saved in the volume
Level 2- Look into the concept of Docker Compose
Level 3- Look at the difference between Docker Swarm and Kubernetes

# Wednesday PM Task-
Tidy your repo and add requirements.txt to your root
Add GitHub Actions with YAML file from my repo
Trigger a push and see if the CI pipeline works as expected

# Thursday AM Task-
Tidy your repository into folders
Create a Power Bi dashboard that shows the library stakeholders. 
    Would like to see the below on a dashboard:
        Number of records processed
        Number of records dropped
        Books and customer data
        Pipeline execution time

![alt text](image.png)