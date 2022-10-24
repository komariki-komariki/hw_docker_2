# Сборка образа
docker build ./ --tag hw

# Запуск контейнера
docker run -d -p 8000:8000 hw
