##Editor en windows vim


##ssh-keygen -t rsa -C "watatarir@gmail.com"
Creamos un llave para ssh:
despues no masnda un mensaje:
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/rosendocruz/.ssh/id_rsa): /Users/rosendocruz/Documents/WebGithub/github_rsa 
y le mandamos la ruta en donde se almacenara la llave tambiem ponemos el monbre de la llave(github_rsa):
/Users/rosendocruz/Documents/WebGithub/github_rsa 

##cat github_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDELF6o2pg6qyHrEL/BZzSEZrfx/0h9u87QQf3EPiqo0QQzzc5s+hKfZNEM7C4kyUciGiyc6KGhV1nB8X34INrq/4bpvvUqZyPd+TilHAkPbOggMePP50HwQMNInqK0vcYheWsJvCoLeJfwjmMoYa9TDIgag7O62G8EZ/LjnkRFl55z0tMvpvqY1bSxMrwChQaMQ77s2iAC3VrLDKK+W7Ik/D7e1iJ8EKB0KDawQ/1JAtObE8FS846YL5lPTOiWIygtiSejhaCmdRMBBBKgdcPQpIPPyem1bOe8ki8hkVt15zhrOU7/ShCb+z0CNJPvosJDaYBqP5a2MKgBdoAFzkP1 watatarir@gmail.com

``Muestra el contenido de la llave  la cual debemos de gregar a git hub``


##eval "$(ssh-agent -s)"
dar de alta el agente de ssh

##ssh-add /Users/rosendocruz/Documents/WebGithub/github_rsa
##ssh-add /Users/rosendocruz/Key_GitHub/github_rsa

Agregar la llave ssh
