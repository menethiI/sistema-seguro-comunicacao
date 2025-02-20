# Como as tecnologias são utilizadas na aplicação:

## Bcrypt
Utilizado no processo de cadastro de usuário para gerar o hash das senhas dos usuários<br>

## Tokens JWT 
Utilizados no processo de login para realizar a autenticação<br>

## Criptografia AES
Utilizada para proteger as mensagens que passarem pela aplicação<br>
 
## RSA
Utilizado para para criptografar as chaves antes de armazená-las<br><br>


# Como é realizado o armazenamento dos dados 

O Cripto Defender tem como missão garantir que as informações digitais da empresa estejam protegidas contra o acesso não autorizado, perda ou roubo<br>

Nosso objetivo é assegurar a integridade e confidencialidade de todas as informações que transitarem pelo sistema e garantir a proteção dos funcionários<br>

Práticas utilizadas para manter o armazenamento seguro:<br>

⚠️ As senhas **NUNCA** são armazenadas em texto plano<br>

⚠️ As senhas são armazenadas utlizando o bcrypt com sal aleatório<br>

⚠️ A aplicação **rejeita** tokens inválidos ou expirados<br>

⚠️ **Todas** as solicitações protegidas são validadas pelos token JWT 
