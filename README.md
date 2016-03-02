WebService de CEP
----------------

Pesquisa de CEP diretamente no site dos correios com PHP, jQuery e phpQuery.

1. A função getEndereco() faz a requisição passando o cep via jQuery o arquivo cep.php;
2. No arquivo cep.php é feita uma nova requisição a pagina dos correios;
3. Com os dados obtidos da pagina fazemos a separação dos dados que desejamos isso usando o phpQuery;
4. Repondemos a requisição inicial com os dados tratados em JSON;
 

Uma das vantagem dessa forma é de sempre obter os dados atualizados diretamente da base de CEP dos correios;

