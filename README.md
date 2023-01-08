<div align="center">

<a href="https://www.ametsoc.org/index.cfm/ams/">
<img src ="https://www.ametsoc.org/themes/ametsoc-new/images/AMSlogoFull-web.png" width=65% alt="American Meteorological Society logo">
</a>

<img src="logos/unidata_logo_horizontal.png" width=50% alt="Unidata logo">

# ![](logos/metpy-32x32.png "MetPy logo") Beginner Python Workshop
### 2023 AMS Annual Meeting
### 22nd Annual Student Conference
</div>

## :keyboard: Getting set up
For this workshop, we have two separate ways you can participate, work ahead, and follow along.
As part of the learning experience, we recommend setting up a Python environment on your personal computer.
We understand potential limitations on this, so you will be provided access to Unidata's Science Gateway to do your work on the NSF Jetstream2 Cloud as part of your registration.

### :cloud: Using [Science Gateway](http://scigw.unidata.ucar.edu/)
If you've registered for this workshop, you can do all of this work on our very own _gateway_ to the NSF Jetstream Cloud!
For this course, temporary logins will be generated and handed out to registrants in the classroom.

When you first sign in, it may take a few seconds for your personal workspace to populate and your coding environment to be fully set up.
From here you will discover a Jupyter Lab interface pre-populated with these materials and a few tools to enable you to update the materials if needed.

This requires only a web browser and a stable internet connection.
Get to coding!

### :computer: Using your computer
**Note that we at Unidata are not able to plan for specific hardware limitations your personal computer might have.**
We will have limited time and facilitator capacity for on-site technical support.
Please plan to use Science Gateway if this is a concern for you.
We will be using and supporting [Conda](https://docs.conda.io/en/latest/) for installing and managing a Python environment from your computer's command line.
Please have this environment prepared ahead of time if you'll be using your own computer.

> 1. [Install Miniconda](https://docs.conda.io/en/latest/miniconda.html#installing) if you don't already have command-line access to `conda`.
> 1. Get a copy of this code!
> You have a few options from the **green button** above,  
> a. [Install git](https://github.com/git-guides/install-git) if necessary.
> `git clone https://github.com/Unidata/pyaos-ams-2023.git` from your command line, within some directory on your computer.
> If you're comfortable with `git`, we recommend this approach as it will easily let you keep this code regularly up to date.  
> b. [`Open with GitHub Desktop`](https://desktop.github.com/) if you have and prefer this graphically-focused software.  
> c. [`Download ZIP`](https://github.com/unidata/pyaos-ams-2023/archive/refs/heads/main.zip) if you prefer to get a single snapshot of the code right here and now.  
> 1. Wherever you have this code saved, set up your Python environment with `conda env create -f environment.yml` from your command line.  
> 1. Give this some time.
> Once it's done, activate this new environment with `conda activate pyaos-ams-2023`.
> Always do this before starting on work for this workshop!
> 1. Launch Jupyter and get to coding with `jupyter lab`.
> Always remember to activate your environment first!

#### :warning: Important!
It is often important to update your environment and code you're working with **frequently**, and that is true for our workshop!
Please make sure to re-download any updated code and confirm that your environment works **before the start of the course**.
To support this, our facilitators will be available in the half-hour before the workshop to have room for doing this together.
Whether you set up a local Python environment or participate in the cloud, please come to the classroom during this time window for a smooth start to the course!

## :speech_balloon: Acknowledgements
Launching this JupyterHub server is the result of a collaboration between several research and academic institutions and their staff.
For Jetstream2 and JupyterHub expertise, we thank Andrea Zonca (San Diego Supercomputing Center), Jeremy Fischer, Mike Lowe (Indiana University), the NSF Jetstream2 (doi:10.1145/3437359.3465565) team.

This work employs the NSF Jetstream2 Cloud at Indiana University through allocation EES220002 from the Advanced Cyberinfrastructure Coordination Ecosystem: Services & Support (ACCESS) program, which is supported by National Science Foundation grants #2138259, #2138286, #2138307, #2137603, and #2138296.

Unidata is one of the University Corporation for Atmospheric Research (UCAR)'s Community Programs (UCP), and is funded primarily by the National Science Foundation (AGS-1901712).

### To Acknowledge This JupyterHub and the Unidata Science Gateway
If you have benefited from the Unidata Science Gateway, please cite doi:10.5065/688s-2w73.
Additional citation information can be found in this Citation File Format file.
