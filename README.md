[CONTENT](https://www.youtube.com/watch?v=07V4cKv16iw)

## Tạo ví

- Setting -> Network
- Fill in the form

```bash
Network name: Volta
New RPC URL: https://volta-rpc.energyweb.org
Chain ID: 73799
Currency symbol: VT
Block explorer URL (Optional): https://volta-explorer.energyweb.org/
```

- Sử dụng `https://voltafaucet.energyweb.org/` để lấy VT
- Lấy private key `Account` -> `Account Details` -> `Show Private Key`

## Tạo project

- `npm init`
- Cài các dependencies từ `package.json`

## Hardhat

`npx hardhat`

- Sửa file `hardhat.config.js`
- Tạo `scripts/deploy.ts`

## Viết contract

- `npx hardhat compile`
- `npx hardhat run --network volta scripts/deploy.ts`
