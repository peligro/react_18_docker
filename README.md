<hr />
<h1>React con Docker</h1>
<hr />
<p>
Crear imagen :
<code>docker-compose up --build --no-recreate -d</code>
</p>
<hr/>
<p>
Desde la segunda vez en adelante :
<code>docker-compose up -d</code>
</p>
<hr/>
<p>
Para ejecutar la aplicación :
<code>docker exec -it vite_docker sh</code>
<br/>
<code>npm i && npm run dev</code>
</p>
<hr />
<p>
Para bajar el contenedor usamos:<br />
<code>docker-compose down</code>
</p>