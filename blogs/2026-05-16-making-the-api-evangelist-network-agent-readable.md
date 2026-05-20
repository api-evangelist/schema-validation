---
title: "Making the API Evangelist Network Agent-Readable"
url: "https://apievangelist.com/blog/2026/05/16/making-the-api-evangelist-network-agent-readable/"
date: "2026-05-16T00:00:00+00:00"
author: "Kin Lane"
feed_url: "https://apievangelist.com/feed"
---
I spent the day applying the agent-readiness playbook across twenty-two subdomains of the API Evangelist network. The result is end-to-end agent-readable infrastructure — RFC 9264 linksets at /.well-known/api-catalog on every site, a Cloudflare Worker doing markdown content negotiation in front of GitHub Pages, agent skills at /skills/, a JSON-LD context for the API Evangelist vocabulary, and AI consent signals in every robots.txt. Twenty-two sites.
