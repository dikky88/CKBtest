Console Output

![ckb_task3](https://user-images.githubusercontent.com/21215088/128854937-28f543de-958f-4350-abbc-96a7a3a62e00.png)


Transaction Hash

0xf7a4bff8a4ddc92c292921e68f26faaac25be6fdf0f908c32f9c8b43be73d082

Contract Address Called

0xa3787903595677d71B0582655fBb2dd34857D741

const CONTRACT_ABI = [
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
]; // this should be an Array []
