# Onboard Professor

- Os cursos podem ter um repositório para compartilhar materiais extras.
- Esses materiais podem ser: roteiros de aulas, código, pdf, slides ou outra coisa que o professor ache util
- O `README` do repo contém a grade do curso

## Templates

- [Aula Inicial](./aula1.md)
- [Aula Conteúdo](./aula-template.md)

## Estrutura do repo

```
├── README.md
├── mod1
│   ├── aula1
│   │   └── roteiro.md
│   ├── aula2
│   │   └── roteiro.md
.   .
.   .
├── mod2
│   ├── aulas
│   │   ├── aula1
│   │   │   └── roteiro.md
│   │   ├── aula2
│   │   │   └── roteiro.md
│   │   ├── aula3
│   │   │   └── roteiro.md
│   └── playground
│       ├── aula1
│       │   ├── createRandomWallet.js
│       │   ├── encryptWallet.js
│       │   ├── importWalletFromPrivateKey.js
│       │   └── signMessage.js
│       ├── aula2
│       │   ├── balanceOf.js
│       │   ├── balanceOfERC20.js
│       │   ├── connect.js
│       │   ├── convertWei.js
│       │   └── erc20.sol
│       └── aula3
│           ├── getTransaction.js
│           ├── getTransactionLogs.js
│           ├── getTransactionReceipt.js
│           ├── sendERC20.sh
│           └── sendETH.sh
├── mod3
│   ├── aulas
│   └── playground
│       ├── aula1
│       │   ├── ...
.       .   .
.       .   .
.       .   .
```
