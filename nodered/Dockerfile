# Utiliser l'image officielle de Node-RED
FROM nodered/node-red:latest

# Définir le répertoire de travail
WORKDIR /data

# Copier les fichiers nécessaires (si tu as des fichiers spécifiques pour Node-RED, comme un flow)
COPY . /data

# Exposer le port 1880
EXPOSE 1880

# Lancer Node-RED
CMD ["npm", "start"]
