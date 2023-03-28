# Introduction-to-data-version-control

Data version control (DVC) is a software tool designed to help data scientists and machine learning engineers manage and track changes to their data sets and machine learning models. Just like how code version control systems like Git help manage changes to code, DVC helps manage changes to data, and keep track of versions of data sets and machine learning models over time.

DVC works by creating a separate version control repository that works in conjunction with Git. The data files and models are stored separately from the code, and DVC creates a reference to the data files in the Git repository. This means that data and code can be versioned separately, but linked together.

With DVC, you can track changes to your data sets, including changes to individual files or the entire data set, and revert to a previous version of the data set if necessary. You can also create different versions of machine learning models based on different data sets or parameters, and easily compare the performance of each model.

DVC also makes it easier to collaborate on data science projects. By using a separate repository for data version control, multiple team members can work on the same data sets and models, and changes can be tracked and merged just like with code.

### What Is Data Version Control?

DVC is a tool that helps data scientists and machine learning engineers manage, version, and collaborate on data sets and machine learning models. It enables tracking changes to data and models, which makes it easier to develop and maintain data-driven applications.There are multiple DVC solutions both free and paid. One of them is `Hangar`, a fully open-source Python DVC package. 

### Working with Hangar

The hangar package is a pure Python implementation and is available through pip. Its core functionality is also closely developed to git, which greatly helps the learning curve. We also have the option to either interact with hangar via the command line or use its dedicated Python client.

We can install hangar through pip using:
```python 
pip install hangar
```

Some of it's functionality include:

- checkout — switch to a new branch or reference point
- commit — add the current changes to the current branch
- branch — create a reference point to a specific commit
- merge — combine the changes from one branch to another
- diff — compare the changes between two branches
- push — upload the local version to the remote repository
- pull/fetch — update the local version of a dataset from the remote repository
- log — display the commit history
