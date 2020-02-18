# docker-php7.4-PG-nginx
<h1>Docker container for symfony and laravel applications</h1>
<p>As a database used a Postgres. As a server used NGINX. As a database manager used Adminer</p>
<p>Php container has preinstalled composer, and you can can use it utside a container.</p>
<p>
  Example <br>
  <code>docker-compose exec php composer install </code>
</p>
<p>Also you can call for execution php scripts placed in app directory</p>
<p>
  Example <br>
  <code>docker-compose exec php php bin/console doctrine:schema:create</code>
</p>
