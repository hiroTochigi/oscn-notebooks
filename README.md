# oscn-noteboks
A collection of notebooks for researching oscn.net

## SetUp by Docker container

1 `git clone https://github.com/codefortulsa/oscn-notebooks`

1 `cd oscn-notebooks`

1 `docker run --name oscn -p 8888:8888 -it -v `pwd`:/home/oscn_notebook/work hirotochigi/oscn_notebook`

## Setup

1 create a python 3.6.5 virtualenv

1 `pip install -r requirements.txt`

## Usage

`jupyter notebook`

Notebooks are available at http://localhost:8888
