# Documentation automatic upload

## Setup virtual environment
```
mkvirtualenv seek --python=python3
(seek) pip install -r requirements.txt
(seek) pip install jupyterlab --upgrade
(seek) python -m ipykernel install --user --name seek
```

## API token
For the connection with the database an API token is required.
Make sure this token is not tracked in the repository.

```
echo -n 'user:password' | base64 > token
```
