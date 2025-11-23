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

<img width="1917" height="1269" alt="image" src="https://github.com/user-attachments/assets/d1d48668-4b81-4d54-8ef8-801582b9871d" />

2.运行hello方法 并在区块链浏览器查看结果

<img width="1923" height="1268" alt="image" src="https://github.com/user-attachments/assets/9cbaa5c2-6975-43e7-ae6b-69f7bec03399" />

Transactions:

<img width="1391" height="737" alt="image" src="https://github.com/user-attachments/assets/d819fb26-be9a-4aed-8b44-092aef7afd2c" />

Events:

<img width="1392" height="843" alt="image" src="https://github.com/user-attachments/assets/7eccd22c-bb3f-4cf9-850c-ee0be4f13898" />

#### Part II - 智能合约编写

成功获取FLAG: PKU_Blockchain_Colearn_Week1_Success

交易哈希: 0x7661fbb60c03948fb20c9bc7f13de6e45dc3933ca0b2963b01ec73d5446b99fb

<img width="1921" height="1268" alt="image" src="https://github.com/user-attachments/assets/9e7314b0-b716-479a-90c2-30109f5123b0" />

<!-- Content_END -->
