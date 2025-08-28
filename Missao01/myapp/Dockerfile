# Imagem oficial do python
FROM python:3.11-slim

# Define o diretório do trabalho dentro do container 
WORKDIR /app

# Copia os arquivos do projeto para dentro do container
COPY . .

# Instala o Flask
RUN pip install flask

# Expõe a porta 5000
EXPOSE 5000

# Comando para rodar o app
CMD ["python", "app.py"]

