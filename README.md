## Web3 常用工具集合

web3 中常见的处理数字和字符串等的工具集合

## 使用说明

### 1.安装依赖

修改 package.json 后 install

```
// package.json
"web3-toolkit": "https://github.com/gatechain/web3-toolkit.git#1.0.0"

pnpm install
```

### 2.使用

```
import { formatPriceDecimals } from 'web3-toolkit'

formatPriceDecimals('0.012345465')// 0.01234
```

### 3.API reference

- [formatPriceDecimals](#formatPriceDecimals)-格式化价格以进行展示
- [formatVolumeDecimals](#formatVolumeDecimals)-格式化市值、交易量（英文）
- [formatVolumeDecimalsZh](#formatVolumeDecimalsZh)-格式化市值、交易量（中文）
- [formatPercentageDecimals](#formatPercentageDecimals)-格式化百分比展示
- [formatVolumeInt](#formatVolumeInt)-格式化市值、交易量（整数，英文）
- [formatVolumeIntZh](#formatVolumeIntZh)-格式化市值、交易量（整数，中文）
- [formatMinimumDecimals](#formatMinimumDecimals)-格式化小数值，折叠 0 的个数后展示
- [thousandSeparatorNum](#thousandSeparatorNum)-千分符展示
- [fixedToInt](#fixedToInt)-将小数值转换为固定精度的整数
- [intoFixed](#intoFixed)-将固定精度的整数转换为小数值
- [formatHash](#formatHash)-格式化哈希，省略中间部分
- [base64ToHex](#base64ToHex)-将 base64 转换为 hex
- [\_convertScientificToNumberString](#_convertScientificToNumberString)-将科学记数法转换为字符串。
- [\_findFirstNonZeroIndex](#_findFirstNonZeroIndex)-找到字符串中第一个不为零的数字的索引

### 附录

常用数字格式参照标准：https://docs.google.com/spreadsheets/d/1e2LwZn5yy6khXLSjfnEJWTnAf8eQfGLAqdDSLf1u3ZM/edit?gid=1828101630#gid=1828101630
