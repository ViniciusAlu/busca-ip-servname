Aplicação CLI desenvolvida em Go que realiza consulta DNS para obter o endereço IP e o nome do servidor(hostname) de um site informado pelo usuário.
Funcionalidades:
  Busca IP de um domínio;
  Consulta ao nome doo servidor associado ao IP;
  Interface simples via linha de comando.

Pré Requisitos:
  Go(Golang) instalado(versão 1.6 ou superior);
  Acesso ao Terminal/shell (Linux, macOS ou Windows).

  Exemplo de uso:
    ./linha_comando ip --host google.com
    ./linha_comando servidores -- host google.com
  Saida:
    142.250.219.206
    ns1.google.com
