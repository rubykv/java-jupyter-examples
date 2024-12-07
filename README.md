# java-jupyter-examples
Examples that can be executed on Java Jupyter kernel

## Installation
Easiest way to get IJava (kernel) up and running is to run it in docker.
1. Install Docker (If not installed already)
2. Run the following command
    ```bash
    
      docker run -itd -p 127.0.0.1:8888:8888 -v $PWD:/home/jupyter deepjavalibrary/jupyter

3. Access jupyter instance at http://localhost:8888

To check other installation options - visit DJL docs here -> https://docs.djl.ai/master/docs/demos/jupyter/index.html
