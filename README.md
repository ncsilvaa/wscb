# wscb
Warming Starting Contextual Bandits is an initiative to mitigate the pure cold-start problem in linear bandit models.


## Setup

1. Create a virtual environment:

```console
    $ cd wscb
    $ python3.8 -m venv .venv
    $ source .venv/bin/activate
```
 
2. Clone the repository **irec** in the root of the **wscb** directory and install:

```console
    $ git clone https://github.com/irec-org/irec.git
    $ cd irec
    $ python3.8 -m pip install pip --upgrade
    $ python3.8 -m pip install -e .
```