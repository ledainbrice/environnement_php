
démarrer l'env de dev:
- docker-compose up -d

l'arrêter avec:
- docker-compose down


pour executer une commande dans un service: 
- docker-compose exec -ti app bash
- docker-compose exec app artisan migrate 