# el-LLM-iott

## Environment
**Step 1: Install Anaconda**
- [Visit the Anaconda Website](https://www.anaconda.com/products/distribution)
- Download the Anaconda distribution that matches your operating system (e.g., Windows, macOS, Linux).
- Follow the installation instructions for your OS. During installation, you can choose whether to add Anaconda to your system's PATH; it's recommended to do so.

**Step 2: Create a Conda Environment**
- Open terminal or command prompt
- Navigate to project `cd ~/[project-path]`
- Create a new conda environment `conda create --name <environment_name> python=3.x`
- Activate the conda environment (source=conda for windows) `source activate <environment_name>`
- Verify the conda environment was create successfully `conda info --envs`

**Step 3: Install Hugging Face's Transformers**
- Activate conda environment `source activate <environment_name>`
- Install transformers library `pip install transformers`

** ongoing... **

## Resources
- [Companion Notebook](https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing)
- [Lecture Repo](https://github.com/karpathy/ng-video-lecture)
- [GPT Repo](https://github.com/elliottbarnes/nanoGPT)
