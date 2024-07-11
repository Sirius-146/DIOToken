# Criando um token no Ethereum

Criação de um token em uma blockchain de testes, simulando a criação de contratos e efetuação de transações na rede Ethereum. <br>
O projeto foi desenvolvido tendo como base o conteúdo do [repositório](https://github.com/digitalinnovationone/formacao-blockchain-dio) referente à formação [Blockchain Developer with Solidity](https://www.dio.me/bootcamp/coding-the-future-blockchain-developer-with-solidity)

> Token name: DIO
>
> Ferramentas:
>
> - Remix IDE
> - Metamask
> - Ganache

### Código

Todo o código foi escrito em _Solidity_, e pode ser encontrado no arquivo [`DIOCoin.sol`](C:\Workspace\BTCWALLET\DIOCoin\DIOCoin.sol)

### Implementando o contrato

Na imagem a seguir, observamos as transações de criação de contrato e transferência de Tokens na rede.<br>
Para isso foi usado o Ganache na criação de uma rede Blockchain local, juntamente com carteiras digitais. Para realizção das transações foi utilizado o Metamask.<br><br>
<img src="img\transactions.png" alt="transactions" width="60%"/>
<br><br>
A cada transação confirmada, o ganache criava um bloco:
<br><br>
<img src="img\blocks.png" alt="blocks" width="60%"/>
<br><br>
Por último, podemos ver o histórico de movimentação na conta por meio do Metamask:
<br><br>
<img src="img\account.png" alt="account" heigth="40%"/>
