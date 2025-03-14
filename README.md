# MCP 服务器项目说明

## 简介

本项目提供了Model Context Protocol (MCP) 服务器的相关资源和推荐，帮助开发者更好地利用MCP技术进行开发和集成。

## MCP 服务器推荐

以下是推荐使用的MCP服务器列表：

- **sequential-thinking** - 用于顺序思考和推理的MCP服务器
- **filesystem** - 提供文件系统操作能力的MCP服务器
- **playwright** - 基于Playwright的自动化测试和网页交互MCP服务器
- **puppeteer** - 基于Puppeteer的网页自动化MCP服务器
- **memory** - 提供内存管理和存储功能的MCP服务器
- **firecrawl** - 网页爬虫MCP服务器
- **fetch** - 提供网络请求功能的MCP服务器
- **git** - Git版本控制集成MCP服务器
- **github** - GitHub集成MCP服务器
- **slack** - Slack集成MCP服务器
- **mcp-installer** - MCP服务器安装工具
- **docker** - Docker容器管理MCP服务器
- **barve search** - 搜索功能MCP服务器
- **figma** - Figma设计工具集成MCP服务器
- **Tavily** - Tavily API集成MCP服务器
- **Brower use** - 浏览器使用MCP服务器

## 开源 MCP Server聚合网站

以下是一些有用的MCP服务器聚合网站和资源：

- [Smithery.ai](https://smithery.ai/) - MCP服务器资源聚合
- [MCPHunt](https://mcphunt.com/zh) - 中文MCP服务器搜索平台
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - 精选MCP服务器列表
- [MCP.so](https://mcp.so/servers) - MCP服务器目录
- [AIMCP.info](https://www.aimcp.info/en) - MCP服务器信息平台
- [GitHub MCP Topic](https://github.com/topics/mcp) - GitHub上的MCP主题
- [MCPServers.org](https://mcpservers.org/) - MCP服务器组织
- [Model Context Protocol Servers](https://github.com/modelcontextprotocol/servers) - 官方MCP服务器仓库
- [Model Context Protocol Organization](https://github.com/modelcontextprotocol) - MCP官方组织
- [MCP Servers Main Branch](https://github.com/modelcontextprotocol/servers/tree/main) - MCP服务器主分支
- [Cursor Directory](https://cursor.directory/) - Cursor MCP服务器目录
- [Glama.ai MCP Servers](https://glama.ai/mcp/servers) - Glama.ai提供的MCP服务器列表

## 使用说明

要使用MCP服务器，您需要在配置文件中设置相应的服务器信息。典型的配置包括命令、参数、权限设置等。

**MacOS mcp配置文件格式 :**

```
{
  "mcpServers": {
    "sequential-thinking": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-sequential-thinking"
      ]
    },
   "playwright": {
      "command": "npx",
      "args": ["-y", "@executeautomation/playwright-mcp-server"]
    },
    "memory": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-memory"
      ]
    }
  }
}
```




**windows mcp配置文件格式 :**

```
{
  "mcpServers": {
    "sequential-thinking": {
      "command": "cmd",
      "args": [
        "/c",
        "npx",
        "-y",
        "@modelcontextprotocol/server-sequential-thinking"
      ]
    },
   "playwright": {
      "command": "cmd",
      "args": [
      "/c",
      "npx",
        "-y",
         "@executeautomation/playwright-mcp-server"]
    },
    "memory": {
      "command": "cmd",
      "args": [
      "/c",
      "npx",
        "-y",
        "@modelcontextprotocol/server-memory"
      ]
    }
  }
}
```



## 贡献

欢迎贡献更多的MCP服务器资源或改进现有内容。请通过提交Pull Request或Issue来参与项目。

## 许可证

本项目采用MIT许可证。详情请参阅LICENSE文件。