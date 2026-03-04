[Home](/ci-docs/) | 
[Get Access](/ci-docs/get-access/) | 
[Training](/ci-docs/training/) | 
[Policies](/ci-docs/policies/) | 
[Examples](/ci-docs/examples/) | 
[Support](/ci-docs/support/)

---

# HTCondor Job Examples
---

➡ **Open the official HTCondor example repository**

[Open HTCondor Examples](https://github.com/jsu-research-computing/htcondor-examples)

---
JSU Research Computing provides ready-to-use **HTCondor example workflows** to help new users learn how to run computational jobs on shared cyberinfrastructure systems.

These examples are designed to be:

- simple to understand  
- safe to run on shared resources  
- easy to modify for real research projects  

---

# Run Your First Job

If you are new to JSU Research Computing, start with a **simple test job** to confirm your environment works correctly.

### Step 1 — Open the official examples repository

➡ **HTCondor Examples (GitHub)**  
https://github.com/jsu-research-computing/htcondor-examples

Start with the **hello-world** example.

---

### Step 2 — Basic workflow

Most HTCondor jobs follow this process:

1. Connect to the submit node
2. Navigate to the example directory
3. Submit the job
4. Monitor the job queue
5. Retrieve the output files

This verifies that your environment and job configuration are working properly.

---

# Included Workflows

The example repository currently includes several starter workflows.

---

## Hello World Job

A minimal HTCondor job demonstrating:

- basic submit file structure  
- job execution and logging  
- output file generation  

This is the recommended **first job for all new users**.

Example location in repository:

https://github.com/jsu-research-computing/htcondor-examples/tree/main/hello-world
---

## File Transfer Job

Shows how to:

- send input files to compute nodes  
- retrieve output files after execution  
- manage working directories safely  

This pattern is essential for **real research workloads**.

---

## DAGMan Workflow

Demonstrates:

- multi-step job pipelines  
- dependency management between jobs  
- scalable execution of complex workflows  

This example prepares users for **advanced computational research**.

---

# How to Use These Examples

1. Clone or download the repository.
2. Read the README inside each example folder.
3. Modify file paths and resource requests for your project.
4. Submit jobs using HTCondor on JSU systems.

New users should complete the **training modules** before running large workloads.

➡ Training:  
/ci-docs/training/

---

# Need Help?

The **Cyberinfrastructure Facilitation Team** can assist with:

- adapting examples for research projects  
- debugging job submissions  
- scaling workflows for large datasets  
- connecting to national HTC resources  

➡ Visit the **Support** page:

/ci-docs/support/
