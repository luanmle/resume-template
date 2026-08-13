# Template de Currículo em LaTeX (ATS-Friendly)

Este repositório disponibiliza um template de currículo limpo e customizável desenvolvido em LaTeX bsaeado no modelo Harvard Resume Template.

Criei este modelo para minhas próprias aplicações em vagas de **estágio e nível júnior**. Por isso, sua estrutura foi pensada para destacar **projetos e formação acadêmica** em vez da experiência profissional tradicional. Além disso, seu layout em texto puro garante que ele seja **ATS-friendly**, ou seja, lido perfeitamente por softwares automatizados de recrutamento.

---

## 🚀 Como Utilizar

Você pode copiar o código do arquivo `.md` (ou `.tex`) e compilá-lo para PDF de duas formas:

### 1. Via Overleaf (Recomendado e mais rápido)
O **[Overleaf](https://pt.overleaf.com/)** compila o código e exporta o PDF nativamente, sem instalar nada.
1. Crie um projeto em branco (*Blank Project*).
2. Substitua o código padrão do `main.tex` pelo código do template.
3. Edite com os seus dados (substitua os textos de *mock*).
4. Clique em **Recompile** e baixe seu PDF.

### 2. Edição Local (VS Code, Sublime, etc.)
Você pode editar o `.tex` em seu editor de texto preferido. **Atenção:** para exportar em PDF localmente, será necessário ter uma distribuição LaTeX instalada no seu computador (como [TeX Live](https://tug.org/texlive/) ou [MiKTeX](https://miktex.org/)).

---

## 🗂️ Estrutura do Template

A estrutura é estratégica para quem está no início da carreira:

* **Cabeçalho:** Seu nome e links essenciais (Contato, LinkedIn, GitHub).
* **Objetivo Profissional:** Um resumo direto sobre sua área de atuação e o que você busca.
* **Formação Acadêmica (Destaque):** Instituição, previsão de conclusão e matérias relevantes.
* **Experiência de Projetos (Destaque principal):** Onde você comprova na prática o que sabe fazer através de projetos pessoais, acadêmicos ou de extensão.
* **Experiência Profissional:** Seu histórico de trabalho. Caso venha de outra área, foque em *soft skills* e resultados alcançados.
* **Habilidades Técnicas:** Lista categorizada de linguagens, ferramentas e conceitos por palavras-chave (ótimo para ATS).
* **Idiomas:** Nível de proficiência e capacidade de uso.

---

## 🛠️ Dicas Rápidas
* No LaTeX, caracteres como `%`, `&` e `#` são comandos. Para usá-los como texto, coloque uma barra invertida antes (ex: `\%`).
* Adicione novos tópicos em listas criando novas linhas com o comando `\item`.

Boa sorte!
