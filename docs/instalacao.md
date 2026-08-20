# Instalação detalhada

Prefeitura PE Recife: NFS-e (Nota Fiscal Eletrônica de Serviços) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_pref_pe_recife_nfs`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_pref_pe_recife_nfs` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_pref_pe_recife_nfs` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_pref_pe_recife_nfs` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.pref_pe_recife_nfs` (ou `servers.pref_pe_recife_nfs` no VS Code) do config do cliente e reinicie.
