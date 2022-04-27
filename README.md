# hatch-2022
Streamlit template that can be used as a starting point for creating a solution to a HATCH challenge

# Step 1: Requirements

This repo was created and tested with python 3.9

We are using pip tools to create the requirements.txt file from the requirements.in file.

```
?>pip install pip-tools
?>pip-compile requirements.in
?>pip install -r requirements.txt
```

# Step 2: Check setup

To verify that streamlit is installed and working properly, run the following command:

```
?>streamlit hello
```

This should start a local server for streamlit and bring up a browser showing a demo application.

# Step 3: Create the simple app

We took one of the demo examples and created a simple app in the dataframe-demo.py file. You can run it with:

```
?>streamlit run dataframe-demo.py
```

# Step 4: Have Streamlit host the app

Create an account (or login) with streamlit cloud: [Link](https://docs.streamlit.io/streamlit-cloud/get-started)

Set up app to point to the repository and branch.