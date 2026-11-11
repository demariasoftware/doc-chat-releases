# DOC-Chat — releases

Este repositório contém apenas as **versões publicadas** do DOC-Chat (instalador do aplicativo e pacote do servidor), assinadas digitalmente. Não há código-fonte aqui.

Os servidores DOC-Chat consultam este endereço por conta própria, conferem a assinatura de cada versão e só então a aplicam. Quem usa o aplicativo não precisa baixar nada manualmente: o aplicativo é instalado e atualizado pela equipe de suporte.

Cada release traz:

- `release.json` e `release.json.sig`: lista dos arquivos, com tamanho e SHA-256, e a assinatura da lista;
- `DocChat-Server-<versão>.zip`: pacote do servidor;
- `DOC-Chat_<versão>_x64-setup.exe` e `.sig`: instalador do aplicativo e sua assinatura;
- `latest.json` e `latest.txt`: arquivos de controle das atualizações.

Uma versão sem a assinatura correta é recusada pelos servidores e pelos aplicativos.
