# LIVRO-ONLINE
Livro Online de partes ao serviço da OM

By Felipe Pedrosa

Esta versão utiliza:

-Apache 2.0.61

-PHP Version 5.3.10-1ubuntu3.13

-Mysql 5.0.45

-PhpMyAdmin 2.11.2.2

Alteração necessária:

Edite o arquivo php.ini do seu servidor e altere o valor da variável abaixo para On:

Caso essa linha não exista deve ser acrescentada

register_globals = On

As Configurações de conexão com o banco de dados são feitas no arquivo base.php

Usuário padrão: admin

Senha: admin


O Livro online atende necessidades específicas de uma OM de Artilharia do Exército Brasileiro, o que não impede de ser modificado e adequado para atender qualquer outra Arma/Quadro/Serviço. No contexto deste sistema, quem faz o preenchimento do livro é um graduado, no caso especifico, o Adjunto ao Oficial de Dia, que ao término, apresenta o mesmo ao Oficial para possíveis correções e alterações.

O livro então segue seu fluxo para a caixa do Scmt, que geralmente é o responsável pelo serviço, o mesmo faz a leitura e em seguida o despacho, podendo fazer despachos individuais para os Cmt SU, S1, S2, S3, S4 e Fiscal Adm, este, por sua vez, devem conferir diariamente os despachos enviados pelo Scmt para suas caixas e relatar providencia tomada.

O livro criado pode ser lido, editado e excluído enquanto não for despachado pelo Scmt, após o despacho fica disponível somente para leitura.

Relatórios por períodos podem ser gerados por qualquer usuário, qualquer usuário pode ler qualquer livro, porém cada um só edita ou exclui livros criados por ele mesmo.
