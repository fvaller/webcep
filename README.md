WebService de CEP
----------------

Fa�a a busca de CEP diretamente no site dos correios utilizando phpQuery.

1. Fun��o faz em jQuery faz requisi��o ao arquivo cep.php;
2. cep.php via curl obtem os dados da pagina;
3. Usando o phpQuery � feito a filtragem dos dados e gerado um retorno em JSON;