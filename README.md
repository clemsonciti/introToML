# introToML
Welcome to Clemson University's Cyberinfrastructure and Technology Integration Training Workshops!

Introduction to Machine Learning Techniques and Tools 

--The first half of this workshop focuses on machine learning techniques in Python (Scikit-learn), which remains the overwhelming first choice as a programming language for machine learning. 
--The second half of workshop focused on deep learning techniques in DIGITS, the NVIDIA Deep Learning GPU Training System, which is easy to learn and use. 
-- We will also learn how to process through the Palmetto Supercomputer.

Instructions to set up the workshop
1. Request to be added to the singularity group if you are not.

Contact ithelp@clemson.edu and include the word "Palmetto" in the subject line with a request to be added to the singularity group.
Check your actual status on your palmetto ssh session by typing "groups" on the terminal:
    $ groups cuuser singularity

2. If you are using windows, please install MobaXterm before the workshop in order to use Nvidia digits. Please follow the instructions at https://www.palmetto.clemson.edu/palmetto/userguide_basic_usage.html

3. Download MNIST dataset

Login to palmetto
Request a compute node by type the command

```
$ qsub -I
```

Then type

```
$module add deep-learning
$python -m digits.download_data mnist ~/mnist
```
