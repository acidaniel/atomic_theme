# atomic_theme

cd <root_projects>
git clone <repositorio>
cd <project_path>
cp ~/Downloads/composer.json <project_path>
vim .env
edit .env as needed.
docker-compose up --build
cd ..									// Change the permitions on the whole project
chown -R user:group <project-name>
cd <project_path>
docker-compose exec php bash
composer install
The host must be mariadb
