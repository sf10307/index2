
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://sf10307.github.io/index2/index.html/$1 [R,L]
