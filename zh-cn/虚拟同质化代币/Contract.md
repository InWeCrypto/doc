这里以ETH合约为例说明虚拟化通知代币标准合约接口



#### 铸币相关函数

##### 创建虚拟代币

```json
function makeAsset(address owner, string symbol, uint256 totalSupply, uint8 decimals) external payable returns(uint256)
```



创建虚拟资产，并将所有权转移给owner；参数说明：

* owner：最终拥有资产的地址；
* symbol：资产显示名；
* tototalSupply：虚拟代币供应量；
* decimals: 资产小数位数；
* msg.value：质押ETH数量；



