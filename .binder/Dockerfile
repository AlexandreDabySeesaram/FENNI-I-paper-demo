################################################################################
###                                                                          ###
### Created by Martin Genet                                                  ###
###                                                                          ###
### École Polytechnique, Palaiseau, France                                   ###
###                                                                          ###
################################################################################

# FROM registry.gitlab.inria.fr/aldabyse/fenni-paper-demos:latest
FROM ghcr.io/alexandredabyseesaram/fenni-i-paper-demo:latest

ARG NB_USER=jovyan
ARG NB_UID=1000
USER ${NB_USER}
ENV HOME /home/${NB_USER}
COPY --chown=${NB_UID} . ${HOME}
