
![iClinic logo](https://d1ydp7gtfj5fb9.cloudfront.net/static/img/views/home_v2/header/logo.png?1525283729)

# Desafio

A missão da iClinic é descomplicar a saúde no Brasil levando mais gestão a clínicas e consultórios através da tecnologia e, com isso, possibilitar que médicos e outros profissionais promovam mais saúde aos seus pacientes.

Seu desafio será analisar e desenvolver scripts de conversão de dados médicos fictícios para o padrão iClinic e, como parte deste desafio, veremos como você trata os dados sensíveis e não padronizados, bem como estrutura as camadas de aplicação, testes unitários, logs e documentação.

### Solução

Analisar, relacionar, transformar e desenvolver script em Python&reg; de conversão de dados médicos fictícios de várias fontes distintas para o padrão iClinic.

Os arquivos de dados médicos disponibilizados são:
- [Dados 1](desafio-base1.zip), da Dra. Maria (dados de todos os médicos);
- [Dados 2](desafio-base2.zip), do Dr. José;
- [Dados 3](desafio-base3.zip), da Dra. Ana, Dr. Carlos e Dr. Gustavo.

É importante destacar que apesar de serem dados fictícios, estes devem ser considerados dados sensíveis e é necessário manter seu conteúdo o mais próximo possível do original.

Todo o processo de análise e de relacionamento dos dados deve ser documentado em um relatório, no qual deve descrever as etapas e ferramentas utilizadas de forma detalhada, bem como, toda informação que julgar relevante. Este relatório deve estar em formato texto, markdown ou pdf, nomeado como relatorio.txt, relatorio&#46;md ou relatorio.pdf, respectivamente.

A conversão dos dados deve gerar arquivos CSV, de acordo com a documentação que descreve o padrão iClinic, disponível em https://docs.iclinic.com.br. Além disso, os arquivos devem ser gerados com o conjunto de caracteres UTF-8.

Caso sejam criados arquivos intermediários, para realização da conversão dos dados, estes também devem ser anexados juntos com seus respectivos scripts.

Também deverá ser gerado um documento, nomeado README&#46;md, contendo as instruções de como executar o(s) script(s) Python&reg;, a descrição dos arquivos intermediários, caso existam, e link para o relatório.


### O que esperamos

 - Disponibilizar a solução do desafio em um repositório GitHub;
 - Que o código do desafio seja feito em Python 3+;
 - Dados convertidos no formato CSV;
 - Relatório com a descrição das etapas e ferramentas utilizadas;
 - Passo a passo de como executar o script de conversão;
 - Clareza no código;
 - Gerenciamento de dependências;
 - Commits semânticos.

### Não obrigatório, mas recomendado
 - Docker para restaurar as bases de dados;
 - Que utilize as bibliotecas Pandas e de banco de dados;
 - Testes unitários;
 - Princípios SOLID;
 - [12Factor](https://12factor.net/);
 - CI (Travis, Gitlab, Circle CI, Github Actions, ...).

___
Boa Sorte,
Equipe iClinic.
