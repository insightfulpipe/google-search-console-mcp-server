# Google Search Console MCP Server by Insightful Pipe

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/google-search-console)
[![Insightful Pipe](https://img.shields.io/badge/Insightful_Pipe-MCP_Servers-purple)](https://insightfulpipe.com/mcp-servers)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Connect Google Search Console to AI assistants for SEO analytics and search performance insights.**

Part of the [Insightful Pipe MCP Server Collection](https://insightfulpipe.com/mcp-servers) — The Google Search Console MCP server enables Claude, ChatGPT, Cursor, and other AI assistants to analyze your website's search performance. Monitor rankings, track clicks, and get AI-powered SEO recommendations.

[![Explore All MCP Servers](https://img.shields.io/badge/Explore_All-MCP_Servers-blue?style=for-the-badge)](https://insightfulpipe.com/mcp-servers)

![Google Search Console MCP Server](https://insightfulpipe.com/images/google-search-console-icon.svg)

## MCP Server URL

```
https://google-search-console.insightfulmcp.com/
```

## What is Google Search Console MCP?

Google Search Console MCP is a **remote Model Context Protocol server** that provides AI assistants with access to your GSC data. This SEO-focused integration allows you to:

- Query search performance using natural language
- Analyze keyword rankings and click-through rates
- Identify indexing issues and coverage problems
- Get AI-powered SEO recommendations
- Inspect individual URLs for indexing status

## Installation

### Claude

1. Copy the MCP Server URL: `https://google-search-console.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

1. Copy the MCP Server URL: `https://google-search-console.insightfulmcp.com/`
2. Open ChatGPT Settings → **Connections**
3. Click **Add Connection** and paste the URL
4. Authorize with your InsightfulPipe account

### Claude Code

```bash
claude mcp add google-search-console https://google-search-console.insightfulmcp.com/
```

### Cursor

1. Open Cursor Settings → **MCP Servers**
2. Add new server with URL: `https://google-search-console.insightfulmcp.com/`
3. Authorize the connection

## Available Actions

| Action | Description |
|--------|-------------|
| `searchanalytics.query` | Pull Search Console performance metrics grouped by optional dimensions |
| `sites.list` | List all Search Console properties the authenticated account can access |
| `sites.get` | Fetch metadata for a single Search Console property |
| `sitemaps.list` | Return all sitemaps submitted for a property |
| `sitemaps.get` | Retrieve detailed stats for a specific sitemap feed |
| `urlinspection.index.inspect` | Inspect indexing status / crawl info for a single URL |

## Usage Examples

### Search Performance Overview

```
"How is my site performing in Google Search this month?"
```

### Keyword Analysis

```
"What are my top 20 keywords by clicks?"
```

### Ranking Opportunities

```
"Which keywords am I ranking on page 2 that have high impressions?"
```

### CTR Optimization

```
"Which pages have low CTR but high impressions?"
```

### URL Inspection

```
"Check the indexing status of https://mysite.com/new-page"
```

### Sitemap Status

```
"Show me the status of my submitted sitemaps"
```

## Supported Metrics

| Metric | Description |
|--------|-------------|
| Clicks | Total clicks from search |
| Impressions | Times shown in search results |
| CTR | Click-through rate |
| Average Position | Average ranking position |

## Why Google Search Console MCP?

### For SEO Professionals
- **Faster analysis** - Query data conversationally
- **Opportunity discovery** - AI finds ranking opportunities
- **Technical auditing** - Identify indexing issues quickly

### For Content Marketers
- **Content performance** - See which content ranks
- **Keyword research** - Discover what you rank for
- **Optimization priorities** - Know what to improve first

### For Website Owners
- **Search visibility** - Understand Google Search presence
- **Problem detection** - Catch issues early
- **Growth tracking** - Monitor SEO progress

## SEO Workflow Examples

### Find Quick Wins

```
"Show me keywords ranking between position 8-20 with more than 100 impressions"
```

### Content Audit

```
"Which of my blog posts are getting the most clicks from search?"
```

### Technical Health Check

```
"Inspect the indexing status of my homepage"
```

## Security & Privacy

- **Google Cloud Partner** - Official API integration
- **OAuth 2.0** - Secure Google authentication
- **Read-only access** - No changes to your property
- **Data encryption** - Secure transmission

## Explore More MCP Servers by Insightful Pipe

Visit **[insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)** to discover our full collection of MCP servers for marketing and analytics.

### SEO & Performance MCP Servers
- [Google Analytics MCP](https://insightfulpipe.com/mcp-servers/google-analytics) - Website analytics
- [PageSpeed MCP](https://insightfulpipe.com/mcp-servers/pagespeed) - Performance metrics
- [Web Crawler MCP](https://insightfulpipe.com/mcp-servers/crawler) - Site crawling
- [Google My Business MCP](https://insightfulpipe.com/mcp-servers/google-my-business) - Local SEO

### Advertising MCP Servers
- [Google Ads MCP](https://insightfulpipe.com/mcp-servers/google-ads) - Google advertising
- [Facebook Ads MCP](https://insightfulpipe.com/mcp-servers/facebook-ads) - Meta advertising

**[View All MCP Servers →](https://insightfulpipe.com/mcp-servers)**

## Resources

- [Documentation](https://insightfulpipe.com/docs/google-search-console)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blogs)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **All MCP Servers**: [insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)
- **Email**: support@insightfulpipe.com

---

**[Insightful Pipe](https://insightfulpipe.com)** — AI-powered marketing analytics through MCP servers. [Explore all integrations →](https://insightfulpipe.com/mcp-servers)

## License

MIT License - see [LICENSE](LICENSE) for details.
