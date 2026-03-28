# Connect
# 联系

## Project Purpose
## 项目目的

This project aims to provide a way for users of my applications to contact me through GitHub Issues and Push requests. Users can select the appropriate template based on the software they are using and their region to submit issues or feedback.

该项目旨在为使用我的应用的用户提供一个通过GitHub Issues、Push联系我的方式。用户可以根据他们使用的软件和所在地区，选择相应的模板来提交问题或反馈。

## Currently Supported Applications
## 目前支持的应用

- Cryptic

## Regional Support
## 地区支持

Currently supported regions:
目前已支持的地区：
- ChineseSimplified (简体中文) 🇨🇳
- US (English) 🇺🇸
- ChineseTraditional (繁體中文) 🇭🇰
- Japanese (日本語) 🇯🇵
- Korean (한국어) 🇰🇷
- French (Français) 🇫🇷
- German (Deutsch) 🇩🇪
- Spanish (Español) 🇪🇸
- Portuguese (Português) 🇵🇹

Users from other countries are also welcome to use this project, simply create a corresponding regional folder following the same directory structure.

其他国家的用户也欢迎使用此项目，只需按照相同的目录结构创建相应的地区文件夹即可。

## Usage
## 使用方法

1. Visit the Issues page of this repository
2. Click "New issue"
3. Select the template corresponding to your application and region
4. Fill in the relevant information and submit

1. 访问本仓库的 Issues 页面
2. 点击 "New issue"
3. 选择对应应用和地区的模板
4. 填写相关信息并提交

## Project Structure
## 项目结构

```
connect/
├── Cryptic/
│   ├── ChineseSimplified   # Simplified Chinese regional issue templates
│   ├── US                  # English regional issue templates
│   ├── ChineseTraditional  # Traditional Chinese regional issue templates
│   ├── Japanese            # Japanese regional issue templates
│   ├── Korean              # Korean regional issue templates
│   ├── French              # French regional issue templates
│   ├── German              # German regional issue templates
│   ├── Spanish             # Spanish regional issue templates
│   └── Portuguese          # Portuguese regional issue templates
└── README.md               # Project description file
```

```
connect/
├── Cryptic/
│   ├── ChineseSimplified   # 简体中文地区的issue模板
│   ├── US                  # 英语地区的issue模板
│   ├── ChineseTraditional  # 繁体中文地区的issue模板
│   ├── Japanese            # 日语地区的issue模板
│   ├── Korean              # 韩语地区的issue模板
│   ├── French              # 法语地区的issue模板
│   ├── German              # 德语地区的issue模板
│   ├── Spanish             # 西班牙语地区的issue模板
│   └── Portuguese          # 葡萄牙语地区的issue模板
└── README.md               # 项目说明文件
```