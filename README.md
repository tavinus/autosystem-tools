# autosystem-tools
Scripts de suporte para Linx Autosystem
## Disclaimer
Esse conjunto de ferramentas foi desenvolvido por Gustavo Arnosti Neves para facilitar a instalação e o uso do sistema Linx Autosystem em linux (Debian, Ubuntu, Mint).  
  
Este conjunto de ferramentas não foi desenvolvido nem tem suporte oficial da ALS / Linx, que é a empresa que detém os direitos sobre o sistema autosystem. Questões de licença devem ser tratadas diretamente com a Linx e pressupõe-se que o usuário destes scripts possuem um contrato válido com a Linx para registrar o sistema ao final da instalação.  
  
O instalador utiliza o repositório Fatux para instalar o autosystem e suas dependências. Este repositório inclui outros pacotes diversos, portanto é recomendado desativar o repositório fatux depois da instalação para evitar que sejam usados seus pacotes adicionais (ao invés dos pacotes padrões de sua distribuição). 
## Ferramentas
Em construção - listar os diferentes scripts, suas funções, como instalar e como usar.
## Wiki
Em construção - vai receber os gists com tutoriais e mais outros guias.
## Gists
A maioria das ferramentas desse pacote foi criada em gists e depois migrada para este repositório.  
Os gists não receberão mais atualizações a partir da criação deste repositório.  
#### gists relacionados
 - [Instalar Linx Autosystem Debian, Mint, Ubuntu (via Repo Fatux)](https://gist.github.com/tavinus/146bdce3695cae9cfec02b534c2ff30f)
 - [Rodar Autosystem em AMD64 e ARM ](https://gist.github.com/tavinus/559c6fef56a757e524c86deffdfb9dc0)
 - [Gera Links e Lançadores para AutoSystem em chroot (jessie_i386)](https://gist.github.com/tavinus/5b2135f4363198c7356139a2399fc1ba)
 - [Reseta permissões de um Autosystem Instalado (linux) ](https://gist.github.com/tavinus/5a57c54d7303ec0a8cff9dcfc4b1bad4)
## To Do
 - Desativar repo fatux ao final da instalação por padrão, com parametro para manter
 - Comando para ativar / desativar repo fatux manualmente
 - Comando para ativar / desativar instalação do postgres (junto com autosystem)
 - Checar instalação AS sem o postgresql server para clientes (quais pacotes manter/retirar?)
 - Rodar *as_fix_permissions* ao final da instalação (talvez tenha que criar pastas e dar touch em arquivos antes)
 - Checar se devemos rodar as_fix_permissions com frequencia (reboot/cron?)
 - Comando para adicionar renovação de licença no cron (precisa CNPJ / senha, deve checar permissões)
 - Updater online via github (para autosystem-tools somente)
 - Adicionar `as_backup` incrementado nas ferramentas (não publicado em gists ainda)
