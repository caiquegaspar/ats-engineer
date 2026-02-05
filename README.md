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

## ⚖️ Licença e Permissões de Uso

Este projeto adota um modelo de **licenciamento híbrido** para proteger a propriedade intelectual do autor enquanto permite o uso livre das ferramentas técnicas fornecidas.

### 1. Manual Técnico (PDF) e Metodologia

O arquivo **`ATS_Engineer.pdf`** e o texto explicativo deste repositório são protegidos por direitos autorais.
**© 2026 Caíque Barbosa Gaspar. Todos os direitos reservados.**

🚫 **Proibições:**

- É proibida a redistribuição, revenda ou hospedagem do PDF em outros servidores ou sites.
- É proibida a alteração ou criação de obras derivadas baseadas no texto do manual.

### 2. Ferramentas (Templates LaTeX e Prompts)

O código fonte contido nas pastas `bonus-1/` (Prompts) e `bonus-2/` (Templates LaTeX) é disponibilizado sob a licença **MIT**, para incentivar o uso prático.

✅ **Você tem permissão para:**

- Baixar, editar e utilizar os templates para criar seu currículo pessoal.
- Utilizar, modificar e adaptar os prompts para uso pessoal ou profissional.
- Compartilhar o seu currículo gerado (o PDF final com seus dados) livremente.

_Nota: O template utiliza a classe `awesome-cv`, que possui sua própria licença (LaTeX Project Public License), respeitada neste projeto._

---

## ⚠️ Disclaimer

Este projeto é um estudo de engenharia reversa com fins educacionais e profissionais. O autor não possui vínculo com as empresas detentoras das plataformas ATS citadas (Gupy, Workday, etc.) e as marcas registradas pertencem aos seus respectivos proprietários.

---

## 🧭 Observação Final

Este projeto foi desenvolvido a partir de:

- pesquisa independente
- experimentação prática
- análise de plataformas ATS reais
- consolidação técnica orientada a engenharia

Não se trata de aconselhamento genérico de RH, mas de **engenharia aplicada a sistemas de triagem automática**.
