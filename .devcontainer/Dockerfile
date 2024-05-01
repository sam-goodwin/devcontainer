FROM rayproject/ray:latest-py310-cpu

# install curl
RUN sudo apt update \
  && sudo apt install -y curl

RUN curl -fsSL https://code-server.dev/install.sh | sh -s

RUN pip install uv \
  && sudo apt update \
  && sudo apt install -y build-essential
