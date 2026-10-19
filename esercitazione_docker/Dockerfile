# Imposta l'immagine di base (nginx basato su alpine, che è molto leggero)
FROM nginx:alpine

# Definisce la directory di lavoro all'interno del container in cui opero
WORKDIR /usr/share/nginx/html

# Copia il file index.html dal mio computer (host) all'interno del container
COPY index.html .

# Dichiara la porta su cui il servizio ascolterà le connessioni
EXPOSE 80

# Specifica il comando predefinito eseguito all'avvio del container per mantenere attivo il server
CMD ["nginx", "-g", "daemon off;"]