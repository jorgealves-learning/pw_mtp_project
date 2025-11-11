# 🧩 GitHub Issues

Os **GitHub Issues** são uma das principais ferramentas de **colaboração e gestão de tarefas** dentro de um repositório.  
Permitem que as equipas organizem o trabalho, discutam ideias, relatem bugs e planeiem novas funcionalidades — tudo num só lugar.

---

## 📘 O que é um Issue?

Um **Issue** é um espaço dentro do GitHub onde é possível:

- Reportar **bugs** (erros do projeto)  
- Propor **melhorias ou novas funcionalidades**  
- Colocar **questões** à equipa  
- Acompanhar o **progresso de tarefas**  
- Documentar **decisões e discussões**

Cada Issue funciona como uma **thread de conversação** sobre um tópico específico.  
Os membros da equipa podem comentar, adicionar imagens, referenciar commits e fechar o Issue quando a tarefa estiver concluída.

🟢 **Diferença entre Issues e Discussions:**
- **Issues** → Usados para *tarefas acionáveis* (algo que precisa de ser resolvido).  
- **Discussions** → Usadas para *conversas gerais, brainstorming e ideias* ainda não transformadas em tarefas.

---

## 🧰 Como Criar um Issue (Passo a Passo)

1. Acede ao separador **Issues** do repositório.  
2. Clica em **New Issue**.  
3. Escolhe um **template** (se existir).  
4. Escreve um **título curto e claro**.  
5. Adiciona uma **descrição detalhada** a explicar o problema, objetivo ou sugestão.  
6. Define **labels**, **assignees** e **milestones** (ver secção seguinte).  
7. Clica em **Submit new issue**.

### 🧩 Exemplo

| Campo | Exemplo |
|-------|----------|
| **Título** | Adicionar secção sobre Revisão de Pull Requests |
| **Descrição** | É necessário documentar o processo de revisão de PRs com exemplos práticos. |
| **Labels** | `documentation`, `enhancement` |
| **Assignee** | @o-teu-utilizador |

---

## 🏷️ Labels, Assignees e Milestones

### 🏷️ Labels  
As **labels** são etiquetas que ajudam a categorizar Issues.  
Exemplos comuns:

- 🐛 `bug` → erro ou problema no projeto  
- ✨ `enhancement` → melhoria ou otimização  
- 🧱 `documentation` → tarefas relacionadas com documentação  
- ❓ `question` → questões gerais  
- 🚀 `feature` → nova funcionalidade  

É possível criar labels personalizadas em **Settings → Labels**.

---

### 👤 Assignees  
Os **assignees** são os responsáveis por resolver o Issue.  
É boa prática atribuir sempre alguém para garantir que a tarefa avança.

---

### 🎯 Milestones  
Os **milestones** permitem agrupar Issues por **versão, fase ou objetivo**.  
Exemplos:

- *Versão 1.0*  
- *Entrega Final*  
- *Sprint 3*

---

## 🔗 Associar Issues a Commits e Pull Requests

Ligar Issues a commits e PRs ajuda a manter o histórico do projeto organizado.  
Podes fazê-lo de várias formas:

### 🔸 Nos Commits
Ao fazer um commit, podes referenciar um Issue assim:

```bash
git commit -m "docs: atualizar secção sobre GitHub Issues (#12)"
