# Lab 5 – LangGraph Studio et Multi-Agents

**Auteur : Najlaa Nacif**

## TP 1 – LangGraph Studio

### Objectif
Visualiser et tester un agent LangGraph à l'aide de LangGraph Studio.

### Exécution

```bash
uv run langgraph dev
```

Question testée :

```text
Qui est le personnage principal ?
```

Réponse obtenue :

```text
Le personnage principal est un jeune homme nommé Jack,
qui découvre un ancien artefact magique.
```

### Résultat obtenu

<img width="772" height="496" alt="capture_langgraph" src="https://github.com/user-attachments/assets/884dab9f-c32c-4f58-9e62-95a3689f182c" />


---

## TP 2 – Multi-Agents

### Objectif
Construire un système composé :

- d'un agent principal
- de deux sous-agents spécialisés

### Outils créés

- `square_root()`
- `square()`

### Sous-agents

- `subagent_1` → calcule les racines carrées
- `subagent_2` → calcule les carrés

### Test réalisé

Question :

```text
What is the square root of 456?
```

Résultat attendu :

```text
21.354156504062622
```

---

## Structure du dossier

```text
Lab5-LangGraph Studio/
│
├── agent_simple.py
├── multi_agents.py
├── langgraph.json
└── README.md
```

## Technologies utilisées

- Python
- LangChain
- LangGraph
- LangGraph Studio
- OpenAI
- uv
