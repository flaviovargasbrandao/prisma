# Projeto notas de qualidade -  Descrição do Projeto e tarefas #

A equipe de engenharia de produção demanda a criação de um sistema para calculo automatico de notas referente a qualidade do produto impresso. 
Para isso, o produto impresso deve obedecer os paramtros lançados semanalmente pela equipe de engenharia. Para fazer o input, o operador utiliza um aparelho da X-Rite para leitura de densidade.

### Como funciona (Front End) ###

O operador faz a leitura utilizando o aparelho da X-Rite que retorna valores CSV. Esse valor é inputado na base de dados para que seja criado um historico temporario. O valor da nota é calculada com base do retorno do que será inputado na base e será armazenado em uma tabela criada para aquele produto.

