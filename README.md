# soc-quick-check
Simple web-based threat intel triage helper for SOC N1 (public sources only)
# SOC Quick Check

Proof of Concept (PoC) de uma extensão para Google Chrome voltada à triagem rápida de indicadores de comprometimento (IOCs) em ambientes SOC N1.

## Objetivo

Reduzir o tempo operacional gasto na consulta manual de IPs, domínios e URLs em múltiplos portais públicos de Threat Intelligence.

## Como funciona

A extensão permite:
- Inserir um IP, domínio ou URL uma única vez
- Selecionar quais portais públicos consultar
- Abrir automaticamente as consultas em novas abas do navegador

Nenhum dado é coletado, armazenado ou correlacionado.

## Fontes públicas utilizadas

- VirusTotal
- AbuseIPDB
- MXToolbox
- URLScan.io
- DomainTools Whois

## Status do projeto

Projeto em estágio inicial (PoC).
Foco em aprendizado, automação simples e boas práticas operacionais.

## Aviso

Ferramenta de apoio à triagem inicial.
Não substitui SIEM, SOAR ou investigações aprofundadas.
