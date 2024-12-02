# java-jupyter-examples
Examples that can be executed on Java Jupyter kernel

## Installation
Easiest way to get IJava (kernel) up and running is to run it in docker (I couldn't get it installed in my local with Java21-GraalVM)
    ```bash
    
      docker run -itd -p 127.0.0.1:8888:8888 -v $PWD:/home/jupyter deepjavalibrary/jupyter

To check other options - visit DJL docs here -> https://docs.djl.ai/master/docs/demos/jupyter/index.html
