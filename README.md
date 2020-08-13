# QA Engineer Code Challenge - LEVEE

Através desse desafio, queremos conhecer suas habildades de escrever cenários e automatizar testes.

## Sem tempo para realizar o desafio?

Você pode enviar o link de um pull request com uma contribuição sua para qualquer projeto Open Source ou algum projeto próprio que você acredita que demonstre o seu nível técnico e a qualidade do seu código. Lembre-se que quanto mais código seu pudermos visualizar, melhor será para te avaliarmos. :)

## Sobre o desafio

* Planejamento dos testes

    * Sua missão é escrever os cenários de teste e definir estratégias com base na necessidade de negócio descrita na história e critérios de aceitação abaixo:
    
    **Nome da História:** `Postagem de vaga` 
    
    **Descrição:**
    ```
    Eu como usuário Recrutador ou Suporte gostaria de ter permissão de cadastrar uma nova vaga para que 
    seja possível divulgar as novas posições de emprego disponível na empresa.
    ```
    
    **Critérios de Aceitação:** 
 
         01. Novos/antigos usuário suporte devem poder postar novas vagas auto ou custom completas, em
         qualquer empresa cadastrada na plataforma;
         
         02. Novos/antigos usuário suporte devem poder postar novas vagas auto ou custom a partir de um
         template, em qualquer empresa cadastrada na plataforma;
         
         03. Novos/antigos recrutadores com perfil Complete devem poder postar novas vaga auto ou custom
         completas, em qualquer unidade cadastrada na empresa na qual possui cadastro;
         
         04. Novos/antigos recrutadores com perfil Complete devem poder postar novas vagas auto ou custom
         a partir de um template, em qualquer unidade cadastrada na empresa na qual possui cadastro;
         
         05. Novos/antigos recrutadores com perfil Intermdiário devem poder postar novas vagas auto ou 
         custom apenas na unidade da qual faz parte;
         
         06. Novos/antigos recrutadores com perfil Intermdiário devem poder postar novas vagas auto ou 
         custom a partir de um template, apenas na unidade da qual faz parte;
         
         07. Novos/antigos recrutadores com perfil Básico devem poder postar novas vagas auto ou custom 
         somente a partir de um template, apenas na unidade da qual faz parte;
         
         08. Usuários suporte deve poder gerenciar todas as vagas postadas pelas empresas;
         
         09. Recrutador com perfil Complete deve poder gerenciar todas as vagas postadas pela sua empresa;
         
         10. Usuários Intermediário deve poder gerenciar as vagas postadas por ele e todas postadas e em
         sua unidade;
         
         11. Usuários Básico deve poder gerenciar apenas as vagas cadastradas por ele;
         
         12. Todas as vagas quando postadas permanecem com status "Pendente/Aberta" até a aprovação e é
         possível fazer edição dos dadaos e copiar a vaga, para postar outra vaga com informações iguais;
         
         13. As vagas com status "Pentente/Aberta" só poderão ser "Aprovadas" por um usuário Suporte e a
         mesma passará ao status "Aberta/Em andamento" não podendo mais ser editada";
         
         14. As vagas custom após aprovadas permanecem com status "Aberta" na plataforma, só mudará para 
         "Em andamento" quando existir ao menos uma data de entrevista cadastrada.
         

* Automação dos testes **(fique a vontade para escolher entre o site ou no nosso APP Android para fazer a automação das funcionalidades)**


    * Cadastrar novo candidato:
    
      No site abaixo, existe uma funcionalidade que permite que os nossos candidatos façam o cadastro para se candidatarem às vagas.
      
      https://www.empregoligado.com.br/
      
      https://play.google.com/store/apps/details?id=com.el.empregoligado

      Com base nessas informações, crie seus testes automatizados. Faça as validações necessárias.


    * Login candidato:
      
      No site abaixo, existe uma funcionalidade que permite que os nossos candidatos já cadastrados possam fazer login para se     candidatarem às vagas.
      
      https://www.empregoligado.com.br/
      
      https://play.google.com/store/apps/details?id=com.el.empregoligado

      Com base nessas informações, crie seus testes automatizados. Faça as validações necessárias.
      

    * Fazer automação da API:

      A API abaixo é publica e faz a listagem dos nossos jobs cadastrados.

      https://apigw.prod.empregoligado.net/applicant/api/v1/public/jobs

      Crie um teste para listar os Jobs e um teste que mostre os detalhes de um Job, utilizando a API. Valide as requisições através do response code e do response body.
      
      Agora gostariamos de analisar um pouco mais seus conhecimentos em automação de microsserviços, então escolha uma API pública e automatize alguns métodos, por exemplo: POST, PATCH, PUT, DELETE, etc. 

## Pré-requisitos

O seu teste deve ter um README com os passos necessários para:
* Instalar as dependências;
* Rodar os testes automatizados.

## Tecnologia

Sinta-se livre para usar a linguagem e as bibliotecas que preferir.

Bônus hints:

* Gostamos de page objects;
* Gostamos de Cucumber;
* Commits estruturados são bem legais.

## O que está sendo avaliado

Nesse desafio queremos avaliar sua habilidade de planejar/levantar cenários de testes e definir estratégias, além de avaliar o seu conhecimento em automação de testes.

Vamos avaliar tudo o que você fizer. Envie o que conseguir realizar, mesmo que você não consiga completar todas as tarefas do desafio.

## Para nos enviar seu código, você pode:

* Fazer um fork desse repositório e nos mandar um pull request.
* Se precisar falar com a gente: engenharia@levee.com.br.
