# analyze-data-arxiv
Data analysis of the website http://arxiv.org

```sh
# Start the jupyter using docker
docker-compose up -d
```

Folder structure

```sh
    * notebooks - Contains all notebooks
    * datasets - Must contain all project datasets files
    * models - Must contains all machine learning models
```

Dataset

```sh
   wget https://www.dropbox.com/s/s5mysx0b6sp7jvw/authors.json -P ../datasets/
   wget https://www.dropbox.com/s/ktvn3q2ijfka9zn/authors_paper.json -P ../datasets/
   wget https://www.dropbox.com/s/jbqvl5htdv41c33/papers.json -P ../datasets/
```


Clustering formed by feature extraction of abstracts from papers

![clusters](https://raw.githubusercontent.com/macio-matheus/analyze-data-arxiv/master/docs/clusters.png)
 