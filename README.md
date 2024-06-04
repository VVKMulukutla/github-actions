# Github Actions Practice

This is a repository for practicing using GitHub Actions. It contains a simple Python program that is used to test the pipeline.

## The Program

The program, `hello.py`, is a simple program that prints "Hello, World!" to the console.

## The Pipeline

The pipeline is defined in `.github/workflows/hello.yml`. It is a simple workflow that runs the program using Python.

The pipeline consists of a single job, `test`, which runs the program using the `actions/setup-python` action. The job uses the `ubuntu-latest` environment and runs the program using the `python` command.

The pipeline is triggered whenever a push is made to the repository.

## Running the Pipeline

To run the pipeline, simply push any change to the repository. You should see the output of the pipeline in the Actions tab of the repository.

If the pipeline is successful, you should see the output of the program in the pipeline logs.

