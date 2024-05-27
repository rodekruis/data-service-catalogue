# 121 Manual

> [!TIP]
> Read the manual: <https://manual.121.global>

## Development

### Getting Started

#### with Python

- Install a [Python virtual environment](https://realpython.com/python-virtual-environments-a-primer/) (On Linux/macOS):

  ```sh
  python3 -m venv venv
  source venv/bin/activate
  ```


- Install dependencies

  ```sh
  pip install -r requirements.txt
  ```

- Build the documentation

  ```sh
  mkdocs serve
  ```

- Preview at: <http://localhost:8000>

#### With Docker

See [this section](https://squidfunk.github.io/mkdocs-material/getting-started/#with-docker) of the mkdocs-material documentation on how to set it up and run in docker.
The `DOCKERFILE` and `requirements.txt` can be used as is.

### Tools in use

- Material for MkDocs: <https://squidfunk.github.io/mkdocs-material/>
