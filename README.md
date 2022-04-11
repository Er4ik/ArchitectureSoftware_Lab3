# ArchitectureSoftware_Lab3

## Installation

- Clone the repository

```bash
git clone https://github.com/Er4ik/ArchitectureSoftware_Lab3.git
```

## Usage

### Run task 1 - Python 

- If you have node and npm on your pc:

```bash
npm run start:python
```

- If you haven't node and npm on your pc:

```bash
cd python
docker build -f Dockerfile -t lab3:01 .
docker run --rm -it -p 3000:8080 lab3:01
```

### Run task 2 - Golang

