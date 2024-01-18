- [Desafio FullStack](#desafio-fullstack)
- [Contexto](#contexto)
  - [Modelo de dados](#modelo-de-dados)
    - [Tipo de profissional](#tipo-de-profissional)
    - [Profissional](#profissional)
  - [Requisitos funcionais](#requisitos-funcionais)
    - [Backend](#backend)
    - [Frontend](#frontend)
  - [Diferencial](#diferencial)
  - [Requisitos não funcionais](#requisitos-não-funcionais)
  - [Opcional - Requisitos avançados ](#opcional---requisitos-avançados)
- [Com o que nos preocupamos](#com-o-que-nos-preocupamos)
- [FAQ](#faq)

# Desafio FullStack

**Seja bem-vindo ao nosso desafio de desenvolvimento!** :raised_hands:

*Tenha certeza de ter lido todo o documento atentamente até o final e esclarecido as dúvidas com nosso time caso surja alguma.*

Esta é a proposta de um desafio que FullStack sinta-se a vontade para tentá-lo por completo, caso seu objetivo esteja focado em uma das duas funções Backend, Frontend ou Mobile fique a vontade para deixar o outros desafios de lado.

:rocket: Tudo certo!?  Então vamos lá! 


# Contexto

Em todo aplicativo comercial temos um controle dos profissinais envolvidos no processo sejam usuários, responsáveis, gerentes, administradores, operadores, etc. Por isso um ponto importante de qualquer aplicação é permitir designarmos estas funções ou seja categorizar em tipos estes profissionais.  Ex.: ProfissionalAna = Médica, José = Professor... 

Vamos criar então uma aplicação que nos permita consultar, criar e editar essas informações e manter essa relação entre o profissional e seu tipo.

## Modelo de dados
### Tipo de profissional
```js
{
  "id": xxx,                  // ID 
  "descricao": "test",        // descricao do tipo *Obrigatório
  "situacao": true,           // situacao do cadastro *Obrigatório
  "updatedAt": "",            // data e hora ultima atualizacao *Obrigatório
  "createdAt": ""             // data e hora de cadastro *Obrigatório
}
```

### Profissional
```js
{
    "id": xxx,                   // ID
    "nome": "teste",             // Nome do profisisonal *Obrigatório
    "telefone": "(xx) xxxx",     // Telefone
    "email": "a@a.com",          // Endereço de e-mail do profissional
    "tipoDeProfissional": xxx,   // Vinculo com o tipo de profissional *Obrigatório
    "situacao": true,            // Situação do cadastro *Obrigatório
    "updatedAt": "",             // Data e hora da última atualização *Obrigatório
    "createdAt": ""              // Data e hora da de cadastro *Obrigatório
}
```

## Requisitos funcionais
### Backend
- A API deve seguir as boas práticas e padrões de implementação REST
- Os dados deve ser salvos em um banco de dados
- Prover documentação para API. (Sugestão OpenAPI/Swagger)
- Use **Node.js** e qualquer outro framework
- Use **TypeScript**
- Use qualquer DB. PostgreSQL DB é a sugestão, sinta-se livre para usar qualquer outro.

### Frontend
- Criar uma tela home com menu de acesso as funcionalidades
- Uma tela de listagem para cada uma das entidades
- Uma tela de cadastro para cada uma das entidades
- Implementar solução usando **ReactJS** ultima versão disponível
- Fique a vontade para utilizar bibliotecas de componentes de mercado ou criar os seus
- Utilize **TypeScript**

## Diferencial
- Testes unitários no backend e/ou no frontend
- Documentação clara do código. Código comentado sempre é bom!
- Boas mensagens de commit ajudam!

## Requisitos não funcionais
- Um arquivo README.md com o resumo de escolhas por frameworks, bibliotecas, banco de dados e como executar seu projeto.


## Opcional - Requisitos avançados

Estes requisitos são opcionais no desafio, sinta-se a vontade para deixá-los de lado, a menos que seja solicitado que os cumpra!   

- Configuração Docker para build da imagem do projeto, docker compose para subir banco de dados com carga inicial necessária (migrations, seeders).
- Criar mecanismo completo de autenticação e autorização (authentication/authorization/etc.) , como OAuth.
- Criar mecanismo de log e auditoria (quando/como/quem etc.).

# Com o que nos preocupamos
- Com certeza muito mais do que o desafio completo é avaliarmos suas competências e habilidades até o ponto em que chegou.
- Sabemos que nem todos temos o mesmo tempo disponível, então como dissemos fique a vontade para ir até onde conseguir ou solicitar mais tempo para o processo, transparência total.
- Sinta-se livre pra usar bibliotecas de código aberto se fizerem sentido, e lembre que avaliaremos sua capacidade de resolver problemas reais.
- Procuramos por código funcionando e limpo
- Exemplos práticos de conhecimento em NodeJS e TypeScript e suas APIs padrões
- Orientação a testes 

# FAQ
> Como devo fazer a entrega do desafio?

- Envie o link do seu repositório de código particular para quem te fez a solicitação de execução desse desafio.

> Se eu tiver dúvidas?
- Entre em contato com nosso time que esta te apoiando no processo seletivo.

[Voltar ao topo](#desafio-fullstack)