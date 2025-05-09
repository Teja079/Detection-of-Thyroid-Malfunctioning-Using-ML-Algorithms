# 1) Go to the project folder (adjust the path if you moved it)
cd ~/Desktop/Detection-of-Thyroid-Malfunctioning-Using-ML-Algorithms-main

# 2) Activate the Python 3.8 virtual‑environment you created earlier
source venv38/bin/activate      # prompt changes to (venv38)

# 3) Jump into the folder that contains app.py
cd src

# 4) Tell Flask which file holds the app object
export FLASK_APP=app.py         # do this once per new shell

# 5) Launch the development server
flask run --debug               # Ctrl‑C to stop it
