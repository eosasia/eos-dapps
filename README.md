## How to add a new token
1. Move into the chain folder.
2. Add logo and large logo to `logos` sub folder.
3. Append token data in `tokens.json`. The whole JSON file is an array.

  Data format:
  ```
  {
    "name": "<TOKEN_NAME>",
    "logo": "https://raw.githubusercontent.com/eosasia/eos-dapps/master/<CHAIN_FOLDER_NAME>/logos/<LOGO_FILE_NAME>",
    "logo_lg": "https://raw.githubusercontent.com/eosasia/eos-dapps/master/<CHAIN_FOLDER_NAME>/logos/<LARGE_LOGO_FILE_NAME>",
    "symbol": "<TOKEN_SYMBOL>",
    "account": "<CONTRACT_ACCOUNT>",
    "precision": 4
  }
  ```
  Replace these capitalized part(includes `<` and `>`) to your own info.

<br/>
<br/>

## 如何添加一个新的代币
1. 转到相应链的文件夹。
2. 子文件夹 `logos` 中加入图标和大号图标。
3. 在 `tokens.json` 的数组中补充完代币数据。

  数据形式如下
  ```
  {
    "name": "<代币名>",
    "logo": "https://raw.githubusercontent.com/eosasia/eos-dapps/master/<相应链的文件夹名>/logos/<图标文件名>",
    "logo_lg": "https://raw.githubusercontent.com/eosasia/eos-dapps/master/<相应链的文件夹名>/logos/<大号图标文件名>",
    "symbol": "<代币符号>",
    "account": "<合约账号名>"
    "precision": 4
  }
  ```
  替换掉尖括号的数据（包括尖括号）。

