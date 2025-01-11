## 1 文件夹结构

``` bash
your-repo/
│
├── vanna/
│   ├── data/                  # 存放数据文件
│   ├── notebooks/             # 存放Jupyter Notebook文件
│   ├── scripts/               # 存放Python脚本
│   ├── models/                # 存放训练好的模型或模型相关文件
│   ├── utils/                 # 存放工具函数或辅助脚本
│   ├── config/                # 存放配置文件
│   ├── README.md              # 文件夹说明文档
│   └── requirements.txt       # 依赖文件
│
└── ...
```

## 2 文件命名建议
- Notebooks: 使用描述性的名称，便于理解其内容。例如：

  - vanna_data_exploration.ipynb：用于数据探索的Notebook。

  - vanna_model_training.ipynb：用于模型训练的Notebook。

  - vanna_inference.ipynb：用于推理或预测的Notebook。


- Scripts: 如果你有一些可重用的Python脚本，可以命名为：

  - data_preprocessing.py：数据预处理脚本。

  - model_training.py：模型训练脚本。

  - inference.py：推理脚本。

- Data: 数据文件可以根据其内容或用途命名，例如：

  - raw_data.csv：原始数据。

  - cleaned_data.csv：清洗后的数据。
  - train_data.csv：训练数据。
  - test_data.csv：测试数据。

- Models: 模型文件可以根据模型类型或训练日期命名，例如：

  - vanna_model_20231015.pkl：2023年10月15日训练的模型。

  - vanna_model_v1.pkl：模型版本1。

- Utils: 工具函数或辅助脚本可以命名为：

  - data_utils.py：数据处理工具。

  - model_utils.py：模型相关工具。

- Config: 配置文件可以命名为：
  - config.yaml 或 config.json：配置文件。



##  3 Vanna 功能实验

这个文件夹用于实验和开发与 Vanna 相关的功能。

### 目录结构

- `data/`: 存放数据文件。
- `notebooks/`: 存放Jupyter Notebook文件。
- `scripts/`: 存放Python脚本。
- `models/`: 存放训练好的模型。
- `utils/`: 存放工具函数。
- `config/`: 存放配置文件。

### 使用说明

1. 安装依赖：`pip install -r requirements.txt`
2. 运行Notebook或脚本进行实验。