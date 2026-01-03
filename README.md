# river-ndti-sentinel2
river-ndti-sentinel2/
│
├── README.md                # 项目总说明（最重要）
├── LICENSE                  # 开源协议（MIT / Apache-2.0 等）
├── CITATION.cff             # 学术引用信息（推荐）
├── .gitignore               # 忽略规则
│
├── data/
│   ├── raw/                 # 原始数据（不上传大文件）
│   ├── processed/           # 处理后数据（示例或小样本）
│   └── README.md            # 数据说明
│
├── gee/
│   ├── ndti_monthly.js      # GEE JavaScript 主脚本
│   └── README.md            # GEE 使用说明
│
├── python/
│   ├── ndti_colab.ipynb     # Colab / Python 实现
│   ├── ndti_xarray.py       # xarray / xee 脚本
│   └── requirements.txt     # Python 依赖
│
├── figures/
│   ├── ndti_maps.png        # 示例结果图
│   └── timeseries.png
│
├── docs/
│   ├── methodology.md      # 方法说明
│   └── faq.md               # 常见问题
│
└── scripts/
    └── utils.js             # 可复用函数
