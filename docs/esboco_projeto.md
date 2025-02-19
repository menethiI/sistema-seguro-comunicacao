O objetivo da nossa aplicação é garantir a proteção de mensagens sensíveis e elevar a segurança dos funcionários da nossa organização.<br>

# Tecnologias utilizadas:
✅ bcrypt → Hashing seguro de senhas.<br>
✅ PyJWT → Autenticação via Tokens JWT.<br>
✅ cryptography → Implementação de AES e RSA.<br>


# Fluxo básico do sistema:
✅ Usuário faz cadastro (senha armazenada com bcrypt).<br>
✅ Usuário faz login (autenticado via JWT).<br>
✅ Usuário envia uma mensagem criptografada com AES.<br>
✅ Apenas o destinatário correto pode descriptografar com sua chave RSA.