 <h1 align="center"> :blue_heart: Projeto: Formação SQL Database Specialist - DIO. :blue_heart:<br/>
 </h1>

<h2 align="center"> 💛👩‍💻🧡 Repositório referente à personalização de Banco de Dados com índices e procedures.  🧡👩‍💻💛 </h2><br/>


***<h2> 📚 Módulo: Técnicas avançadas em Banco de Dados com MySQL. </h2>***



<h5> :blue_book: Parte 1 – Criando índices em Banco de Dados. </h5>

Criação de índices para consultas do cenário de company com as perguntas (queries sql) para recuperação de informações. Sendo assim, dentro do script são criados os índices com base na consulta SQL.  

O que será levado em consideração para criação dos índices? 

:ballot_box_with_check: Quais os dados mais acessados.<br/> 
:ballot_box_with_check: Quais os dados mais relevantes no contexto.<br/><br/>

<h5>:small_red_triangle: Importante::small_red_triangle:</h5> <h6> Função do índice:</h6> Impactar diretamente na velocidade da busca pelas informações no SGBD. Portanto, criação de apenas aqueles que são importantes, que poderá ser via ALTER TABLE ou CREATE Statement, como segue o exemplo: 

:heavy_check_mark: ALTER TABLE customer ADD UNIQUE index_email(email);<br/> 
:heavy_check_mark: CREATE INDEX index_ativo_hash ON exemplo(ativo) USING HASH;<br/> 

<h5> Questionamentos:</h5> 

:ballot_box_with_check: Qual o departamento com maior número de pessoas? <br/>
:ballot_box_with_check: Quais são os departamentos por cidade? <br/>
:ballot_box_with_check: Relação de empregrados por departamento. <br/>

 
<h5> :blue_heart: Entregável:  </h5>
:ballot_box_with_check: Criação de queries para responder às perguntas acima.<br/>
:ballot_box_with_check: Criação de índice para cada tabela envolvida (de acordo com a necessidade).<br/>
:ballot_box_with_check: Tipo de índice utilizado e motivo da escolha (via comentário no script ou readme).<br/><br/><br/>

 
<h5> :blue_book: Parte 2 - Utilização de procedures para manipulação de dados em Banco de Dados. </h5>

Objetivo: Criação de uma procedure que possua as instruções de inserção, remoção e atualização de dados no banco de dados. As instruções devem estar dentro de estruturas condicionais (como CASE ou IF). Além das variáveis de recebimento das informações, a procedure deverá possuir uma variável de controle. Essa variável de controle irá determinar a ação a ser executada. Exemplo: opção 1 – select, 2 – update, 3 – delete. Sendo assim, alteração da procedure para receber as informações supracitadas. 

 
<h5> :blue_heart: Entregável:  </h5> 
Script SQL com a procedure criada e chamada para manipular os dados de universidade e e-commerce. Podendo ser possível a criação de dois arquivos distintos, assim como, a utilização do mesmo script para criação das procedures. Aplicada a atenção para selecionar o banco de dados antes da criação da procedure.  

 
:heavy_check_mark: As modelagens de dados assim como o projeto, foram desenvolvidos com estudos e utilização dos recursos das ferramentas: DB Designer, Draw.io, MySQL Workbench e SQL. :blue_heart: 

<br/>***<h2> :pencil: Observação: </h2>***
Os desenvolvimentos dos procedimentos propostos, foram realizados com o acompanhamento e anotações 💗<br/>das orientações do projeto, revisão das aulas e pesquisas. 💛 👩‍💻 🧡
  
<h3 align="center"> {✿◠‿◠} Muita gratidão! ✨🤗✨<br/><h3>  

![](https://cdn.revealbi.io/wp-content/uploads/2021/08/what-is-stored-procedure.png)

......![](https://www.mssqltips.com/tipimages2/3099_RowChainingMultiversion.jpg)


___

