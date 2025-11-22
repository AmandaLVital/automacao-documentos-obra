# Automação Completa de Documentos da Construção Civil (Python)

Este repositório apresenta o projeto que desenvolvi para automatizar a geração de documentos técnicos usados em processos de obras, como:

- alvará de construção  
- regularização  
- habite-se  
- declarações
- procurações  
- requerimentos  
- relatórios fotográficos  
- entre outros documentos exigidos por prefeituras  

O objetivo foi eliminar tarefas repetitivas, reduzir erros e aumentar produtividade.

---

## 🎯 Problema

Os processos de obra exigem muitos documentos com informações semelhantes (dados do cliente, responsável técnico, imóvel, medidas etc.).

Antes da automação:

- Eu precisava preencher **cada documento manualmente**
- O relatório fotográfico demandava **inserir foto por foto**
- Era fácil cometer erros de digitação (RG, endereço, numeração)
- Cada processo consumia horas apenas com burocracia

---

## 🚀 Solução Desenvolvida

Desenvolvi uma automação completa usando **Python**, conectada a uma tabela no Google Sheets.

### **Fluxo da solução**
1. Preencho uma planilha chamada **"tabela_automacao"** com todas as informações necessárias (cliente, imóvel, obra, responsável técnico).
2. O script Python:
   - lê os dados da planilha  
   - abre os documentos-modelo  
   - substitui automaticamente os campos  
   - gera todos os documentos prontos  
3. Para o relatório fotográfico, o script:
   - lê a pasta de fotos  
   - insere todas no documento  
   - organiza automaticamente em páginas  

---

## 🛠 Tecnologias utilizadas

- **Python**
- `python-docx` para manipular documentos .docx  
- `pandas` para leitura dos dados  
- `gspread` ou leitura via CSV/exportação do Google Sheets  
- `reportlab` (opcional, para PDFs)  
- Visual Studio Code como ambiente principal  
- Automação de pastas e arquivos usando `os` e `pathlib`

---

## ✅ Resultados

- Redução de horas de trabalho manual para **minutos**
- Eliminação quase total de erros de escrita
- Escalabilidade para múltiplos projetos simultâneos
- Processo padronizado e muito mais profissional
- Permite focar no projeto arquitetônico em si

---

## 📁 Estrutura do Repositório

