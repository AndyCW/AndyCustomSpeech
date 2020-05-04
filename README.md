# Azure Custom Speech DevOps Solution

Learn about DevOps with [Azure Custom Speech](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/how-to-custom-speech) and use the solution in this template repository as the foundation for your own project to continuously improve Custom Speech models using a CI/CD workflow running on GitHub Actions.

* Automatically create new Custom Speech models when training data is updated.
* Create and manage release endpoints when an improved model is built.
* Update the benchmark accuracy when testing data is updated.
* Version Custom Speech data, test results, endpoints, models, and more out of the box.

## Get the Code

Create a new repository to hold the code and the GitHub Actions pipelines:

1. Log in to GitHub, or [create an account](https://github.com/join).
2. Click the green **Use this template** button at the top of this repository, or the following link to [generate a copy of this template repository](https://github.com/KatieProchilo/CustomSpeechDevOpsSample/generate) to your own GitHub account.
    1. Enter a name for the repository where prompted.
    2. Leave **Include all branches** unchecked. You only need to copy the master branch of this repository.
    3. Click **Create repository from template** to create your copy.
3. [Clone your repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). Use this repository to walk through this guide and for your own experimentation.

## Walk Through the Solution

Step through the Custom Speech DevOps workflow to set up the environment, train the first model, and continuously improve any models that come after that. The project you create can be used as a starting point to develop your own Custom Speech model.

***Required:*** Follow the steps to run this workflow in your personal GitHub repository:

1. [Project Setup](./documentation/1-project-setup.md)
2. [Create the Initial Custom Speech Model](./documentation/2-create-the-initial-custom-speech-model.md)
3. [Improve Custom Speech Models](./documentation/3-improve-custom-speech-models.md)

***Customization:*** Visit [Advanced Customization](./documentation/4-advanced-customization.md) to incorporate this solution into a pre-existing Custom Speech project, change the folder structure, use alternative storage options, and more.
