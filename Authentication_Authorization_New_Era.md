# Authentication and Authorization Part 2: A New, Verifiable Era
- Referência: `https://duo.com/labs/research/authentication-and-authorization-for-a-new-verifiable-era`

- Data de Leitura: `25/09/24`

## 00. O Desafio da Autenticação
- **Mudanças Necessárias**: A necessidade de melhorar a autenticação e autorização devido às senhas fracas e ao compartilhamento de dados não verificados.
- **Soluções Sem Senha**: Crescimento de soluções que eliminam o uso de senhas, embora algumas apenas ofusquem os problemas subjacentes.

## 01. Decodificando um Paradoxo de Senha
- **Chaves de Acesso**: Introdução de passkeys que utilizam chaves criptográficas assimétricas armazenadas em hardware.
  - **Benefícios**: Login rápido e seguro sem senhas, resistência a phishing e fácil integração com SSO (Single Sign-On).
- **Problemas com Chaves de Acesso**:
  - **Identidade Não Inclusa**: Passkeys não contêm informações de identidade, o que pode levar a associações incorretas. O usuário é realmente o usuário com a passkey?
  - **Risco de Sincronização**: Sincronizar chaves entre dispositivos aumenta a superfície de ataque.

## 02. Progresso em Direção a um Ecossistema de Identidade Descentralizado
- **Segurança Aumentada**: Necessidade de vincular chaves a usuários de forma validável (ex: biometria, realmente tem que ser o usuário!).
- **Padrões Emergentes**: Desenvolvimento de credenciais verificáveis que eliminam a necessidade de senhas e nomes de usuário.
  - **Vantagens**: Redução de pontos de falha, melhor privacidade e autenticação descentralizada.
