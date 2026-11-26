# TechOS — Gestão de Ordens de Serviço (MVP — 5ª Entrega UCSAL)

**Disciplina:** Processos de Negócios — UCSAL (Prof. Haroldo Peon)  
**Equipe (Dupla):** João Victor Costa Nascimento e Vinicius Freitas de Oliveira Souza  

## Sobre o MVP
O **TechOS** é uma aplicação web operacional desenvolvida para pequenas assistências técnicas de computadores e notebooks em Salvador/BA, cobrindo integralmente:
- **Processos BPMN 2.0:** `P01` (Recebimento e abertura de OS), `P02` (Diagnóstico, orçamento versionado com apoio do Google Gemini AI e decisão do cliente), `P03` (Execução do reparo autorizado e verificação de testes), `P04` (Devolução física rastreável e encerramento) e `P05` (Área do Cliente transversal para acompanhamento e aprovação/recusa).
- **Regras de Negócio:** `RN01` a `RN12` com bloqueios ativos e trilha de auditoria.
- **Requisitos de Negócio:** `REQ01` a `REQ08`.

## Como Publicar / Importar no Google AI Studio (`https://aistudio.google.com/`)
1. Acesse [https://aistudio.google.com/apps](https://aistudio.google.com/apps) (ou **Build with Gemini** no menu lateral do Google AI Studio).
2. Clique em **Create new app** / **Import code** e selecione os arquivos deste diretório (`index.html`, `app.js`, `metadata.json`, `package.json`).
3. Clique em **Deploy / Share App** no canto superior direito do Google AI Studio para obter ou atualizar o link público no Google Cloud Run / AI Studio.
