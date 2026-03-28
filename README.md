# 🚀 Switch em Java com Tema da Wanda — Programação de Soluções Computacionais

![Status](https://img.shields.io/badge/status-concluído-green)
![Plataforma](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue)
![Tecnologia](https://img.shields.io/badge/Java-console%20app-orange)

---

## 📖 Sobre o Projeto

Este repositório documenta a implementação de uma atividade prática da disciplina **Programação de Soluções Computacionais**, proposta pelo **Centro Universitário UNA**.

O projeto foi desenvolvido em **Java**, com foco no estudo de **estruturas condicionais com `switch`**, utilizando como contexto as diferentes fases da personagem **Wanda** no universo Marvel.

Foram criadas duas versões do mesmo conceito:

- uma com a sintaxe tradicional do `switch`
- outra com a sintaxe mais moderna usando `switch` como expressão

Os programas foram escritos com sintaxe introdutória, utilizando recursos fundamentais como:

- classe `public`
- método `main`
- variáveis do tipo `String`
- estrutura condicional `switch`
- exibição de resultados com `System.out.println`

---

## 🎯 Objetivos da Atividade

- Praticar lógica de programação com Java
- Compreender o funcionamento do `switch case`
- Comparar a sintaxe tradicional com a sintaxe moderna do `switch`
- Organizar o código em arquivos separados
- Manter o código simples, legível e bem indentado
- Desenvolver a base de programação exigida no início da graduação

---

## 🧩 Conteúdo Prático Desenvolvido

O projeto contém 2 exemplos principais:

1. `WandaSwitchAntigo` com `switch` tradicional
2. `MarvelSwitch` com `switch` em formato de expressão

---

## ⚙️ Estrutura do Projeto

Os exemplos foram organizados em arquivos `.java` na raiz do repositório.

### Estrutura

```text
una-marvel02-java/
├── LICENSE
├── README.md
├── MarvelSwitch.java
└── WandaSwitchAntigo.java
```

### Descrição dos arquivos

- `WandaSwitchAntigo.java` → demonstra o uso do `switch` tradicional com `case`, `break` e `default`
- `MarvelSwitch.java` → demonstra o uso moderno de `switch` com `case ->`
- `README.md` → documentação da atividade
- `LICENSE` → licença do projeto

---

## 💻 Exercícios Desenvolvidos

### 1. WandaSwitchAntigo

O programa define uma fase da Wanda e utiliza a estrutura `switch` tradicional para determinar o status correspondente.

As fases tratadas no código são:

- `Vingadora`
- `WandaVision`
- `Feiticeira Escarlate`

Caso o valor não esteja previsto, o programa utiliza `default` e retorna `Fase desconhecida.`

### 2. MarvelSwitch

O programa aplica a versão moderna do `switch`, atribuindo diretamente uma mensagem à variável `status`.

As fases tratadas no código são:

- `Vingadora`
- `WandaVision`
- `Feiticeira Escarlate`
- `Civil War`

Caso a fase não seja reconhecida, o programa retorna `Fase não identificada no multiverso.`

---

## ▶️ Como Compilar e Executar

Para compilar a versão tradicional:

```bash
javac WandaSwitchAntigo.java
```

Para executar:

```bash
java WandaSwitchAntigo
```

Para compilar a versão moderna:

```bash
javac MarvelSwitch.java
```

Para executar:

```bash
java MarvelSwitch
```

### Observação sobre versão do Java

O arquivo `MarvelSwitch.java` usa `switch` como expressão com a sintaxe `case ->`, recurso disponível em versões mais novas do Java.

Se o ambiente estiver em **Java 11**, apenas o arquivo `WandaSwitchAntigo.java` compilará normalmente. Para compilar `MarvelSwitch.java`, é recomendado usar **Java 14 ou superior**.

---

## ✅ Principais Conceitos Utilizados

- declaração de variáveis
- estrutura condicional `switch`
- uso de `case`, `break` e `default`
- atribuição de valores com `switch` moderno
- comparação de sintaxes da linguagem
- exibição de resultados com `System.out.println`

---

## 💡 Boas Práticas Aplicadas

- nomes de classes claros e objetivos
- separação de exemplos em arquivos distintos
- código simples e apropriado para iniciantes
- indentação consistente
- uso de exemplos diretos para facilitar aprendizagem
- presença de `default` para tratar casos não previstos

---

## 🚀 Aplicação no Contexto Acadêmico

Esta atividade fortalece fundamentos importantes do início do curso, especialmente:

- raciocínio lógico
- uso de estruturas de decisão
- leitura e interpretação de fluxo condicional
- organização básica de código em Java
- comparação entre versões de sintaxe da linguagem

Essas habilidades servem como base para conteúdos mais avançados da graduação, como repetições, métodos, orientação a objetos e desenvolvimento de sistemas completos.

---

## 🧩 Conclusão

O projeto entrega os dois exemplos solicitados em Java, mantendo uma estrutura simples, organizada e adequada ao nível introdutório da disciplina.

A implementação prioriza clareza, legibilidade e foco didático, permitindo compreender a diferença entre o `switch` tradicional e o moderno de forma objetiva.

---

## 👨‍💻 Autor

Lucas Cota  
Estudante de Análise e Desenvolvimento de Sistemas  
Foco em Backend e Engenharia de Software
