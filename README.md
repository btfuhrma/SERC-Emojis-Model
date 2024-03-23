Repository for the SERC team for setting up their model for identifying sentiment values of emojis in context.

Will be using HuggingFace and Tensorflow.

Set up instructions:

1. Set up virtual environment (Windows)

    Inside VSCode console, type: python3 -m venv .venv
   
    This will create a virtual environment that will be separate from differentiating between already installed Python packages on your machine.

    To Start the virtual environment type: .venv\Scripts\activate

3. Install HuggingFace and dependencies
   
    pip install --upgrade huggingface_hub

    pip install 'huggingface_hub[tensorflow]'    
