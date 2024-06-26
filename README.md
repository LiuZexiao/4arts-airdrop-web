# 4arts

sources/scripts/deploy.ts 部署ENT合约

# 开始
确保具备node环境，需要安装 yarn 
```shell
npm install -g yarn 
```
加载环境
```shell
yarn install
```

运行部署 deploy.ts  
```shell
yarn deploy
```
# 测试进度


# 常见问题

Error: timeout of 5000ms exceeded
访问超时，添加代理配置 （clash）
```shell
yarn config set proxy http://127.0.0.1:7890 
yarn config set https-proxy http://127.0.0.1:7890
```
## 错误代码
# Error Codes
2: Stack undeflow
3: Stack overflow
4: Integer overflow
5: Integer out of expected range
6: Invalid opcode
7: Type check error
8: Cell overflow
9: Cell underflow
10: Dictionary error
13: Out of gas error
32: Method ID not found
34: Action is invalid or not supported
37: Not enough TON
38: Not enough extra-currencies
128: Null reference exception
129: Invalid serialization prefix
130: Invalid incoming message
131: Constraints error
132: Access denied
133: Contract stopped
134: Invalid argument
135: Code of a contract was not found
136: Invalid address
137: Masterchain support is not enabled for this contract
3688: Not mintable
4429: Invalid sender
5862: No items in the array to update!
6947: No items in the array!
12241: Max supply exceeded
14534: Not owner
16059: Invalid value
17848: No items in the array to delete!
18668: Can't Mint Anymore
23951: Insufficient gas
32846: Not true
42469: No space in the array left for new items!
42708: Invalid sender!
43422: Invalid value - Burn
62972: Invalid balance