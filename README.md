# ATS Engineer — Technical Manual

**Engineering the Resume Screening Pipeline**

Este repositório funciona como **registro público de autoria, anterioridade e material técnico de apoio** do projeto **ATS Engineer — Engenharia Reversa do Processo Seletivo**.

O conteúdo principal está consolidado no PDF técnico, enquanto este repositório reúne:

- artefatos complementares,
- templates LaTeX,
- provas de integridade,
- e instruções de uso técnico.

---

## 📄 Conteúdo Principal

- **ATS_Engineer.pdf**  
  Manual técnico completo sobre:
  - Funcionamento interno de ATS (Applicant Tracking Systems)
  - Parsing, tokenização e normalização de texto
  - Densidade e clusterização semântica de palavras-chave
  - Compatibilidade com plataformas como **Gupy, Workday, Greenhouse, Lever**
  - Estratégias práticas para currículos humanos + ATS-friendly

---

## 🧩 Estrutura do Repositório

```

.
├── ATS_Engineer.pdf        # Manual técnico principal
├── HASH.txt                # Hash SHA-256 do PDF (prova de integridade)
├── README.md               # Este arquivo
├── index.html              # Página simples de referência (opcional)
├── bonus-1/                # Prompt Mestre (ATS Engineer Mode)
└── bonus-2/                # Template LaTeX profissional
    ├── curriculo_template_ats.tex
    ├── awesome-cv.cls
    ├── fonts/
    └── exemplo_compilado.pdf

```

---

## 🧪 Prova de Integridade & Anterioridade

O arquivo **HASH.txt** contém o hash criptográfico **SHA-256** do PDF original.

Isso permite:

- Verificar que o conteúdo **não foi alterado**
- Comprovar a **existência pública do material nesta data**
- Usar commits do GitHub como **timestamp público imutável**

### Verificação local

```bash
sha256sum ATS_Engineer.pdf
```

Compare o resultado com o valor registrado em `HASH.txt`.

---

## 🧠 Bônus 1 — Prompt Mestre (ATS Engineer Mode)

O diretório `bonus-1/` contém um **prompt avançado** para orientar IAs a:

- reescrever currículos com foco em ATS,
- priorizar parsing, tokens e clusters semânticos,
- gerar conteúdo compatível com triagem automática.

Compatível com múltiplos modelos (ChatGPT, Gemini, Grok, DeepSeek, etc).

---

## 📐 Bônus 2 — Template LaTeX Profissional (ATS-Friendly)

O diretório `bonus-2/` inclui um **template LaTeX profissional**, otimizado para ATS, com:

- layout single-column
- tipografia consistente
- metadados configuráveis
- parsing limpo para PDF

---

## ✏️ Como Editar o Template (Overleaf)

> 🔗 **Link do projeto no Overleaf (somente leitura):**
> **[overleaf.com/read/ftpphsxjmgqy#a87aaf](https://www.overleaf.com/read/ftpphsxjmgqy#a87aaf)**

⚠️ **Importante:** o projeto no Overleaf está em modo **read-only**.

Para editar o currículo:

1. Acesse o link do Overleaf acima
2. Faça login ou crie uma conta gratuita no Overleaf
3. Clique em **"Copy Project"** (ou **"Make a Copy"**)
4. O projeto será clonado para sua conta
5. Edite normalmente os arquivos `.tex` no navegador
6. Compile e exporte o PDF final

Essa abordagem garante:

- preservação do projeto original
- controle total da sua versão
- edição sem necessidade de ambiente local

---

## 🖥️ Compilação Local (Opcional)

Caso prefira compilar localmente:

```bash
# Ubuntu / Debian
sudo apt-get install texlive-xetex texlive-fonts-extra

# Compilação
xelatex curriculo_template_ats.tex
```

---

## 👤 Autoria

**Autor:** Caíque Barbosa Gaspar
**Ano:** 2026
**Status:** Obra original de autoria própria

Este repositório e seus commits funcionam como **registro técnico e público de autoria**.

---

## ⚠️ Aviso Legal

Este repositório **não concede licença de uso, reprodução ou redistribuição** do conteúdo integral.

Qualquer reprodução não autorizada caracteriza violação de direitos autorais.

---

## 🧭 Observação Final

Este projeto foi desenvolvido a partir de:

- pesquisa independente
- experimentação prática
- análise de plataformas ATS reais
- consolidação técnica orientada a engenharia

Não se trata de aconselhamento genérico de RH, mas de **engenharia aplicada a sistemas de triagem automática**.
