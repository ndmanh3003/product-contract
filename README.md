[CONTENT](https://www.youtube.com/watch?v=07V4cKv16iw)

## Set up

0. Tạo ví

- Setting -> Network
- Fill in the form

```json
Network name: Volta
New RPC URL: https://volta-rpc.energyweb.org
Chain ID: 73799
Currency symbol: VT
Block explorer URL (Optional): https://volta-explorer.energyweb.org/
```

- Sử dụng `https://voltafaucet.energyweb.org/` để lấy VT
- Lấy private key `Account` -> `Account Details` -> `Show Private Key`

1. `npm init`

2. Cài cái dependencies từ `package.json`

3. `npx hardhat`

- Sửa file `hardhat.config.js`
- Tạo `scripts/deploy.ts`

4. Viết contract trong thư mục `contracts` và chạy

- `npx hardhat compile`
- `npx hardhat run --network volta scripts/deploy.ts`
