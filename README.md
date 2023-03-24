# Clash Self Rule

This repo contains the rules of clash which only used myself.

- `Cloudflare.yaml` contains Cloudflare CDN
- `OpenAI.yaml` contains OpenAI url

## Usage

Add code to rule-providers: 
```yaml
  NameHere:
    type: http
    behavior: classical
    url: "https://ghproxy.com/raw.githubusercontent.com/evalexp/SelfRules/main/FileNameHere"
    path: ./ruleset/NameHere.yaml
    interval: 86400
```