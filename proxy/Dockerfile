# Image de base : nginx version 1.12
# copier default.conf dans : /etc/nginx/conf.d/default.conf
# Fichier HTML pour réponses BACKEND-NOT-FOUND : à copier dans /var/www/html/backend-not-found.html
# Configuration du proxy : copier proxy.conf dans /etc/nginx/includes/

# Utiliser l'image Nginx version 1.12
FROM nginx:1.12

# Copier le fichier de configuration default.conf
COPY default.conf /etc/nginx/conf.d/default.conf

# Copier le fichier HTML pour les réponses BACKEND-NOT-FOUND
COPY backend-not-found.html /var/www/html/backend-not-found.html

# Copier le fichier de configuration du proxy
COPY proxy.conf /etc/nginx/includes/
