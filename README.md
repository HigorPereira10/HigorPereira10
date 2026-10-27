<div align="center">

# Higor Pereira

**Desenvolvedor Python · automação, integrações e dados**

Estagiário de desenvolvimento na [L&A Contabilidade](https://github.com/L-A-Contabilidade) · Ciência da Computação na UNIP (7º semestre)

[![Portfólio](https://img.shields.io/badge/Portfólio-10B981?style=for-the-badge&logo=googlechrome&logoColor=white)](https://higorpereira10.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badgehttps://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=whitelogo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg==)](https://www.linkedin.com/in/higor-pereira10)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:higor.pereira368@gmail.com)

</div>

## Sobre mim

No estágio, escrevo robôs e integrações que tiram trabalho manual de um escritório de contabilidade: consultas fiscais em lote, leitura de boletos e notas, envio de obrigações e avisos automáticos para clientes. Fora dele, estudo dados e IA e mantenho o [UnePDF](https://github.com/HigorPereira10/UnePDF), uma ferramenta open source que nasceu de uma necessidade do escritório.

## Projetos em destaque

| Projeto | O que faz | Stack |
| :--- | :--- | :--- |
| [**UnePDF**](https://github.com/HigorPereira10/UnePDF) | Suíte de ferramentas PDF para Windows, 100% offline: unir, dividir, OCR, XML de NF-e para DANFE e assinatura com certificado A1. Instalador nas [releases](https://github.com/HigorPereira10/UnePDF/releases/latest). | Python, PySide6, pyHanko, pytest, GitHub Actions |
| [**Clareza Contábil**](https://github.com/HigorPereira10/Clareza_Contabil) | Junta contas a receber e a pagar de vários ERPs (Conta Azul, Omie, Bling, Nibo, Asaas ou CSV), projeta o fluxo de caixa e gera relatório em Excel. Multi-empresa. | Python, Streamlit, Pandas, pytest |
| [**Regime Tributário**](https://github.com/HigorPereira10/Regime_Tributario) | Consulta em lote o regime tributário de uma lista de CNPJs usando a BrasilAPI. Roda na [web](https://regimetributario.streamlit.app/) ou como executável. | Python, Streamlit, httpx, PyInstaller |
| [**SatVision Cerrado**](https://github.com/HigorPereira10/SatVision-Cerrado) | Detecção de vegetação e desmatamento no Cerrado com imagens Sentinel-2 e modelo ResNet18. | Python, PyTorch, OpenCV, Streamlit |
| [**Gerenciador de Estoque**](https://github.com/HigorPereira10/GerenciadorDeEstoque) | App desktop com arquitetura em camadas e persistência em SQLite. | Java 21, JavaFX, SQLite, JUnit |
| **Ecovision** *(TCC, em andamento)* | Detecção precoce de pragas em estufas: Raspberry Pi com câmera e sensores envia imagens para uma API no Railway que roda o modelo de visão computacional, e o produtor recebe alertas por um app. Código público após a entrega. | Python, Raspberry Pi, TensorFlow Lite, FastAPI, Railway, Supabase, Expo / React Native |

## O que já automatizei na L&A

O código fica em repositórios privados porque lida com dados de clientes.

- **Certificados digitais:** monitor em C# que acompanha a validade dos certificados dos clientes e envia a proposta de renovação pelo WhatsApp, via API do Zappy.
- **Obrigações e consultas fiscais:** envio de DCTFWeb em lote pela Acessórias, consulta de restituições do IRPF e análise de retenções em NFS-e da Prefeitura de São Paulo.
- **Integrações financeiras:** download de notas fiscais de clientes do Mercado Livre pela API oficial, leitura de boletos em PDF para atualizar as cobranças do BPO e conciliação de bases financeiras.
- **Atendimento:** portal em Google Apps Script para clientes enviarem documentos e receptor de webhooks que registra as pesquisas de satisfação em planilha com dashboard.

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Google Apps Script](https://img.shields.io/badge/Apps_Script-4285F4?style=flat-square&logo=google&logoColor=white)
<br>
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
<br>
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Estudando agora:** inteligência artificial, ciência e engenharia de dados, e Amazon S3 e outras tecnologias de nuvem muito usadas em produção.

## Estatísticas

<div align="center">

<img height="165" src="https://github-readme-stats-five-theta-73.vercel.app/api?username=HigorPereira10&show_icons=true&theme=dark&hide_border=true&hide_rank=true&hide=prs,stars&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats-five-theta-73.vercel.app/api/top-langs/?username=HigorPereira10&layout=compact&theme=dark&hide_border=true" />

</div>
