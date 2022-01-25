
## Notas de aula referentes ao módulo 1 do curso git & github da potência feminina

Git é um sistema de controle de versão.

Github é uma plataforma de hospedagem de codigo-fonte e arquivos com controle de versão utilizando o Git.

## VERSIONAMENTO
Versionamento de software é um processo de controle de versões, definido através de "numerações" de históricos diferentes.

Tudo que a gente adiciona no git (comit?) algo e ele reconhece como uma mudança, esse código vai ganhar uma numeração. Quer dizer determinado estado do seu código tem aquela numeração. Esse código nunca irá se repetir. Ele diz quem fez a alteração, quando e o que foi alterado também (quando trabalha em grupo, isso ajuda).

Da para voltar para versões anteriores.

Não basta salvar a alteração para o git entender como uma mudança. Você tem que adicionar e "comitar" para ele entender que é uma mudança.

## REPOSITÓRIO
Repositório é a pasta onde a gente armazena nosso  projeto. Dentro de um repositório, os projetos podem se dividir em módulos e outras divisões específicas para cada tipo de projeto.

Todo repositório tem um arquivo .git, isso quer dizer que esse repositório é "rastreável" para o Git.

## COMMIT
Commit é um conjunto de alterações no código.

Toda vez que você salva/registra as alterações no projeto, você comita essas alterações.

Um commit tem as alterações que são realizadas nele e uma mensagem descritiva, além de informações sobre o autor, a data, etc.

Change(Diff): O Git mantém o controle de versão rastreando as alterações e diferenças entre as versões dos arquivos "cadastrados" nele.

O que o git entende como alteração de arquivo? Criação, renomeação ou exclusão de arquivos. Inserção ou exclusão de uma linha em um arquivo (uma linha modificada é uma inserção e exclusão)

## BRANCH
Branchs são separações de código, com elas é possível que várias pessoas atuem em um mesmo projeto independentemente
A Branch inicial de todo projeto é a branch master, nas empresas geralmente criamos branchs de acordo com o ambiente que esse código será disponibilizado.
TIPOS DE BRANCH:
Develop: ambiente para uso em tempo de desenvolvimento.
Depois de testar o que desenvolvemos em nossa máquina (ambiente local), o código é disponibilizado nesse ambiente.
Homolog: Após as alterações serem validadas em ambiente de desenvolvimento, o código vai para a branch/ambiente de homologação, onde pessoas de negócio podem validar a solução e pessoas da área de qualidade efetuam mais testes para validar a solução.
Master: É a branch principal do nosso projeto, geralmente os códigos contidos nela são os que vão para a produção. Produção é o site que é disponibilizado para o público.

A equipe de desenvolvimento cria novas branchs para separar e desenvolver novas soluções para um produto de forma simultanea, bem como melhorar funcionalidades já existentes, trabalhando de forma paralela e independente.

## MERGE
Como os commits dessas branchs se unem? Através do Merge.

Merge: Geralmente é utilizado para juntar alterações de duas branchs em que duas pessoas estavam atuando simultaneamente.

## CLONE
Clone: Podemos transferir o repositório que está no github para nosa máquina local através de um clone.
Dessa forma, teremos acesso ao repositório localmente, podendo realizar alterações e envia-las para o github quando desejar.

Mas como eu continuo atualizada com o meu repostório remoto?

Realizando um Pull:
É realizado um merge entre o repositório online (github) com o que temos localmente, dessa forma, evitamos conflitos, estaremos com o conteúdo atualizado e poderemos enviar nossas futuras alterações.

Mas como eu envio as alterações que eu comitei localmente para a minha origem remota?

Realizando um push:
Com o comando git push podemos enviar nossas alterações locais para o nosso repositório remoto.

Dessa forma o seu repositório remoto estará atualizado com a sua versão local, e outras pessoas que forem acessar ele poderão ter uma versão mais atualizada.

Mas como posso contribuir com o repositório de outras pessoa?
Fazendo um fork:
O Fork é bem semelhante ao clone, porém ele só ocorre na interface gráfica do github.
O repositório não será baixado para o seu computador, mas você terá uma cópia dele na sua conta do github.

Depois de "Forkar" um repositório de outra pessoa, você pode fazer pull-requests para contribuir com o conteúdo no repositório principal.

Mas como posso enviar uma contribuição para o repositório de outra pessoa?
Fazendo uma pull request:
Após "forkar" o repositório de outra pessoa, podemos resolver issues dele e fazer pull requests enviando soluções para erros e adicionando novos conteúdos.

A pessoa dona do repositório irá avaliar sua pull request e, se estiver ok, será mergeada no repositório principal.
