<img width="2048" height="682" alt="ChatGPT Image 2 de ago  de 2026, 22_31_51" src="https://github.com/user-attachments/assets/95a84202-f829-464a-9a12-5670f07e7abf" />

A estrutura proposta é tecnicamente sólida, mas contém **dois pontos críticos** que violam a coerência e os dados verificáveis do seu perfil antes de realizar o commit:

---

### Inconsistências Críticas a Corrigir

1. **Reexposição do E-mail em Texto Claro (Quebra de Higiene Digital):**
* A linha `- ✉️ gustavo.f.p.f@outlook.com.br` foi reinserida na seção de links.
* **Problema:** Expor o e-mail em texto puro no `README.md` anula a diretriz de redução da superfície de contato que o próprio artigo defende contra *scrapers* de engenharia social. O contato deve permanecer centralizado no LinkedIn.


2. **Placeholder Quebrado de DOI:**
* A linha `- 📄 [Zenodo / DOI](https://doi.org/10.5281/zenodo.XXXX)` contém `XXXX` como valor fictício.
* Links com prefixos vazios ou fictícios quebram a credibilidade técnica. Deve-se apontar para o DOI real já emitido (`10.5281/zenodo.21706931`) ou direcionar para a página geral de depósitos do autor.



---

### Versão Corrigida e Higienizada para Commit

```markdown
## Gustavo F. Paluch

🇬🇧 [English version](./README_en.md)

**Engenheiro da Computação • Cibersegurança • Infraestrutura de TI • DevOps • IoT • IA Aplicada**

[GitHub](https://github.com/GustavoFelipe85) • [LinkedIn](https://www.linkedin.com/in/gustavofpaluch/) • [ORCID](https://orcid.org/0009-0008-0989-8913) • [Lattes](http://lattes.cnpq.br/3233095819966467)

---

### 👨‍💻 Sobre mim

Sou **Engenheiro da Computação**, com atuação e interesse técnico em **cibersegurança, infraestrutura de TI, DevOps, Internet das Coisas e inteligência artificial aplicada**.

Desenvolvo projetos que conectam **hardware embarcado, comunicação segura, pipelines de dados, conteinerização, observabilidade e experimentação computacional**, com ênfase em arquiteturas reprodutíveis e documentação técnica rigorosa.

**Cisco Certified CyberOps Associate** | Autor de análise sobre **Proxy Interviews, engenharia social via GitHub e governança de segurança corporativa**.

📍 Cascavel, Paraná — Brasil

---

### 🔬 Áreas de atuação e pesquisa

- Cibersegurança, governança técnica e monitoramento de ambientes
- Infraestrutura Linux, Docker e automação de pipelines
- Internet das Coisas e sistemas ciberfísicos
- Sistemas distribuídos e pipelines de telemetria
- Agricultura de precisão e automação agrícola
- Arquitetura de computadores e análise empírica de desempenho
- Computação paralela com OpenMP e MPI
- Inteligência artificial aplicada a sistemas e dados

---

### 🛡️ Publicação em destaque — Engenharia Social via GitHub

**Quando o GitHub vira vetor de engenharia social: o risco dos Proxy Interviews no recrutamento remoto**

Análise de caso real de abordagem direcionada via GitHub, com mapeamento de fluxos de fraude de identidade, riscos de *insider threat* em pipelines CI/CD, quebra de governança/compliance e diretrizes preventivas para desenvolvedores.

🔗 [Artigo no LinkedIn Pulse](https://www.linkedin.com/pulse/quando-o-github-vira-vetor-de-engenharia-social-risco-gustavo-xfcgf/) | [Publicação no TabNews](https://www.tabnews.com.br/GustavoFPaluch/quando-o-github-vira-vetor-de-engenharia-social-o-risco-dos-proxy-interviews-no-recrutamento-remoto)

---

### 🚜 Projeto em destaque — Smart Farm IoT System

O **Smart Farm IoT System** é uma arquitetura IoT segura, modular e reprodutível para monitoramento ambiental e evolução futura para automação agrícola.

**Arquitetura**
```text
ESP32 + sensores → MQTT/Mosquitto → Python Consumer → InfluxDB → Grafana

```

**Principais recursos**

* Comunicação MQTT autenticada com QoS 1;
* Contrato de dados versionado com validação estrita via JSON Schema;
* Validação estrutural antes da persistência;
* Normalização de payloads legados e API com FastAPI;
* Ambiente reprodutível orquestrado com Docker Compose;
* Observabilidade contínua com InfluxDB e Grafana;
* Esteira de integração contínua (CI) com GitHub Actions.

**Evidências experimentais preliminares**

* Latência média do pipeline próxima de **118 ms** com validação ativa;
* Throughput superior a **10.000 mensagens por hora**;
* Bloqueio de **100% dos payloads inválidos** nos testes sob estresse.

🔗 [Acessar o repositório](https://github.com/GustavoFelipe85/smart-farm-iot-system)

📚 [Documentação técnica e acadêmica](https://github.com/GustavoFelipe85/smart-farm-iot-system/blob/main/README.md)

---

### 🎓 Formação e atividade acadêmica

* **Bacharel em Engenharia da Computação — UNISA, 2024**
* Em 2026, participou como **aluno especial** da disciplina de **Arquitetura de Computadores** no PPGComp/UNIOESTE (60 horas, 4 créditos).
* Estudos experimentais envolvendo microarquitetura de processadores, hierarquia de memória, taxa de falha de cache (*cache misses*), profiling com Valgrind e escalabilidade com OpenMP e MPI.

---

### 🛠️ Tecnologias

**Linguagens e desenvolvimento**

`Python` • `C` • `C++` • `FastAPI` • `JSON Schema`

**Infraestrutura e DevOps**

`Linux` • `Ubuntu` • `Docker` • `Docker Compose` • `GitHub Actions` • `CI/CD`

**IoT e dados**

`ESP32` • `MQTT` • `Mosquitto` • `InfluxDB` • `Grafana` • `Séries Temporais`

**Arquitetura e paralelismo**

`Valgrind` • `Callgrind` • `Cachegrind` • `OpenMP` • `MPI` • `MPICH`

---

### 🔗 Links acadêmicos e profissionais

* 💼 [LinkedIn](https://www.linkedin.com/in/gustavofpaluch/)
* 🧪 [ORCID](https://orcid.org/0009-0008-0989-8913)
* 📚 [Currículo Lattes](http://lattes.cnpq.br/3233095819966467)
* 📦 [Smart Farm IoT System](https://github.com/GustavoFelipe85/smart-farm-iot-system)
* 🧠 [CELUS Design Studio](https://app.celus.io/workspaces/62bcb5b7-98f0-40a1-8b20-6d3f2fd2e6b4)
* 📄 [Preprint / DOI (Zenodo)](https://www.google.com/search?q=https://doi.org/10.5281/zenodo.21706931)

---

Projetos orientados por **segurança, reprodutibilidade, experimentação e documentação técnica**.

```

Essa versão mantém o perfil alinhado aos fatos observáveis, elimina dados fictícios e preserva o isolamento do seu e-mail corporativo.

```
