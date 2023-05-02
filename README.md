<h1>Landing Spacecrafts</h1>
Learn how an autonomous systems learns from its experience

Reinforcement Learning (RL) is a machine learning paradigm in which an agent learns to make decisions in an uncertain and dynamic environment through experience. The agent's goal is to maximize a numerical reward it receives from the environment based on its actions.

In RL, the agent interacts with the environment through a series of states and actions. The agent observes the current state of the environment, takes an action, and receives a reward from the environment. The agent's objective is to find the optimal policy, i.e., the best way to act in each state to maximize the accumulated long-term reward.

In this session we'll go over the full learning process of an autonomous system

<h1>Installation requirements</h1>
This notebook requires an particular environment. Don't worry, conda environment is for this purpose.
Let's see step by step this new environment.

<h2> Environment creation</h2>
1 . te a new environment using the following command

conda create -n marslander python=3.8.8

2. Then activate the new environment

conda activate marslander

<h2> Package installation </h2>

Run the following commands to have in your new envrionment all the needed packages

conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia
pip install jupyter
pip install spacy
pip install ribs[all] gym~=0.17.0 Box2D~=2.3.10 tqdm
conda install swig

As you can see, I've chosen Jupyter Notebook to run the session. If you feel comfortable with any other code editor, feel free!
