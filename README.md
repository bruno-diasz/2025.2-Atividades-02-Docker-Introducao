
# Relatório da Atividade Avaliativa 01 de S.O.

> Bruno Natanael Gomes Dias, 19/09/2025.

## Introdução

&nbsp;&nbsp;&nbsp;&nbsp;O exercicio tem como objetivo incentivar a prática de comandos basicos do linux(Fedora) em um ambiente controlado de container docker, onde o exercicio vai desde da criação do container e execução até o por exemplo controle de permissão dos linux.

## Relato

1. Iniciando utizamos o comando `pwd`, que é responsavel por retornar o diretorio atual em que estamos, que no caso atual é o diretorio raiz "/".

   ![image01](/photos/img01.png)
   ---

1. O comando `cd ~` faz com que o diretorio da Pasta do usuario "~", seja aberta.

    ![image02](/photos/img02.png)
   ---


1. Logo em seguida utilizamos o comando `ls` para listar tudo que o diretorio atual contem

    ![image03](/photos/img03.png)
   ---

1. O comando `mkdir` é utlizado para a criação de um novo diretorio ou pasta chamado "atividades".

   ![image04](/photos/img04.png)
   ---

1. Utilizando novamente o comando `cd` para adentrar o novo diretorio criado.

   ![image05](/photos/img05.png)
   ---

1. Utilizando novamente o comando `cd ..` so que dessa vez utilizando o ".." para representar o diretorio pai.

   ![image06](/photos/img06.png)
   ---

1. O comando `pwd` sendo utlizado novamente para mostrar onde o ".." nos trouxe.

   ![image07](/photos/img07.png)
   ---
1. Aqui conseguimos vizualizar o novo comando `touch` sendo utilizado para a criação de um arquivo de texto no diretorio pessoal do root.

   ![image08](/photos/img08.png)
   ---
1. Em sequencia foi utlizado o comando `mv` para renomear o arquivo de "arquivo.txt" para "documento.txt".

   ![image09](/photos/img09.png)
   ---
1. Entramos no diretorio "atividades usando o `cd`.

   ![image10](/photos/img10.png)
   ---
1. Nessa imagem aconteceram dois comandos , sendo um deles criação da pasta "backup" utilizando o `mkdir` e alem disso foi feito uma copia do arquivo "documento.txt" utlizando o `cp` para dentro dessa pasta no printa é mostrado o que conta nessa pasta.

   ![image11](/photos/img11.png)
   ---
1. Outra vez novamente retornamos para o diretorio de home do usuario root usando o `cd`.

   ![image12](/photos/img12.png)
   ---
1. Nessa imagem é utilizado o comando `rm` para a remoção do arquivo "documento.txt" do diretorio home.

   ![image13](/photos/img13.png)
   ---
1. Nessa imagem é possivel que o arquivo que foi feito a copia não foi removido junto com ele.

   ![image14](/photos/img14.png)
   ---
1. Nessa parte eu utilizei o comando `tree` que não é um comando nativo do fedora, mas que foi instalado para ser possivel vizualizar vizualmente a estrura de diretorios.

   ![image15](/photos/img15.png)
   ---
1. Iniciando um novo tópico iniciamos a parte de pacotes, na figura a abaixo foi utilizado o comando `dnf update -y` que é utlizado para atualizados todos os repositorios de pacotes.

   ![image16](/photos/img16.png)
   ---
1. O comando `dnf install -y` que é utlizado para instalar um novo pacote no sistema, no qual no exemplo é usado o programa "nano" que é utilizado para edição de texto.

   ![image17](/photos/img17.png)
   ---
1. Comando simples para vizualizar a versão de um pacote `nano --version`.

   ![image18](/photos/img18.png)
   ---
1. Utilizando esse comando `dnf remove [nome do pacote]`, é possivel remover os pacotes que foram instalados do sistema.

   ![image19](/photos/img19.png)
   ---
1. Iniciando a parte de permissão de usuario o comando `ls -l [nome do arquivo]` é responsavel por mostrar as permissões que o usuario tem de um arquivo.

   ![image20](/photos/img20.png)

1. O `chmod` foi utlizado para adicionar a permissão de execução dessa arquivo ao usuario atual, alem disso ele tambem consegue remover a permissão e adicionar outra para usuarios especificos os grupos.

   ![image21](/photos/img21.png)
   ---
   
1. Utilizamos o comando `ps aux` para vizualizar as lista de processos em sua maquina.

   ![image22](/photos/img22.png)
   ---
1. Enquanto isso utlizamos o comando `sleep 60 &` somente para ver um novo processo sendo criado e mostrado no ps, esse comando é reponsavel por não fazer nada durante um intervalo de tempo.

   ![image23](/photos/img23.png)
   ---



1. Em seguida utlizamos o "ps" seguido do comando `| grep` para fazer uma filtro na saida do ps onde será possivel encontrar o processo com mais facilidade.

   ![image24](/photos/img25.png)
   ---

1. Logo então foi utilizado o comando `kill` juntamente com o id do processo para encerra-lo.

   ![image25](/photos/img26.png)
   ---

## Conclusão

&nbsp;&nbsp;&nbsp;&nbsp;Com isso consegui aprender como navegar por diretorios no linux, criação e exclusão de pastas, criação e exclusão de arquivos simples, instalação e remoção de pacotes, listagem e manipulação de processos. Felizmente não tive dificuldade para executar a atividade proposta, e achei bem bacana como funciona a parte das permissões no linux.

<!-- - Cabeçalho: título da atividade, nome, data
- Introdução: objetivo do exercício
- Relato: descreva as suas atividades e mostre os resultados com as imagens capturadas
- Conclusão: O que aprendeu? Dificuldades? -- >
