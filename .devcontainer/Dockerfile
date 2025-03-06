FROM quay.io/jupyter/base-notebook

USER root

RUN apt-get update && apt-get install -y nodejs npm

RUN groupadd jovyan && usermod -g jovyan -a -G users jovyan

USER $NB_UID
RUN pip install jupysql duckdb duckdb-engine matplotlib seaborn plotly rich --quiet

WORKDIR /home/jovyan/work/