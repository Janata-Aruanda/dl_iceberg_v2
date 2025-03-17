FROM bitnami/spark:3.4.1

# Instala o curl
USER root
RUN apt-get update && apt-get install -y curl

# Configurar o PATH do Spark
ENV PATH="/opt/bitnami/spark/bin:${PATH}"

# Não é necessário baixar o Delta Lake manualmente
# O Delta Lake será fornecido via pip install no Jupyter