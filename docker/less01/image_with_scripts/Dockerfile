FROM ubuntu:latest
RUN apt update && apt install python3 && apt-get clean
COPY script.sh .
COPY script.py .
CMD ["/bin/bash"]
