# ML workflow workshop
In this workshop, we will work on improving our machine learning workflow by creating a small framework to build our pipeline for EDA, data processing, modeling, evaluation and logging. You could this as a boilerplate for hackathons, ML projects/experiments or running quick prorotypes for a proof of concept.

We will work with the following dataset: https://zindi.africa/competitions/be-a-trailblazer/data

# Setup
In this workshop. You will prepare your own setup by:
- Adding instructions to create and activate a virtual envir an
- Adding a requirements.txt file that contains all necessary dependencies in your project
  - Tip: after activating your virtual envir and installing necessary packages, you can dump them into the file by running the following commmand:
    ``pip freeze > requirements.txt``

# Objectives of this workshop
The goal of this workshop is for you to build your own boilerplate starting from this repo so you could customize it to your preferences. But in order to do that, these are the things we need to cover:
- Writing scripts to train, evaluate and predict with our models
- Parsing arguments to have better control over our workflow
- using the settings.py file to manage file paths, global variables and configurations
- Properly document our code
- Logging our experiments
- Serializing/pickling our models
