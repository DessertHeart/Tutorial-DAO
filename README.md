# Tutorial-DAO

## Instruction

FundDao: Hold & Manage Fund, The Miner of DaoToken.
DaoToken: A ERC20 Token for Governor.
Governor: The Owner of FundDao, Control the FundDao.

## Deploy Contract
1. create .env file with content:

```
MNEMONIC="your mnemonic"
```

2. deploy mock usdc (option):

```
npx hardhat run scripts/00_deploy_mock_usdc.js --network mumbai
```

3. deploy dao contracts:

```
npx hardhat run scripts/01_deploy_dao.js --network mumbai
```

## Run Demo
1. cd demo & npm install
2. npm run serve

