Conda Environments

This repo contains a collection of predefined conda environments.

```
mamba env create -n dp -f dataprocessing.yml
mamba activate dp
```

Envs can be mixed and matched. A Python version other than the latest compatible can also be manually selected.

```
mamba create -n py310 python=3.10
mamba activate py310
mamba env update -n py310 -f dataprocessing.yml
mamba env update -n py310 -f arts.yml
```
