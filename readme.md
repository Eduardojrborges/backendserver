Arquivos que servirão de base para implementação do servidor. Inicialmente o servidor não terá https pois sera acessado apenas pelo proxy e o proxy implementará o https,
cache e outros melhorias de segurança e perfomace.

Instalação do ambiente.

Comandos:
sudo mkdir /opt/backend_swag (criar diretorio)
sudo chown ejborge:ejborge /opt/backend_swag (trocar dono do diretorio recem criado)
Não esquecer de adicionar o usuario que usará o docker e o servidor no grupo "docker e sudo.
