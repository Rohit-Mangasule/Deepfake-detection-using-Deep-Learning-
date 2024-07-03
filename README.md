# Deep fake detection Django Application
## Requirements:

**Note :** Nvidia GPU is mandatory to run the application.
- CUDA version >= 10.0 for GPU
- GPU Compute Capability > 3.0 


Main requirements are listed below:

```
Python >= v3.6
Django >= v3.0
```

## Directory Structure

- ml_app -> Directory containing code in views.py file
- project_settings -> Contains Django settings and files to run in production
- static -> Contains all css, js and json files (for face-api)
- templates -> Template files for HTML

<b>Note:</b> Before running the project make sure you have created directories namely <strong>models, uploaded_images, uploaded_videos</strong> in the project root and that you have proper permissions to access them.


### Prerequisite
1. Copy your trained model to the models folder.
   - You can download our trained models from the [Google Drive](https://drive.google.com/drive/folders/1UX8jXUXyEjhLLZ38tcgOwGsZ6XFSLDJ-?usp=sharing) or you can train your models using the steps mentioned in Model Creation directory.


#### Step 1: Create virtualenv (optional)

`python -m venv venv`

#### Step 2: Activate virtualenv (optional)

`venv\Scripts\activate`

#### Step 3: Install requirements

`pip install -r requirements.txt`

#### Step 4: Copy Models

`Copy your trained model to the models folder i.e Django Application/models/`


### Step 5: Run project

`python manage.py runserver`
