WebService de CEP
----------------

Faça a busca de CEP diretamente no site dos correios utilizando phpQuery.

1. Função faz em jQuery faz requisição ao arquivo cep.php;
2. cep.php via curl obtem os dados da pagina;
3. Usando o phpQuery é feito a filtragem dos dados e gerado um retorno em JSON;