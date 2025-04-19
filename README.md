# 🛡️ CTFRoom – A SOC Odyssey

[![Status](https://img.shields.io/badge/status-em%20andamento-yellow)]()
[![Nível](https://img.shields.io/badge/nível-intermediário-blue)]()
[![MITRE ATT&CK](https://img.shields.io/badge/framework-MITRE%20ATT%26CK-red)]()

## 🔍 Descrição

Projeto prático baseado no desafio **"A SOC Odyssey – Windows Event IDs"** da plataforma **CTFRoom**. Neste projeto, simulo o dia a dia de um analista de segurança em um **Security Operations Center (SOC)**, realizando investigações baseadas em **Windows Event Logs** e **Sysmon**, com foco em identificação de TTPs e correlação de eventos.

O desafio exige análise minuciosa de eventos do sistema Windows, especialmente execução de **PowerShell**, persistência, movimentação lateral e técnicas adversárias. Utilizo o framework **MITRE ATT&CK** para mapear o comportamento malicioso e automatizo o processo de análise e extração de Event IDs relevantes usando **Python**.

---

```bash
📦 soc-odyssey-windows-events              <- Pasta principal do projeto  
├── logs/                                  <- Arquivos .evtx e de logs brutos  
├── analysis/                              <- Scripts e anotações da análise  
├── ttp-mapping/                           <- Mapeamento MITRE ATT&CK das evidências  
├── report/                                <- Relatório final da investigação  
└── README.md                              <- Descrição geral do projeto
```

---

## 🛠️ Tecnologias e Ferramentas

- 🪟 **Windows Event Logs / Sysmon** – Fonte dos eventos para análise  
- 🧠 **MITRE ATT&CK** – Framework de TTPs  
- 🐍 **Python** – Parsing e automação da análise de logs  
- 📜 **Markdown** – Documentação técnica

---

## ✅ Status

- [x] Criação do repositório  
- [ ] Coleta e preparação dos logs  
- [ ] Análise dos eventos do Sysmon e PowerShell  
- [ ] Identificação de TTPs e correlação de eventos  
- [ ] Criação de scripts de parsing  
- [ ] Relatório técnico final  
- [ ] Finalização e publicação no GitHub  

---

## 📌 Referência

🔗 [CTFRoom – A SOC Odyssey (Windows Event IDs)](https://app.ctfroom.com/vault/a_soc_odyssey_windows_event_ids_63de13a31c364)

---

> 💡 *Este projeto demonstra minha capacidade de investigação em ambiente SOC, aplicando análise comportamental, correlação de eventos, automação com Python e frameworks como o MITRE ATT&CK para identificar comportamentos maliciosos em logs do Sysmon e PowerShell.*
