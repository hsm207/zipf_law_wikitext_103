# Introduction

This repository contains code to reproduce the results from my blog post titled [Using Zipf's Law To Improve 
Neural Language Models](https://medium.com/@_init_/using-zipfs-law-to-improve-neural-language-models-4c3d66e6d2f6).

# Usage

1. Install [Docker](https://docs.docker.com/install/).

2. Open a terminal and execute:

    ```bash
    # PATH is the path to this project's directory.
    docker run --rm -p 8888:8888  -v PATH:/home/jovyan/work jupyter/scipy-notebook:6fb3eca57bd3

    ```
3. This previous command will produce a url for you to log into a jupyter notebook server. Open a webrowser and
navigate to that URL. Look for a notebook titled `zipf_law_in_wikitext` in the `notebooks` folder.
