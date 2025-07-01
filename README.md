cd liweather
# 安装构建工具
uv add build twine
# 构建您的Python包
uv run -m build
# 上传您的Python包
uv run -m twine upload dist/***.whl
# 通过inspector快速测试
npx @modelcontextprotocol/inspector uvx liweather