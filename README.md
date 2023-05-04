## Amazon SageMaker training jobs using Snowpark Python API

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) is a fully managed service for data science and machine learning (ML) workflows. You can use Amazon SageMaker to simplify the process of building, training, and deploying ML models.

To train a model, you can include your training script and dependencies in a [Docker container](https://www.docker.com/resources/what-container) that runs your training code. A container provides an effectively isolated environment, ensuring a consistent runtime and reliable training process.

In this GitHub repo we will demonstrate how to use SageMaker training jobs using Snowpark Python API to fetch data from Snowflake.

### Build a custom SageMaker Studio image with Snowpark already installed

We aim to explain how to create a custom image for Amazon SageMaker Studio that has Snowpark already installed. The advantage of creating an image and make it available to all SageMaker Studio users is that it creates a consistent environment for the SageMake Studio users, which they could also run locally.
To create the custom Conda environment for Snowpark, please follow the instructions [here](snowflake-env-kernel-image).

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

