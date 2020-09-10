<p align="center">
  <img src="../material-de-apoio/img/jfrn_logo.png" />
</p>


# DESAFIO: DESENVOLVIMENTO :octocat:

O desafio tem por objetivo resolver uma problematica de um cenário presente na Justiça Federal no Rio Grande do Norte (JFRN). Esta problemática implica na entrega de um software desenvolvido na linguage de programação Java, onde o cenário é descrito logo abaixo. 

## PROBLEMÁTICA

<p align="center">
  <i>(Situação meramente ilustrativa)</i>
</p>


A JFRN está planejando o retorno do atendimento presencial ao público externo, e para isto precisa gerenciar o controle dos visitantes e funcionários dentro do prédio da JFRN, de acordo com a nova portaria do *Conselho Nacional da Justiça* (CNJ) e devido o atual cenário nacional da pandemia do Covid-19,  os prédios do judiciário só poderão comportar até 50 **usuários externos** dentro do prédio da JFRN e para **funcionários (servidores, estagiários, terceirizados e trabalhadores da JFRN)** este limite não é imposto.

De acordo com as especificações repassadas, se faz necessário a criação de um sistema desenvolvido na linguagem Java, que insira ou que já tenha inserido em uma lista ou em um Banco de Dados, os usuários que entrarão na JFRN, esses usuários poderão ser **usuário externo** ou **funcionários**, o sistema deve identificar se o usuário que está entrando é visitante (**usuário externo**) ou é um **funcionário**  de acordo com os dados já cadastrados no sistema (que serão consumidos de uma lista ou de um banco de dados). 

Para controle de acesso, o sistema precisará incluir registro de **entrada** e **saída** para os **usuários externos** e **funcionários**, ~podendo ter apenas 50 **usuários externos** dentro do prédio da JFRN e não limitando a entrada para **funcionários**, entretanto, o sistema não deve impedir a entrada de **usuários externos** dentro da JFRN se a soma de **funcinários** e **usuários externos** dentro da JFRN ultrapassar a quantidade de 50, o sistema deverá fazer a verificação apenas se há uma quantidade máxima de 50 visitantes como **usuários externos** dentro do próprio da Justiça.~

É necessário que o sistema informe a quantidade de pessoas dentro da justiça, informando quantos **funcionários** estão na justiça, quantos **usuários externos** e também informando o quantitativo total (a soma dos **funcinoários** e **usuários externos** dentro da justiça).  

## HABILIDADES AVALIADAS

Os avaliadores levarão em consideração os seguintes critérios para valorização da sua solução:

   - Sua capacidade análita em avaliar o problema e trazer uma solução prática;
   
   - Sua capacidade em trabalhar com estrutura de dados;
   
   - Qualidade do código da solução entregue, que envolve:
      - Estrutura de raciocínio lógico para implementação de solução para **P**rogramação **O**rienta a **O**bjetos (**POO**);
      - Código limpo (Coesão e coerencia do código, assim como também boa documentação);
      - Separação de responsabilidades (cada fluxo lógico deve está envolvido no que lhe cabe, use boas práticas de POO).
      
Os critérios abaixo não impactaram em alteração de nota, ficando o candidato livre para sua implementação ou não.

   - Implementação de comunicação com Banco de Dados;
   
   - Confecçao de interface gráfica para solução desenvolvida.
      

## RECOMENDAÇÕES

Para avaliação plena, é necessário realizar alguns cuidados na confecção de sua solução, sendo eles:

   - **Compilar em Java 8:** verifique a versão do seu Java e se disponível e possível construa a sua solução em estrutura do Java 8, vacilitará na avaliação pelos supervisores;

   - As API's: **JaxaFX, Swing & AWT** devem ser evitadas para elaboração e entrega dessa solução;

   - **Evite arquivos desnecessários, uso gitignore:** ao desenvolver soluções na linguagem Java, o interpretador da linguagem gera muitos arquivos que tem por objetivo uso exclusivo da JVM ou da sua IDE, como por exemplos os arquivos com extensão *.class*, neste documento indicamos o gitignore com essa configuração mínima: [clique para visualizar  um exemplo do gitignore para Java](../.gitignore);
   
   - **Se possível, use o Eclipse:** o candidato tem autonomia para usar a ferramenta que mais lhe agrada, porém, o cuidado com os arquivos gerados por causa do Ambiente de Desenvolvimento Integrado (do inglês IDE) deve ser realizado. A fiscalização usará a IDE do Eclipse para avaliação dos trabalho;
   
   - **Javadoc e Comentário no código:** optem por comentários na lingua português do Brasil, evitem registrar comentários em inglês ou em outra língua;
   
   - **Soluções com interface gráfica:** o único cenário que será aceito o desenvolvimento de uma solução contendo uma Interface Gráfica e os desenvolvidos em *JavaServer Faces* (**JSF**), soluções de interface gráfica entregues com JS, Angular, Vue jS, PHP e outros fora do ecosistema Java, serão ignoradas;
   
   - **Bloquear conteúdo com senha de acesso:** este desafio não avalia o grau de segurança da informação da solução entregue, então implementações de lógica de segurança, como: área de login na aplicação com autenticação, filtros de segurança na aplicação e implementação do Spring Security ou alguma biblioteca que tenha este objetivo, devem ser evitadas. Se for enviar a solução em arquivo compactado (.zip), gere-o sem senha.

## ENVIO

Para envio da solução do problema de desenvolvimento, é necessário ter realizado a [escolha prévia das especializações](../README.md#2---envio-das-escolhas), garantido a sua participação nesta especialização especificava, o usuário deverá enviar um e-mail de resposta da solução, seguinte as seguintes regras:

#### Diponibilização do Código Fonte

O candidato poderá escolher uma das três formas para enviar a solução desenvolvida:

   - **E-mail**: compacte a solução com o código fonte e os arquivos necessários para compilação da solução em um arquivo **.zip**, (re)nomeie esse arquivo para "solução desenvolvimento {seu_nome_completo}", anexe o arquivo zipado no e-mail de resposta desafio desenvolvimento. (Obs. atente-se ao tamanho de sua solução, alguns servidores de e-mail limitam o envio de anexo a uma quantidade definida por eles)

   - **Nuvem**: compacte a solução com o código fonte e os arquivos necessários para compilação da solução em um arquivo **.zip**, (re)nomeie esse arquivo para "solução desenvolvimento {seu_nome_completo}", faça upload do arquivo zipado em uma das plataformas de carregamento de arquivos na nuvem (Google Driver, OneDriver, etc.) a qual podem gerar link compartilhado, gere um link compartilhado para download e adicione esse link a mensagem do e-mail de resposta desafio desenvolvimento.
   
   - **Github**: se você é usuário do github e pensa em desenvolver a sua solução usando essa plataforma, então garanta que o seu repositório do desafio esteja privado (com visualização bloqueada para usuários que não receberem convite de colaboração), e envie um convite de colaboração para sua solução em *Manage access* (Gerenciar acesso) para o usuário [jackson-roberio](https://github.com/jackson-roberio).

   
#### Envio da resposta (e-mail de resposta desafio desenvolvimento)

   - **O e-mail** deve ser enviado à selecaoestagio@jfrn.jus.br;
   - **O assunto (título da mensagem)**: Resposta da solução de desenvolvimento por {seu_nome_completo}
   - A mensagem deve ser
   

**Obs. o candidato terá até 24h00 após as instruções repassadas por e-mail**
