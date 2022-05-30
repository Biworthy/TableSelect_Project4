
## Features

## How do I open a specific Notebook?
The following code should open the given notebook in the currently running notebook server, starting one if necessary.

```jupyter notebook notebook.ipynb```
### How do I start the Notebook using a custom IP or port?
By default, the notebook server starts on port 8888. If port 8888 is unavailable or in use, the notebook server searches the next available port. You may also specify a port manually. In this example, we set the server’s port to 9999:

```jupyter notebook --port 9999```
