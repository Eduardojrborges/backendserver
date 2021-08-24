Arquivos que servirão de base para implementação do servidor. Inicialmente o servidor não terá https pois sera acessado apenas pelo proxy e o proxy implementará o https,
cache e outros melhorias de segurança e perfomace.

Instalação do ambiente.

Comandos:
<p>sudo mkdir /opt/backend_swag (criar diretorio)</p>
<p>sudo chown ejborge:ejborge /opt/backend_swag (trocar dono do diretorio recem criado)</p>
<p>Não esquecer de adicionar o usuario que usará o docker e o servidor no grupo "docker e sudo.</p>
<p>cd /opt/backend_swag</p>
<p>git clone https://github.com/Eduardojrborges/backendserver.git . (não esquecer do ponto para clonar na pasta atual)</p>
<p>sudo rm -rf .git (escluir uma pasta desnecessaria)</p>


