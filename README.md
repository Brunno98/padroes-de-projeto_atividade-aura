# padroes-de-projeto_atividade-aura

Nome: Brunno Santana Soares  
Matricula: 202002770317  
Curso: Ciência da computação  
Disciplina: Padrões de Projetos de Software Com Java  
Unidade: Nova América  
Professor: Ronaldo Santos  

---

## Enunciado da atividade:

Crie um repositório (google drive, GitHub, etc.), elabore um documento com seus dados acadêmicos (matrícula, nome, curso, disciplina, unidade, Professor) e responda as questões das atividades autônomas Aura das Aulas 09 a 12. Enviar o link do repositório apenas. Valerá até 3,0 pontos para a AV.

---

### Aula 9:

Questão 1: Uma das fontes de informação acerca do clima são as boias meteorológicas de alto 
mar, que emitem sinais para alguns satélites, e estes enviam as informações para um receptor 
em terra, de forma codificada. De uma forma simples, temos uma cadeia de caracteres, onde 
as letras iniciais definem um evento, seguido de parâmetros que podem ser numéricos ou 
literais, em quantidades e tamanhos diversos, obedecendo a padronização para cada tipo de 
evento.
Qual padrão de desenvolvimento seria indicado para o decodificador do sistema?  
Resposta: **D) interpreter**

Questão 2: Os frameworks se tornaram muito comuns na área de desenvolvimento, onde no Java temos 
exemplos como Spring, Struts e Hibernate. Eles definem um arcabouço com todas as funcionalidades 
comuns para determinado domínio de problemas, mas permitem ao desenvolvedor especializar a 
implementação original, para satisfazer aos requisitos apresentados pelo sistema. Na construção do 
framework, um padrão de desenvolvimento muito utilizado é o Template Method.
Qual é a afirmação correta acerca do Template Method?  
Resposta: **A) O padrão define um algoritmo dividido em vários passos, onde alguns desses passos são a implementação 
da parte comum, enquanto outros são lacunas a serem preenchidas pelo desenvolvedor.**

### Aula 10:

Questão 1: Uma abordagem comum para o acesso ao banco de dados, nos sistemas atuais, é a
concentração das operações com uso de SQL (Structured Query Language) em uma classe do
tipo DAO (Data Access Object), que deve se comunicar com o restante do sistema através de
entidades ou coleções delas.
Qual padrão GRASP se mostra predominante nesse contexto?  
Resposta: **B) Especialista na Informação**

Questão 2: Alocação de memória é um dos processos mais caros para a execução de sistemas, exigindo
muitas operações envolvendo a CPU e o barramento. Saber onde criar os objetos, para que tenhamos
maior visibilidade e menor número de instâncias, pode ser um fator decisivo na eficiência do sistema, e
o padrão Criador, do GRASP, define boas práticas no que tange ao assunto.
Qual a opção correta acerca do padrão de desenvolvimento Criador  
Resposta: **B) Tem como objetivo garantir baixo acoplamento entre as classes**

### Aula 11:

Questão 1: Um dos ferramentais mais interessantes da orientação a objetos é a herança, pois
permite alto reuso estrutural, diminuindo de forma considerável o tempo utilizado no
desenvolvimento de um sistema. Apesar de oferecer uma grande vantagem em termos de reuso,
a criação de uma grande hierarquia de classes pode dificultar ações de manutenção, pois
qualquer modificação repercute em todos os descendentes.
Qual padrão do GRASP estaria sendo violado nessa situação?  
Resposta: **E) Acoplamento Fraco**

Questão 2: Um código bem escrito é sempre mais fácil de manter, pois a semântica adequada facilita a
compreensão das entidades e dos processos que atuam sobre elas. Utilizar nomes compreensíveis,
manter os objetos focados em seus reais objetivos e definir um ambiente facilmente gerenciável, estão
entre os muitos elementos que podem ser utilizados para melhorar a semântica e facilitar o uso dos
objetos.
Qual padrão do GRASP demonstra esse tipo de preocupação?  
Resposta: **D) Coesão Alta**

### Aula 12:

Questão 1: A orientação a objetos tem uma característica adaptativa muito forte, baseada na
alteração funcional de métodos herdados, sem modificação de assinaturas, para que os
descendentes possam ser utilizados em um novo contexto de forma automática.
Qual padrão do GRASP se baseia nessa característica?  
Resposta: **C) Polimorfismo**

Questão 2: Nem sempre é fácil garantir acoplamento baixo e alta coesão. Por exemplo, em um
sistema para controle de vendas, teríamos a definição do Especialista na Informação com base na
classe Venda, já que ela detém os dados necessários, mas isso poderia trazer uma dependência
dos componentes JDBC.
Como o padrão Invenção Pura seria utilizado para resolver esse problema?  
Resposta: **A) Utilizando o polimorfismo e acrescentando a persistência no descendente.**