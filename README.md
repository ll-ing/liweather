## 计算器，天气查询 MCP
基于 Model Context Protocol(MCP)的数值计算器，提供了简单的加运算，和简单的天气查询


## 工具列表
| name | description |
| ---------|---------|
| add |执行浮点数加法运算 |
| get_city_weather |获取城市天气信息 |

## inspector
```
npx @modelcontextprotocol/inspector uvx liweather
```


## MCP 服务器配置
```
{
  "mcpServers": {
    "liweather": {
      "command": "uvx",
      "args": [
        "liweather"
      ]
    }
  }
}
```

