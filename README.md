# Home Sale Assistant

中国购房者/卖房者咨询助手，帮助您了解购房卖房需求、掌握房产知识、学会谈判技巧。

## 功能特点

- **需求分析**：通过对话了解您的需求，提供个性化购房/卖房建议
- **知识查询**：房产名词解释（容积率、公摊、得房率等）
- **计算功能**：贷款月供计算、税费计算
- **谈判指导**：买房/卖房谈判技巧和话术
- **城市分析**：杭州/上海各板块分析

## 快速开始

### 方式一：对话咨询

通过 Claude Code 使用此技能：

```
/home-sale-assistant 我想在上海买房，预算500万
```

### 方式二：阅读文档自学

直接阅读 `docs/` 目录下的文档：

| 文档 | 内容 |
|------|------|
| [docs/basics/terms.md](docs/basics/terms.md) | 房产名词解释 |
| [docs/basics/fee.md](docs/basics/fee.md) | 各种费用详解 |
| [docs/negotiation/buyer.md](docs/negotiation/buyer.md) | 买房谈判技巧 |
| [docs/negotiation/seller.md](docs/negotiation/seller.md) | 卖房谈判技巧 |
| [docs/calculator/loan.md](docs/calculator/loan.md) | 贷款计算 |
| [docs/calculator/tax.md](docs/calculator/tax.md) | 税费计算 |
| [docs/city/hangzhou.md](docs/city/hangzhou.md) | 杭州房产分析 |
| [docs/city/shanghai.md](docs/city/shanghai.md) | 上海房产分析 |

## 项目结构

```
home-sale-assistant/
├── SKILL.md              # 主技能文件（MIT License）
├── LICENSE.md            # 许可证说明
├── README.md             # 本文件
├── .gitignore            # Git忽略配置
├── docs/                 # 知识文档（CC BY 4.0）
│   ├── basics/           # 基础知识
│   ├── negotiation/      # 谈判技巧
│   ├── calculator/       # 计算器
│   └── city/             # 城市分析
└── data/                 # 用户数据（不上传GitHub）
    └── user_profile.md   # 用户画像
```

## 使用示例

### 对话示例

```
用户：我想买房，不知道从哪里开始
助手：我来帮您分析一下。首先想了解一下：
      1. 您想买在哪个城市？
      2. 您的预算是多少？
      3. 是刚需还是改善？

用户：上海，500万，刚需
助手：好的，根据您的情况，我可以给您以下建议...
```

### 知识查询

```
用户：容积率是什么
助手：容积率是指一个小区的地上总建筑面积与用地面积的比率。
      计算公式：容积率 = 总建筑面积 ÷ 用地面积
      容积率越高，居住密度越大，舒适度可能降低。
      ...
```

### 计算功能

```
用户：帮我算下500万房子贷款30年月供
助手：根据当前利率水平：
      - 等额本息月供：约 24,465 元
      - 等额本金首月：约 31,667 元（每月递减）
      ...
```

## License

- **代码**：MIT License - 见 [LICENSE.md](LICENSE.md)
- **文档**：CC BY 4.0 - 可自由分享但需署名

## 贡献

欢迎提交 Issue 和 Pull Request！

## 免责声明

本项目仅供学习参考，房产信息可能有过时之处，实际购房决策请咨询专业人士。