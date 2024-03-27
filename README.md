# DAVID_The_Desktop_Voice_Assistant
DAVID is an 21st Century Prototype of an Modern AI Assistant for desktop users.
DAVID is an enhance version of previous so called desktop assistant "Microsoft Cortana"

# DAVID Working
The model is based on the working of the API, through which we give the commands and recieve response from the model.
The model is developed using Python Programming Language.
It is an prototype model for the implementation of Natural Language Processing and Deep Learning.
# DAVID Working Methodology
Step 1: Installing of Modules for the model formation

Step 2: Voice Input from the user

Step 3: Recognition of the Command from the user

Step 4: Collecting Data for the search

Step 5: Extracting Data for the search

Step 6: Presenting the Data for the model output

#Step 1 Installation, accounts, APIs...
Environment
Make a new, empty virtual environment with Python 3.8 and activate it (.\venv_name\Scripts\activate );
pip install -r venv_requirements.txt; This might take some time; if you encounter conflicts on specific packages, install them manually without the ==<version>;
install manually PyTorch according to your CUDA VERSION;
Copy and paste the files you'll find in the folder whisper_edits to the whisper folder of your environment (.\venv\lib\site-packages\whisper\ ) these edits will add just an attribute to the whisper model to access its dimension more easily;
install TTS;
Run their script and check everything is working (it should download some models) (you can alternatively run demos/tts_demo.py);
Rename or delete the TTS folder and download the Assistant and other scripts from this repo
Install Vicuna following the instructions on the Vicuna folder or by running:
cd Vicuna and call vicuna.ps1
Manual instructions will instruct you to follow the Vicuna Installation Guide
paste all your keys in the env.txt file and rename it to .env (yes, remove the txt extension)
Check everything works (following)

Checks
Verify your graphic engine and CUDA version are compatible with PyTorch by running torch.cuda.is_available() and torch.cuda.get_device_name(0) inside Pyhton; .
run tests.py. This file attempt to perform basic operations that might raise errors;
[WARNING] Check the FAQs below if you have errors;
You can check the sources of error by running demos in the demos folder;



