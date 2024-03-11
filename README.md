# Learnign Log

Simple blog-like application. You can create your user profile and store information in topics by creating entries. You can manage these topics and entries.


## Setup

1. Clone repository

```bash
git clone 
```

2. Make sure Docker is installed on your system (else install [Docker](https://docs.docker.com/engine/install/))
```bash
docker --version
```

3. Build Docker image

```bash
docker build -t learning_log .
```

### Deploy locally

4. Run container

```bash
docker run -d --name learning_log -p 80:80 learning_log
```
 5. Go to [localhost:8000/](localhost:8000/) and explore