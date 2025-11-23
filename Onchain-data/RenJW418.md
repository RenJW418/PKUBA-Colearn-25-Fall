---
timezone: UTC+8
---

> 请在上边的 timezone 添加你的当地时区(UTC)，这会有助于你的打卡状态的自动化更新，如果没有添加，默认为北京时间 UTC+8 时区


# 你的名字

1. 自我介绍 我是任纪武 2023级前沿交叉学科研究院直博生
2. 你认为你会完成这次共学小组吗？可以
3. 你感兴趣的小组 Onchain-data
4. 你的联系方式（Wechat or Telegram）Wechat: 15265978697

## Notes

<!-- Content_START -->

### 2025.11.23

#### Part I - 动手部署一个智能合约

1.在Remix中创建合约并编译部署

```jsx
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HelloWeb3 {
    event Greeting(address indexed sender, uint256 timestamp);
    
    constructor() {}

    function hello() external {
        emit Greeting(msg.sender, block.timestamp);
    }
}
```

<img width="1917" height="1269" alt="image" src="https://github.com/user-attachments/assets/81e862a9-d82d-4d68-b8a0-2ab05a6658f1" />


2.运行hello方法 并在区块链浏览器查看结果

<img width="1923" height="1268" alt="image" src="https://github.com/user-attachments/assets/2bca7cdb-e5e9-47e9-beee-44cb07be5a58" />


Transactions结果

<img width="1391" height="737" alt="image" src="https://github.com/user-attachments/assets/6b304bd6-011a-4cc2-a5db-542a5ccef6d3" />


Events结果

<img width="1392" height="843" alt="image" src="https://github.com/user-attachments/assets/bb3190f7-020e-4ffc-b0b5-c521512bdff9" />


#### Part II - 智能合约编写

成功获取FLAG: PKU_Blockchain_Colearn_Week1_Success

交易哈希: 0x7661fbb60c03948fb20c9bc7f13de6e45dc3933ca0b2963b01ec73d5446b99fb

<img width="1921" height="1268" alt="image" src="https://github.com/user-attachments/assets/03a4ff1d-03c8-4b70-81f9-d197a81ad6a4" />




<!-- Content_END -->
