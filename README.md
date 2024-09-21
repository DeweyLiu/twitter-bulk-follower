# twitter-bulk-follower
Twitter Bulk Follower

<div align="right">
  Language:
  <a title="English" href="#readme">🇺🇸</a>
  <a title="中文" href="#readme-cn">🇨🇳</a>
</div>

Twitter Bulk Follower is an automated tool designed to follow multiple Twitter users in bulk. This script helps you quickly expand your Twitter network, making it particularly useful for individuals or businesses looking to rapidly increase their follower count.

## Features

- Automatic Twitter account login
- Bulk extraction of Twitter user links from a specified page
- Automated user profile visits and follow actions
- Intelligent delay and retry mechanisms to reduce detection risk
- Detailed logging for easy debugging and monitoring

## Requirements

- Python 3.6+
- Selenium WebDriver
- Chrome browser

## Installation

Install the required dependencies:

bash
pip install selenium webdriver_manager

## Usage

1. Clone the repository:

bash
git clone https://github.com/DeweyLiu/twitter-bulk-follower.git
cd twitter-bulk-follower


2. Set environment variables or modify the Twitter account information directly in the script:

bash
export TWITTER_USERNAME="your_username"
export TWITTER_PASSWORD="your_password"


3. Run the script:

bash
python twitter_bulk_follower.py


## Configuration

- `page_url`: Set the URL of the page from which to extract Twitter user links
- `chrome_options`: Modify Chrome browser options as needed

## Caution

- Use this script responsibly. Excessive use may violate Twitter's terms of service
- Set appropriate delay times to avoid account restrictions or bans
- The user assumes all responsibility for any consequences resulting from the use of this script

## Contributing

Issues and pull requests are welcome to help improve this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<div id="readme-cn"></div>

# Twitter 批量关注工具

<div align="right">
  语言:
  <a title="English" href="#readme">🇺🇸</a>
  <a title="中文" href="#readme-cn">🇨🇳</a>
</div>

Twitter 批量关注工具是一个自动化工具，用于批量关注 Twitter 用户。这个脚本可以帮助您快速扩大您的 Twitter 网络，特别适合需要快速增加关注者的个人或企业账户。

## 功能特点

- 自动登录 Twitter 账户
- 从指定页面批量提取 Twitter 用户链接
- 自动访问用户主页并关注
- 智能延迟和重试机制，降低被检测风险
- 详细的日志输出，方便调试和监控

## 安装要求

- Python 3.6+
- Selenium WebDriver
- Chrome 浏览器

## 安装

安装所需的依赖：
bash
pip install selenium webdriver_manager

## 使用方法

1. 克隆仓库到本地：
bash
git clone https://github.com/DeweyLiu/twitter-bulk-follower.git
cd twitter-bulk-follower

2. 设置环境变量或直接在脚本中修改 Twitter 账号信息：
bash
export TWITTER_USERNAME="your_username"
export TWITTER_PASSWORD="your_password"

3. 运行脚本：

bash
python twitter_bulk_follower.py

## 配置选项

- `page_url`: 设置要从中提取 Twitter 用户链接的页面 URL
- `chrome_options`: 可以根据需要修改 Chrome 浏览器的选项

## 注意事项

- 请谨慎使用此脚本，过度使用可能违反 Twitter 的使用条款
- 建议设置适当的延迟时间，避免账号被限制或封禁
- 使用此脚本造成的任何后果由使用者自行承担

## 贡献

欢迎提交 issues 和 pull requests 来帮助改进这个项目。

## 许可证

本项目采用 MIT 许可证。详情请见 [LICENSE](LICENSE) 文件。






