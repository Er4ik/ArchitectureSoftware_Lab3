# ArchitectureSoftware_Lab3

## Installation

- Clone the repository

```bash
git clone https://github.com/Er4ik/ArchitectureSoftware_Lab3.git
```

## Usage

### Run task 1 - Python 

- If you have node and npm on your pc:

Running on port 80

```bash
npm run start:python
```

- If you haven't node and npm on your pc:

```bash
cd python
docker build -f Dockerfile -t lab3:01 .
docker run --rm -it -p 80:8080 lab3:01
```

### Run task 2 - Golang

- If you have node and npm on your pc:

- Check first Dockerfile:

Running on port 3000

```bash
npm run start:go_v1
```

- Check second Dockerfile:

Running on port 3001

```bash
npm run start:go_v2
```

- Check third Dockerfile:

Running on port 5000

```bash
npm run start:go_v3
```

- If you haven't node and npm on your pc:

- Check first Dockerfile:

```bash
cd go
docker build -f Dockerfile.V1 -t lab3:01 .
docker run --rm -it -p 3000:8080 lab3:01
```

- Check second Dockerfile:

```bash
cd go
docker build -f Dockerfile.V2 -t lab3:01 .
docker run --rm -it -p 3001:8080 lab3:01
```

- Check third Dockerfile:

```bash
cd go
docker build -f Dockerfile.V3 -t lab3:01 .
docker run --rm -it -p 5000:8080 lab3:01
```

### Run task 3 - JavaScript

- If you have node and npm on your pc:

Running on port 5001

```bash
npm run start:js
```

- If you haven't node and npm on your pc:

```bash
cd js
docker build -f Dockerfile -t lab3:01 .
docker run --rm -it -p 5001:3000 lab3:01
```