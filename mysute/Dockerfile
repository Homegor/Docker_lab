FROM nginx

RUN apt update && apt install -y php-fpm php-mysql php-cli php-curl php-gd php-mbstring php-xml php-zip

# Открываем порт 80
EXPOSE 80

# Запускаем Nginx (в официальном образе уже прописан CMD)
CMD php-fpm8.4 && nginx -g "daemon off;"
