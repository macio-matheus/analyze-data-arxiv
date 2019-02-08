# analyze-data-arxiv
Data analysis of the website http://arxiv.org

Chosen topic: math

### Team

- Henrique Lima (https://github.com/henriquelima1408)
- Julio Sales (https://github.com/jsalesba)
- Mácio Matheus Arruda (https://github.com/macio-matheus)
- Victor Outtes (https://github.com/victorouttes)


### Folder structure

```sh
    * notebooks - Contains all notebooks
    * datasets - Must contain all project datasets files
    * models - Must contains all machine learning models
```

### Dataset

```sh
   wget https://www.dropbox.com/s/k6knmy7pvqiqo8v/_author_paper.json -P ../datasets/
   wget https://www.dropbox.com/s/z5qz0al2eezdlin/_papers.json -P ../datasets/
```

### Dataframe paper

![paper](https://raw.githubusercontent.com/macio-matheus/analyze-data-arxiv/master/docs/dataframe-paper.png)



### Network year one

![network](https://raw.githubusercontent.com/macio-matheus/analyze-data-arxiv/master/docs/network-one.png)

### Usage
First of all, build the container using docker-compose and then you can 
access the Jupyter that is ready to be used.

#### Run with docker compose
```sh
cd analyse-data-arxiv
docker-compose up -d
```

#### Accessing Jupyter
```sh
http://<your-ip>:8899/tree
```

#### Ports
```sh
- 8899 => Jupyter
```

### DockerHub
```sh
https://hub.docker.com/r/maciomatheus/jupyter_notebook_data_science/
```