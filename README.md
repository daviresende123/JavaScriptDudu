# JavaScript - Conceitos Fundamentais

Este repositório contém exemplos práticos de conceitos básicos da linguagem JavaScript, organizados em diferentes arquivos para facilitar o aprendizado.

## 📁 Estrutura do Projeto

```
JavaScript/
├── README.md
├── variáveis.js
├── type-number.js
├── juntando-salas.js
├── lista-duas-dimensoes.js
├── atualizando-salas.js
└── dividindo-sala.js
```

## 📚 Conteúdo dos Arquivos

### 1. `variáveis.js` - Declaração de Variáveis
**Conceitos abordados:** `var`, `let`, `const`

Este arquivo demonstra as diferentes formas de declarar variáveis em JavaScript e suas características:

- **var**: Escopo de função, pode ser redeclarada
- **let**: Escopo de bloco, pode ser reatribuída
- **const**: Escopo de bloco, não pode ser reatribuída

**Exemplo prático:** Cálculo de área de formas geométricas usando estruturas condicionais.

```javascript
const forma = 'quadrado';
const altura = 5;
const comprimento = 7;
```

### 2. `type-number.js` - Tipo Numérico
**Conceitos abordados:** Operações matemáticas básicas

Demonstra como trabalhar com números em JavaScript:
- Declaração de variáveis numéricas
- Operações aritméticas (multiplicação)
- Saída de dados com `console.log()`

### 3. `juntando-salas.js` - Concatenação de Arrays
**Conceitos abordados:** Método `concat()`

Mostra como unir dois arrays em JavaScript:
- Criação de arrays
- Uso do método `concat()` para juntar arrays
- Aplicação prática: unindo listas de estudantes

```javascript
const salaJS = ["Dudu", "Vini", "Henrique"];
const salaPython = ["Dani", "Josy", "Rafa"];
const salasUni = salaJS.concat(salaPython);
```

### 4. `lista-duas-dimensoes.js` - Arrays Bidimensionais
**Conceitos abordados:** Arrays multidimensionais e template literals

Demonstra como trabalhar com arrays dentro de arrays:
- Criação de estruturas de dados bidimensionais
- Acesso a elementos específicos usando índices
- Formatação de saída com template literals (`` `${}` ``)

**Exemplo:** Relacionando alunos com suas respectivas médias.

### 5. `atualizando-salas.js` - Modificação de Arrays
**Conceitos abordados:** Método `splice()`

Ensina como modificar arrays existentes:
- Remoção de elementos
- Inserção de novos elementos
- Substituição de elementos em posições específicas

```javascript
nomes.splice(1, 2, "Rodrigo") // Remove 2 elementos a partir do índice 1 e insere "Rodrigo"
```

### 6. `dividindo-sala.js` - Divisão de Arrays
**Conceitos abordados:** Método `slice()`

Mostra como dividir um array em partes menores:
- Extração de porções de arrays
- Criação de subconjuntos sem modificar o array original
- Aplicação prática: dividindo turma em duas salas

## 🚀 Como Executar

Para executar qualquer um dos arquivos, use o Node.js:

```bash
node nome-do-arquivo.js
```

**Exemplos:**
```bash
node variáveis.js
node type-number.js
node juntando-salas.js
```

## 📖 Conceitos JavaScript Abordados

### Fundamentais
- ✅ Declaração de variáveis (`var`, `let`, `const`)
- ✅ Tipos de dados (Number, String, Array)
- ✅ Operadores aritméticos
- ✅ Estruturas condicionais (`if/else`)

### Arrays e Métodos
- ✅ `concat()` - Concatenação de arrays
- ✅ `splice()` - Modificação de arrays
- ✅ `slice()` - Extração de porções de arrays
- ✅ Arrays bidimensionais

### Saída de Dados
- ✅ `console.log()`
- ✅ Template literals (`` `${}` ``)

## 🎯 Objetivos de Aprendizado

Este repositório é ideal para:
- Estudantes iniciantes em JavaScript
- Revisão de conceitos fundamentais
- Exemplos práticos de manipulação de arrays
- Compreensão de diferentes tipos de declaração de variáveis

## 📝 Próximos Passos

Para expandir seus conhecimentos, considere estudar:
- Loops (`for`, `while`, `forEach`)
- Funções e arrow functions
- Objetos e métodos
- Manipulação do DOM
- Programação assíncrona

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Adicionar novos exemplos
- Melhorar a documentação existente
- Corrigir bugs ou otimizar código
- Sugerir novos conceitos para abordar

---

**Nota:** Este repositório é voltado para fins educacionais e demonstra conceitos básicos da linguagem JavaScript de forma prática e acessível