diario-de-estudos
(ou: como eu resolvi aprender programação depois dos trinta)

- SETEMBRO
1) Para deixar registrado, estou utilizando as seguintes versões:
- Python 3.14.10
- Node 26.13.1
- npm 11.20.0
- git 2.56.1.windows.1
- code 1.148.0.661626d0e72f97806550790a98fb87116c9db825 x64

*Acho que fica mais compreensível definir as coisas de maneira mais simples. Afinal, trata-se de uma nova terminologia pra mim*

1.1. Python: É a linguagem de programação que estou aprendendo no momento. Ela se destaca por uma sintaxe bastante legível, baseada no inglês. É conhecida também por uma boa portabilidade, sendo utilizada em sistemas como Windows, MacOS e Linux. De acordo com o que tenho pesquisado, é possível utilizá-la em diversas áreas, como Inteligência Artificial, análise de dados, automação, cibersegurança, dentre outras... alguns nomes ainda são estranhos pra mim. Mas acredito que com o tempo fará mais sentido. 

1.2. Node: É o ambiente multiplataforma de execução JavaScript fora dos navegadores (uma outra linguagem de programação bastante presente no contexto da web). Em resumo, não basta escrever um código JavaScript, é preciso executá-lo. O Node.js é esse ambiente de execução. (*Será que existem outros ambientes de execução para JavaScript? Qual a diferença?*)

Além disso, o Node.js conta com um gerenciador de pacotes, chamado de NPM, abreviação de Node Package Manager. É como se fosse um kit de ferramentas para a utilização do Node.

1.3. Git: É um sistema de controle de versão instalada localmente no computador que salva os históricos de alterações em um código. É como se fosse um *save* do um videogame, com a vantagem que dá para visualizar os vários pontos de construção do percurso final. Confesso que ainda não compreendi muito bem como ele funciona, mas nas aulas seguintes, creio que ficará mais claro também.

Dúvidas: Consegui executar print("Olá, Mundo!) no terminal do VS Code. Na internet, vi algumas pessoas executando pelo CMD do próprio Windows. Toda vez que o tento fazer, a partir do comando < phyton ola_mundo.py >, recebo a seguinte mensagem: 'phyton' não é reconhecido como um comando interno ou externo, um programa operável ou um arquivo em lotes. O que estou fazendo de errado?

2) Primeiros passos com o Git Bash.

Esse vídeo tem ótimos comandos adicionais que podem ser utilizados no Git Bash: https://www.youtube.com/watch?v=ZQx7o9TMVVU

- pwd mostra o diretório atual.
- ls lista arquivos e diretórios. ls mostra as pastas, ls* mostra cada pasta com cada arquivo dentro.
- mkdir *nome da pasta* cria uma nova pasta.
- cd *nome da pasta* entra nessa pasta, cd .. volta para a pasta anterior.
- touch cria um arquivo vazio. Pode escolher o nome e formato, por ex: touch arquivo.txt
- echo é realmente um *eco* do que foi escrito. Se digo echo "mensagem", o terminal responderá com mensagem.
- OBS: se utilizo echo "mensagem" > *nome de um arquivo.formato* então cria-se esse arquivo, nesse formato, com o conteúdo echo dentro dele.
  ex: echo "essa mensagem é um teste de escrita " > leiame.txt , então será criado um arquivo de texto com a mensagem entre aspas como conteúdo.
- cat mostra o que está dentro do arquivo criado, como uma conferência. No caso acima, seria cat leiame.txt e a resposta seria "essa mensagem é um teste de escrita"
- clear limpa tudo
- rm *nome do arquivo* remove o arquivo
- mv *nome do arquivo* *novo nome* muda o nome do arquivo. Mas se eu colocar mv *nome do arquivo* *nome de uma pasta nesse diretório* o arquivo é movido.
- OBS: dá pra fazer o comando todo de uma vez, separando por ; ex: mv leiame.txt readme.txt; readme.txt *pasta de exemplo*. O arquivo muda de nome e é movido para a pasta indicada.


3) 
