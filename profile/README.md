# Apier

Apier gives AI agents machine-verifiable Norwegian company authority: company status, registered roles and the register's coded signing rules (signaturrett and prokura) from Brønnøysundregistrene (Brreg), over REST or MCP. Each answer carries its source and retrieval time, and you can ask for a signed receipt that anyone can check offline.

Norsk: Maskinverifiserbar norsk signaturrett for AI-agenter: selskapets registrerte signaturregler fra Brønnøysundregistrene, med historikk og signerte kvitteringer.

## Try it in 30 seconds (no key)

```bash
curl -s https://www.apier.no/api/v1/sandbox/public/company/999999999/authority
```

The public sandbox answers for the fictional test company `999999999` without a key or an account.

## Repositories

| Repository | What it is |
|---|---|
| [apier-mcp](https://github.com/apier-no/apier-mcp) | `@apier-no/mcp`, the npm proxy that connects stdio MCP clients to the hosted Apier MCP server |
| [apier-quickstart](https://github.com/apier-no/apier-quickstart) | Runnable examples in curl, TypeScript, Python and Go, and a comparison with Brreg's open APIs |
| [apier-python](https://github.com/apier-no/apier-python) | Python client with no runtime dependencies |
| [n8n-nodes-apier](https://github.com/apier-no/n8n-nodes-apier) | n8n community node for signing authority and register changes |

## Links

- Website: https://apier.no
- Docs: https://www.apier.no/docs
- MCP docs: https://www.apier.no/docs/mcp
- Pricing: https://www.apier.no/pricing
