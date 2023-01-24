ARG DOCKER_REGISTRY=public.aml-repo.cms.waikato.ac.nz:443/
FROM ${DOCKER_REGISTRY}wairas/happy-spy:0.23.1

RUN pip install --no-cache-dir "git+https://github.com/wairas/spy-utilities.git@e2024fc8b4f65e0e858e104868a3848d0e476c50"

COPY bash.bashrc /etc/bash.bashrc
