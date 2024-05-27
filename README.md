# 121 Manual

> [!TIP]
> Read the manual: <https://manual.121.global>

## Development

### Getting Started

#### With Python

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

- Install Docker: <https://docs.docker.com/get-docker/>

- Open a terminal at this folder to build a Docker-container:

  ```sh
  docker build --tag manual-121 .
  ```

- Run the Docker-container:

  ```sh
  docker run --rm -it -p 8000:8000 -v ${PWD}:/docs manual-121
  ```

### Tools in use

- Material for MkDocs: <https://squidfunk.github.io/mkdocs-material/>
