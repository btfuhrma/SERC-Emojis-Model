Repository for the SERC team for setting up their model for identifying sentiment values of emojis in context.

Will be using HuggingFace and Tensorflow.

Set up instructions:

1. Install WSL

    In Windows CMD type: wsl --install
   
    wsl --set-default Ubuntu

2. Update source list and install python

    sudo apt-get update

    sudo apt install python3

    sudo apt-get install python3-pip

4. Install HuggingFace and dependencies
   
    pip install --upgrade huggingface_hub

    pip install 'huggingface_hub[tensorflow]'    

    pip install transformers[tf-cpu]
