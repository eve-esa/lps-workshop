# Living Planet Symposium, EVE workshop 2025

This repository contains materials for hands on sessions for the EVE project

Each track have notebooks that can be ran in the provided environment and are self contained. If desired, these notebooks can be ran in any jupyterlab environment (See [Environment Setup](#environment-setup)).

# Slides:

# Prerequisites
1. Basic understanding of git
2. Python and jupyter environment knowledge
3. Machine Learning knowledge
4. Basic knowledge of Natural Language Processing (NLP)

# Getting started
1. Navigate to [Login URL](https://workshop-domain-wfs0nk4u.auth.us-west-2.amazoncognito.com/login?client_id=809mbkpbfj5mddgb7dismf3g0&response_type=code&scope=aws.cognito.signin.user.admin+openid+profile&redirect_uri=https://ngsa42o8k5.execute-api.us-west-2.amazonaws.com/invoke)
2. Log in using the credential provided
![Login with username and password](images/login.png)
3. Once the Studio starts, Click on JupyterLab
![Sagemaker studio](images/sagemaker-studio.png)
![JupyterLab spaces](images/jupyterlab-spaces.png)
4. <code style="color : red">A JupyterLab space should already be availble for you. If not, please follow along the next steps. Skip to Step 9 if the environment is already available.</code>
5. Click `Create JupyterLab Space`
![JupyterLab spaces](images/create-jupyterlab-env.png)
6. Give it a name. Eg: `Workshop`
7. Once initialized, change Instance type to `ml.p3.2xlarge` and storage to `30`
8. Click on `Run Space`. If it throws an error, you might have to pick an Image. The top setting called `Latest` works.
9. If a space is already running, click on "open". This should open a new tab with the jupyterlab environment.
![Open](/images/workshop-jypyterlab-app-list.png)
![Jupyterlab Environment](/images/jupyter-lab-home-page.png)


# Colab fallback
If you're unable to follow the session using the provided environment, you can follow these steps to run the notebook on your personal Colab account:
1. Download the hands-on-notebook from the [repo](https://github.com/eve-esa/lps-workshop/blob/main/eve_use_cases.ipynb):
![Download](images/download_colab.png)
2. Upload it on your [colab account](https://colab.research.google.com/):

![Upload notebook](images/upload_notebook.png)
3. Uncomment (by removing '#' characters) and run the requirements cell:
![Install libraries](images/install_libraries.png)
4. Create another cell and run the [code](https://docs.google.com/document/d/1DPKWhcv-PcLUVyvsKr8kM_tQG2cx0rdAr96jHSu4p6k/edit?usp=sharing) to initialize the enviroment variables

# Acknwoledgements
Many thanks to Iksha from the [NASA-IMPACT](https://github.com/NASA-IMPACT) team for the support and guidance during the infrastructure setup.