# Deephaven Streamlit Component

This component displays Deephaven widgets within streamlit

## Quickstart

Uses the [Streamlit component-template](https://github.com/streamlit/component-template).

- Create a new Python virtual environment for the template:

```
$ cd template
$ python3 -m venv .venv  # create venv
$ source .venv/bin/activate   # activate venv
$ pip install streamlit # install streamlit
$ pip install deephaven-server #install Deephaven server
```

- From a separate terminal, run the template's Streamlit app:

```
$ source .venv/bin/activate  # activate the venv you created earlier
$ streamlit run deephaven_component/__init__.py  # run the example
```

- If all goes well, you should see something like this:

![Quickstart Success](quickstart.png)

- Modify the Python code at `deephaven_component/__init__.py`.
