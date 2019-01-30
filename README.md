# analyze-data-arxiv
Data analysis of the website http://arxiv.org

```sh
# Start the topology as defined in http://debezium.io/docs/tutorial/
docker-compose up -d
```

Folder structure

```sh
    * notebooks - Contains all notebooks
    * datasets - Must contain all project datasets files
```

Dataset

```sh
   wget https://www.dropbox.com/s/s5mysx0b6sp7jvw/authors.json -P ../datasets/
   wget https://www.dropbox.com/s/ktvn3q2ijfka9zn/authors_paper.json -P ../datasets/
   wget https://www.dropbox.com/s/jbqvl5htdv41c33/papers.json -P ../datasets/
```