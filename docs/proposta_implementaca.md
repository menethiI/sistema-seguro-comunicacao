# Como as tecnologias são utilizadas na aplicação:

## Bcrypt
Utilizado no processo de cadastro de usuário para gerar o hash das senhas dos usuários<br>

## Tokens JWT 
Utilizados no processo de login para realizar a autenticação<br>

## Criptografia AES
Utilizada para proteger as mensagens que passarem pela aplicação<br>
 
## RSA
Utilizado para para criptografar as chaves antes de armazená-las<br>


# Como é realizado o armazenamento dos dados 

O Cripto Defender tem como missão garantir que as informações digitais da empresa estejam protegidas contra o acesso não autorizado, perda ou roubo<br>

Nosso objetivo é assegurar a integridade e confidencialidade de todas as informações que transitarem pelo sistema e garantir a proteção dos funcionários<br>

Práticas utilizadas para manter o armazenamento seguro:<br>

⚠️ As senhas **NUNCA** serão armazenadas em texto plano<br>

⚠️ As senhas serão armazenadas utlizando o bcrypt com sal aleatório<br>

⚠️ A aplicação irá **rejeitar** tokens invalidos ou expirados<br>

⚠️ **Todas** as solicitãções protegidas serão validas pelos token JWT 
