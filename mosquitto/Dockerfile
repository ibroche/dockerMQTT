# Utiliser l'image officielle de Mosquitto
FROM eclipse-mosquitto:latest

# Copier le fichier de configuration mosquitto.conf (si tu as un fichier local)
COPY ./mosquitto.conf /mosquitto/config/mosquitto.conf

# Exposer le port 1883 pour le service MQTT
EXPOSE 1883

# Démarrer Mosquitto
CMD ["mosquitto", "-c", "/mosquitto/config/mosquitto.conf"]
