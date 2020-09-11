# Instrução para realização do desafio de Desenvolvimento

O desafio tem por objetivo resolver uma problemática de um cenário presente na Justiça Federal no Rio Grande do Norte (JFRN). Esta problemática implica na entrega de um *software* desenvolvido na linguagem de programação Java, onde o cenário é descrito logo abaixo.

## PROBLEMÁTICA

<p align="center">
  <i>(Situação meramente ilustrativa)</i>
</p>

A JFRN está planejando o retorno do atendimento presencial ao público externo e para isto precisa gerenciar o controle de acesso de pessoas. As pessoas podem ser **visitantes** (advogados, partes e testemunhas) ou **funcionários** (magistrados, servidores, estagiários e colaboradores da JFRN).

De acordo com a nova portaria do Conselho Nacional da Justiça (CNJ) e devido ao atual cenário nacional da pandemia do Covid-19, o prédio sede, em Natal, só poderá comportar até **50 visitantes** simultaneamente. Este requisito não se aplica aos funcionários.

De acordo com as especificações repassadas, você foi convidado a criar um sistema Web onde seja possível gerenciar o fluxo de pessoas no prédio da JFRN, registrando a data e horário de **entrada** e **saída**. O sistema deve identificar se a pessoa que está acessando o prédio é visitante ou funcionário.

É necessário que o sistema informe a quantidade de pessoas que estão na Justiça Federal, separando-os em total de funcionários e total de visitantes.

## HABILIDADES AVALIADAS

O avaliador levará em consideração os seguintes critérios para analisar a solução entregue:

   - Sua capacidade analítica em avaliar o problema e trazer uma solução prática;   
   
   - Sua capacidade em trabalhar com estrutura de dados;
   
   - Qualidade de código, que envolve:
      - Estrutura de raciocínio lógico implementada na solução em Programação Orienta a Objetos (POO);
      - Código limpo (coesão e coerência de código);
      - Separação de responsabilidades (use boas práticas de programação).
      
Os critérios abaixo não serão avaliados, ficando o candidato livre para sua implementação.

   - Realizar comunicação com banco de dados;
   
   - Desenvolver interface gráfica para a solução desenvolvida.

## RECOMENDAÇÕES

Para avaliação plena, é necessário realizar alguns cuidados no desenvolvimento de sua solução, sendo eles:

   - **Compile em Java 8:** verifique a versão do seu Java e se possível construa a sua solução com a estrutura do Java 8, facilitará na avaliação do avaliador;

   - As API's: **JaxaFX, Swing & AWT** devem ser evitadas para elaboração e entrega desta solução;

   - **Evite arquivos desnecessários, use gitignore:** ao desenvolver soluções na linguagem Java, o interpretador da linguagem gera muitos arquivos que tem por objetivo o uso exclusivo da JVM ou da sua IDE, como por exemplos os arquivos com extensão *.class*. Neste documento indicamos o gitignore com essa configuração mínima: [clique para visualizar  um exemplo do gitignore para Java](../.gitignore);
   
   - **Se possível, use o Eclipse IDE:** o candidato tem autonomia para usar a ferramenta que mais lhe agrada. Porém, o cuidado com os arquivos gerados por causa do Ambiente de Desenvolvimento Integrado (do inglês IDE) deve ser realizado. O avaliador usará a IDE do Eclipse para avaliar as soluções;
   
   - **Javadoc e Comentário no código:** caso seja necessário, optem por comentários em português, evitem registrar comentários em inglês ou em outro idioma;
   
   - **[OPCIONAL] Soluções com interface gráfica:** o único cenário que será aceito o desenvolvimento de uma solução contendo uma interface gráfica é o desenvolvido em *JavaServer Faces* (*JSF*). Soluções entregues com JavaScript, Angular, Vue JS, PHP ou outra linguagem fora do ecossistema Java, serão ignoradas;
   
   - **Não bloquear conteúdo com senha de acesso:** Se for enviar a solução em arquivo compactado (.zip), gere-o sem senha.

<p align="right">
  <i>Boa sorte!</i>
</p>
