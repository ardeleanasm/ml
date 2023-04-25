#BUILD

docker build -t python .

# RUN

docker run -p 8888:8888 -it -v c:\Users\sardelean\Documents\Docker\python\work:/app --entrypoint /bin/bash python
