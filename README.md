# The Golang Dev Environment

This is the Golang dev-environment.

The environment is using the following tools:

- Go: > 1.16
- gopls
- dlv

## Requirements

This requires the following to run:

- Docker
- Docker Compose

## Getting Started

1. Clone the repo.

```
git clone git@github.com:hodanov/docker-template-golang.git
```

The directory structure is the below.

```
.
├── .env
├── README.md
├── docker-compose.yml
└── df-go.dockerfile
```

2. After cloning, modify some environment in `.env` file.

3. Execute `docker-compose up`

```
docker-compose up -d
```

Docker container will run and the `code/app` directory will be made.

The directory is mounted `/go/src/app` directory in a container.

Thank you.

## Author

[Hoda](https://hodalog.com)
