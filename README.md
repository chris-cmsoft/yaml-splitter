# Yaml Splitter

Self feeding script, which takes a single yaml file as input, and unbundles all the different parts, split by `---`, into their own separate files.

This project spawned from the need to constantly unbundle ~6000 line yaml files for Kubernetes, into a file for every resource.

Normally I would go through afterwards and give each file an appropriate name.

### Setup

After cloning the repository, you should install the dependencies. 

### Installation

```bash
pip install -r requirements.txt
```

### Usage

```bash
splityaml input.yml -o split/
```
