# Gestão de Custos de Projetos com IA — Portal do Curso

Ambientes interativos para ensinar gestão de custos de projetos com apoio de IA.
São páginas HTML **autossuficientes** (CSS e JavaScript embutidos): funcionam em
qualquer navegador, no computador ou no celular, **sem instalar nada e sem login**.

Autor: **Prof. Dr. Thiago Lima**.

## Fluxo da aula

**Parte 1 (teoria) → Parte 2 (prática)**

1. **Jornada** — a base conceitual (planejar, controlar, decidir), com analogias. Sem prompts.
2. **Consultor de Projetos** — a mesa de decisão executiva, onde acontece a prática com IA.
3. **Ficha do caso ZapRango** — para aplicar os prompts e exportar um relatório.

## Conteúdo

| Arquivo | O que é |
|---|---|
| `index.html` | Página-portal que lista e linka todos os materiais (abra este primeiro). |
| `jornada-custos-projeto.html` | **Parte 1 · teoria.** Conceitos de custos com analogias; sem IA. |
| `consultor-de-projetos.html` | **Parte 2 · prática.** Mesa de decisão (5 rodadas A/B/C), prompts no formato PTCF, campo para colar respostas, exportação de relatório e a aba **"Crie seu Especialista"** (GPT/Gem/Claude). |
| `ficha-dados-caso.html` | Ficha do caso ZapRango: prompts PTCF prontos e editáveis, campo para colar a resposta da IA em cada bloco e exportação do relatório. |
| `exemplo-respostas-ia.html` | Exemplo de como a IA responde a cada prompt (referência). |
| `gabarito-comentado-ZapRango.docx` | Gabarito comentado (Word), passo a passo das respostas. |

> Os prompts seguem o modelo **PTCF** (Persona · Tarefa · Contexto · Formato), uma
> estrutura simples para escrever bons pedidos à IA — que o aluno aprende usando.

## Novidades desta versão

- **Prompts em PTCF** na Ficha e no Consultor (rótulos Persona/Tarefa/Contexto/Formato destacados).
- **Colar respostas da IA**: abaixo de cada prompt há um campo para o aluno colar o que a IA respondeu.
- **Exportar relatório**: botões para baixar (`.txt`) ou copiar um relatório com os prompts e as respostas (no Consultor, inclui também o resumo das decisões das 5 rodadas).
- **Aba "Crie seu Especialista"** no Consultor: texto pronto de um consultor de custos para colar em um GPT personalizado, um Gem (Gemini) ou um Projeto no Claude, além de um modelo em branco para o aluno criar o seu.

## Como publicar / atualizar no GitHub Pages (≈5 minutos)

1. Crie um repositório **público** no **github.com** (ou use o existente).
2. Clique em **Add file → Upload files** e arraste **todos os arquivos desta pasta**
   (os `.html`, o `.docx` e este `README.md`). Para **atualizar**, basta subir o
   arquivo com o **mesmo nome** — o GitHub sobrescreve o anterior. Depois clique em
   **Commit changes**.
3. Vá em **Settings → Pages**. Em *Branch*, selecione **main** e a pasta **/(root)**.
   Clique em **Save**.
4. Aguarde ~1 minuto e recarregue. O GitHub mostrará o link público, algo como:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`
5. Esse link abre o **portal** (`index.html`). Compartilhe-o com a turma.

> **Atenção aos nomes dos arquivos.** Os links do portal e a navegação entre as
> páginas dependem dos nomes exatos abaixo. Se o navegador salvar como
> `arquivo (1).html`, renomeie para o nome correto antes de subir:
> `index.html`, `jornada-custos-projeto.html`, `consultor-de-projetos.html`,
> `ficha-dados-caso.html`, `exemplo-respostas-ia.html`, `gabarito-comentado-ZapRango.docx`.

## Observações sobre a IA

- O simulador **não depende de IA para funcionar**. Os prompts são fornecidos para o
  aluno **copiar e colar** na IA de sua preferência (ChatGPT, Claude, Gemini etc.).
- Os **campos de resposta** guardam o texto **enquanto a página estiver aberta**.
  O fluxo previsto é: colar as respostas e **exportar o relatório na mesma sessão**.
  Se a aba for fechada ou recarregada antes de exportar, o conteúdo colado se perde
  (nada é salvo no navegador, por simplicidade e privacidade).
- A aba **"Crie seu Especialista"** entrega o texto de configuração pronto e o passo a
  passo; a criação do assistente acontece na conta do aluno em cada plataforma.

## Licença de uso

Material didático para uso educacional. Sinta-se livre para adaptar os textos, os
números dos casos e a identidade visual às necessidades da sua turma.
