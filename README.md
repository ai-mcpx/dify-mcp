## dify-mcp

**Author:** [craftslab](https://github.com/craftslab)  
**Version:** 0.1.0  
**Type:** agent-strategy  
**Github Repo:** [dify-mcp](https://github.com/ai-mcpx/dify-mcp)  
**Github Issues:** [issues](https://github.com/ai-mcpx/dify-mcp/issues)  


---


### Description

#### Configuration

```json
{
  "server1": {
    "url": "http://127.0.0.1:8000",
    "headers": {},
    "timeout": 60,
    "sse_read_timeout": 300
  },
  "server2": {
    "url": "http://127.0.0.1:8001/sse",
    "headers": {},
    "timeout": 60,
    "sse_read_timeout": 300
  }
}
```


---


### Reference

- [agent-strategy-plugin](https://docs.dify.ai/plugins/quick-start/develop-plugins/agent-strategy-plugin)
- [dify-plugin-agent-mcp_sse](https://github.com/junjiem/dify-plugin-agent-mcp_sse)
