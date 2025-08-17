# chatgpt_5_structured_asking_question

This repo shares a structured method for asking ChatGPT better questions to build systems faster.

[Messy] ──refine──► [Structured] ──run──► [Better Output]
    ▲                               │
    └───────────────feedback────────┘   (iterate to improve)

Developers love practical samples. For example:

Laravel backend API prompt

Go microservice prompt

DevOps automation SOP prompt


## In development 

```xml
<guiding_principles part="1">
  <!-- API & Backend -->
  - Use Golang for backend
  - Parser API from e-solat.gov.my
  - Cache JSON fallback 7 days
</guiding_principles>

<guiding_principles part="2">
  <!-- Frontend -->
  - TailwindCSS for styling
  - Responsive layout
  - Dropdown zone selector
</guiding_principles>

<guiding_principles part="3">
  <!-- Integration -->
  - Provide REST API for frontend
  - Fallback if API down
</guiding_principles>
```
## In Security 

```xml
<security_principles part="headers">
  - Add security headers (CSP, XFO, HSTS, Referrer-Policy)
</security_principles>

<security_principles part="rate_limit">
  - Rate limit API: 1 req/sec, burst 5
</security_principles>

<security_principles part="waf">
  - Install Nginx + ModSecurity
  - Enable OWASP CRS
  - Log WAF alerts
</security_principles>

<security_principles part="ssh">
  - Disable root login
  - Allow only key-based auth
  - Fail2ban enabled
</security_principles>
```

In Infra 

```xml
<infra_principles part="1">
  <!-- Server & OS -->
  - Ubuntu 24.04 LTS
  - Harden SSH
  - Auto apply security updates
</infra_principles>

<infra_principles part="2">
  <!-- Networking -->
  - Tailscale VPN
  - UFW firewall default deny
  - Caddy reverse proxy
</infra_principles>

<infra_principles part="3">
  <!-- Monitoring -->
  - Prometheus + Grafana
  - Loki for logs
  - Telegram alerts
</infra_principles>

<infra_principles part="4">
  <!-- Backup -->
  - Daily DB backup → S3
  - Weekly snapshot → NAS
  - Retention 7/4/3
</infra_principles>
```

Exmaple

```xml
<code>
 <code_editing_rules>
- Apps: Waktu Solat Apps
<guiding_principles>
- Parser Api dari e-solat.gov.my
- View Solat time 
- Create API 
- Create 2 days fallback cache using json 
- create dropdown zone to change zone 
- zone as https://raw.githubusercontent.com/hardyweb/e-solat/refs/heads/main/zone.json 
</guiding_principles>


<back_end_defaults>
- Programming: Golang 
</back_end_defaults>
<frontend_stack_defaults>
- Syling: tailwindCSS
</frontend_stack_defaults>


<other_instructions>
- create all func in main.go
</other_instructions>
</code_editing_rules>

</code>
```
