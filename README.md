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

- Open up a terminal and pull the image
  ```sh
  docker pull squidfunk/mkdocs-material
  ```

- Run the container
  ```sh
  docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
  ```

- If you are using plugins, create a DOCKERFILE to extend the official images
    ``` Dockerfile title="Dockerfile"
  FROM squidfunk/mkdocs-material
  RUN pip install -r requirements.txt
  ```
  Make sure to have a requirements.txt file in the root folder.

### Tools in use

- Material for MkDocs: <https://squidfunk.github.io/mkdocs-material/>
