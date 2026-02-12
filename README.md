# 🔢 Calculadora de Números Complexos

<div align="center">

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

Uma calculadora completa e intuitiva para operações com números complexos, desenvolvida em Python para a disciplina de Métodos de Matemática Aplicada.

[Características](#-características) •
[Instalação](#-instalação) •
[Uso](#-uso) •
[Documentação](#-documentação-matemática) •
[Exemplos](#-exemplos) •
[Contribuindo](#-contribuindo)

</div>

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Características](#-características)
- [Requisitos](#-requisitos)
- [Instalação](#-instalação)
- [Uso](#-uso)
- [Operações Suportadas](#-operações-suportadas)
- [Documentação Matemática](#-documentação-matemática)
- [Exemplos](#-exemplos)
- [Roadmap](#-roadmap)
- [Contribuindo](#-contribuindo)
- [Licença](#-licença)
- [Autores](#-autores)
- [Agradecimentos](#-agradecimentos)

---

## 🎯 Sobre o Projeto

A **Calculadora de Números Complexos** é uma ferramenta educacional desenvolvida como parte da disciplina de Métodos de Matemática Aplicada. O projeto visa facilitar o aprendizado e a realização de cálculos envolvendo números complexos, oferecendo uma interface intuitiva e resultados precisos.

### Motivação

Números complexos são fundamentais em diversas áreas da engenharia, física e matemática aplicada. Esta calculadora foi desenvolvida para:

- 📚 **Auxiliar no aprendizado** de conceitos matemáticos complexos
- ⚡ **Acelerar cálculos** em exercícios e trabalhos acadêmicos
- 🔍 **Verificar resultados** de operações manuais
- 🎓 **Demonstrar aplicações práticas** de programação em matemática

---

## ✨ Características

### Funcionalidades Principais

- ✅ **Operações Aritméticas Básicas**
  - Adição de números complexos
  - Subtração de números complexos
  - Multiplicação de números complexos
  - Divisão de números complexos

- ✅ **Operações Avançadas**
  - Conjugado de um número complexo
  - Módulo (valor absoluto)
  - Argumento (fase/ângulo)
  - Potenciação
  - Radiciação (raízes n-ésimas)
  - Forma exponencial (representação de Euler)

- ✅ **Conversões**
  - Forma retangular (a + bi)
  - Forma polar (r∠θ)
  - Forma exponencial (r·e^(iθ))
  - Forma trigonométrica (r(cos θ + i·sen θ))

- ✅ **Interface e Usabilidade**
  - Interface de linha de comando intuitiva
  - Entrada flexível de dados
  - Saída formatada e clara
  - Tratamento robusto de erros
  - Validação de entrada

### Diferenciais

- 🎨 **Código Limpo**: Seguindo boas práticas de programação Python
- 📖 **Bem Documentado**: Comentários claros e documentação completa
- 🧪 **Testável**: Estrutura que facilita a criação de testes
- 🔧 **Extensível**: Fácil adição de novas funcionalidades
- 🌍 **Educacional**: Ideal para estudantes de ciências exatas

---

## 💻 Requisitos

### Requisitos de Sistema

- **Python**: 3.7 ou superior
- **Sistema Operacional**: Windows, macOS, ou Linux
- **Memória RAM**: 512 MB (mínimo)
- **Espaço em Disco**: 50 MB

### Bibliotecas Python

O projeto utiliza apenas bibliotecas padrão do Python:

```python
import math      # Operações matemáticas
import cmath     # Operações com números complexos
import sys       # Operações do sistema
```

Não são necessárias instalações adicionais de pacotes externos.

---

## 🚀 Instalação

### Método 1: Clone do Repositório (Recomendado)

```bash
# Clone o repositório
git clone https://github.com/LeonardoPigatti/Calculadora-Numeros-Complexos.git

# Entre no diretório do projeto
cd Calculadora-Numeros-Complexos

# Execute a calculadora
python calculadora_numeros_complexos_mma_.py
```

### Método 2: Download Direto

1. Acesse a página do projeto: [Calculadora-Numeros-Complexos](https://github.com/LeonardoPigatti/Calculadora-Numeros-Complexos)
2. Clique em **Code** → **Download ZIP**
3. Extraia o arquivo ZIP
4. Navegue até a pasta extraída
5. Execute o arquivo Python:

```bash
python calculadora_numeros_complexos_mma_.py
```

### Verificação da Instalação

Para verificar se o Python está instalado corretamente:

```bash
python --version
```

Ou no Windows:

```bash
py --version
```

---

## 📖 Uso

### Execução Básica

```bash
python calculadora_numeros_complexos_mma_.py
```

### Entrada de Números Complexos

A calculadora aceita números complexos em diversos formatos:

```
Formato retangular:
  3+4j
  3+4i
  -2-5j
  0+1j

Formato com espaços:
  3 + 4j
  -2 - 5i

Apenas parte imaginária:
  4j
  -3i

Apenas parte real:
  5
  -7
```

### Fluxo de Uso

1. **Inicie o programa**
2. **Escolha a operação** desejada no menu
3. **Insira os números complexos** quando solicitado
4. **Visualize o resultado** formatado
5. **Continue ou encerre** conforme necessário

### Exemplo de Sessão

```
===========================================
  CALCULADORA DE NÚMEROS COMPLEXOS
===========================================

Escolha a operação:
1. Adição
2. Subtração
3. Multiplicação
4. Divisão
5. Conjugado
6. Módulo
7. Argumento
8. Forma Polar
9. Potenciação
0. Sair

Opção: 1

Digite o primeiro número complexo: 3+4j
Digite o segundo número complexo: 1-2j

Resultado:
(3+4j) + (1-2j) = (4+2j)

Forma retangular: 4 + 2i
Forma polar: 4.472∠26.57°
```

---

## 🔧 Operações Suportadas

### 1. Adição

**Fórmula**: `(a + bi) + (c + di) = (a + c) + (b + d)i`

**Exemplo**:
```
(3 + 4i) + (1 - 2i) = 4 + 2i
```

### 2. Subtração

**Fórmula**: `(a + bi) - (c + di) = (a - c) + (b - d)i`

**Exemplo**:
```
(5 + 3i) - (2 + 1i) = 3 + 2i
```

### 3. Multiplicação

**Fórmula**: `(a + bi) × (c + di) = (ac - bd) + (ad + bc)i`

**Exemplo**:
```
(3 + 2i) × (1 + 4i) = -5 + 14i
```

### 4. Divisão

**Fórmula**: `(a + bi) ÷ (c + di) = [(ac + bd) + (bc - ad)i] / (c² + d²)`

**Exemplo**:
```
(4 + 2i) ÷ (1 + 1i) = 3 - 1i
```

### 5. Conjugado

**Fórmula**: `conj(a + bi) = a - bi`

**Exemplo**:
```
conj(3 + 4i) = 3 - 4i
```

### 6. Módulo (Valor Absoluto)

**Fórmula**: `|a + bi| = √(a² + b²)`

**Exemplo**:
```
|3 + 4i| = 5
```

### 7. Argumento (Fase)

**Fórmula**: `arg(a + bi) = arctan(b/a)`

**Exemplo**:
```
arg(1 + 1i) = 45° ou π/4 rad
```

### 8. Forma Polar

**Conversão**: `a + bi = r(cos θ + i·sen θ)` onde:
- `r = |a + bi|`
- `θ = arg(a + bi)`

**Exemplo**:
```
3 + 4i = 5∠53.13°
```

### 9. Potenciação

**Teorema de De Moivre**: `[r(cos θ + i·sen θ)]ⁿ = rⁿ(cos nθ + i·sen nθ)`

**Exemplo**:
```
(1 + i)² = 2i
```

### 10. Radiciação

**Fórmula**: As n raízes n-ésimas de `z = r∠θ` são:

```
z_k = ⁿ√r · ∠[(θ + 2πk)/n], k = 0, 1, ..., n-1
```

**Exemplo**: Raízes cúbicas de 8
```
∛8 = {2, -1+√3i, -1-√3i}
```

---

## 📚 Documentação Matemática

### Propriedades dos Números Complexos

#### Propriedade Comutativa
```
z₁ + z₂ = z₂ + z₁
z₁ × z₂ = z₂ × z₁
```

#### Propriedade Associativa
```
(z₁ + z₂) + z₃ = z₁ + (z₂ + z₃)
(z₁ × z₂) × z₃ = z₁ × (z₂ × z₃)
```

#### Propriedade Distributiva
```
z₁ × (z₂ + z₃) = z₁ × z₂ + z₁ × z₃
```

#### Elemento Neutro
```
z + 0 = z
z × 1 = z
```

#### Elemento Inverso
```
z + (-z) = 0
z × (1/z) = 1, se z ≠ 0
```

### Identidades Importantes

#### Conjugado
```
conj(z₁ + z₂) = conj(z₁) + conj(z₂)
conj(z₁ × z₂) = conj(z₁) × conj(z₂)
conj(conj(z)) = z
z × conj(z) = |z|²
```

#### Módulo
```
|z₁ × z₂| = |z₁| × |z₂|
|z₁/z₂| = |z₁|/|z₂|
|z₁ + z₂| ≤ |z₁| + |z₂| (Desigualdade triangular)
```

### Fórmula de Euler

Uma das mais belas equações da matemática:

```
e^(iθ) = cos(θ) + i·sen(θ)
```

Casos especiais:
```
e^(iπ) + 1 = 0  (Identidade de Euler)
e^(i·π/2) = i
e^(i·2π) = 1
```

---

## 💡 Exemplos

### Exemplo 1: Cálculo de Impedância em Circuitos

```python
# Impedâncias em série
Z1 = 4 + 3j  # Ω
Z2 = 2 - 5j  # Ω

# Impedância total
Z_total = Z1 + Z2
# Resultado: (6 - 2j) Ω
```

### Exemplo 2: Análise de Sinais

```python
# Sinal complexo
s = 3 + 4j

# Módulo (amplitude)
amplitude = abs(s)  # 5

# Fase (ângulo)
fase = cmath.phase(s)  # 0.927 rad ≈ 53.13°
```

### Exemplo 3: Raízes de Equações

```python
# Resolver: x² + 4 = 0
# Raízes: x = ±2i

raiz1 = 2j
raiz2 = -2j

# Verificação
print(raiz1**2 + 4)  # Aproximadamente 0
```

### Exemplo 4: Transformações Geométricas

```python
# Rotação de 90° no plano complexo
z = 3 + 4j
rotacao = z * 1j  # Multiplica por i

# Resultado: -4 + 3j (rotação anti-horária de 90°)
```

### Exemplo 5: Aplicação em Física Quântica

```python
# Estado quântico
psi = (1 + 1j) / cmath.sqrt(2)

# Probabilidade
probabilidade = abs(psi)**2  # 1.0 (normalizado)
```

---

### Fluxograma

```
┌─────────────────────┐
│   Iniciar Programa  │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Exibir Menu        │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Escolher Operação  │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Validar Entrada    │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Executar Operação  │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Exibir Resultado   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Continuar/Sair?    │
└──────────┬──────────┘
           │
           └──────► Volta ao Menu ou Encerra
```

---

## 🧪 Testes

### Executando Testes

```bash
# Executar todos os testes
python -m pytest tests/

# Executar testes específicos
python -m pytest tests/test_operacoes_basicas.py

# Executar com cobertura
python -m pytest --cov=calculadora_numeros_complexos_mma_ tests/
```

## 🗺️ Roadmap

### Versão 1.0 (Atual)
- [x] Operações básicas (adição, subtração, multiplicação, divisão)
- [x] Conjugado e módulo
- [x] Conversão retangular ↔ polar
- [x] Interface de linha de comando

### Versão 1.5 (Planejada)
- [ ] Interface gráfica (GUI) com Tkinter
- [ ] Histórico de cálculos
- [ ] Exportação de resultados para arquivo
- [ ] Modo de precisão arbitrária

### Versão 2.0 (Futura)
- [ ] Plotagem gráfica no plano complexo
- [ ] Calculadora de matrizes complexas
- [ ] Suporte a funções complexas (exp, log, sin, cos)
- [ ] API REST para integração

### Versão 3.0 (Visão)
- [ ] Aplicativo mobile (Android/iOS)
- [ ] Machine Learning para sugestão de operações
- [ ] Integração com Wolfram Alpha
- [ ] Modo interativo tipo REPL

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

```
MIT License

Copyright (c) 2024 Leonardo Pigatti

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 👥 Autores

### Leonardo Pigatti
- GitHub: [@LeonardoPigatti](https://github.com/LeonardoPigatti)
- Estudante de Métodos de Matemática Aplicada


## 🙏 Agradecimentos

### Inspirações e Referências

- **Professor(a) Everton de Toledo Hanser**: Pela orientação e conhecimento compartilhado
- **Colegas de Classe**: Pelas discussões e feedback
- **Comunidade Python**: Pela linguagem incrível e recursos disponíveis

### Bibliotecas e Ferramentas

- [Python](https://www.python.org/) - Linguagem de programação
- [cmath](https://docs.python.org/3/library/cmath.html) - Biblioteca de números complexos
- [math](https://docs.python.org/3/library/math.html) - Biblioteca matemática

### Recursos Educacionais

- 📘 [Wikipedia - Complex Number](https://en.wikipedia.org/wiki/Complex_number)
- 📗 "Complex Variables and Applications" - Brown & Churchill
- 📙 Khan Academy - Complex Numbers
- 📕 MIT OpenCourseWare - Mathematics

---

## 📞 Contato e Suporte

### Reportar Problemas

Encontrou um bug ou tem uma sugestão?

1. Verifique se já não existe uma [issue aberta](https://github.com/LeonardoPigatti/Calculadora-Numeros-Complexos/issues)
2. Se não, [abra uma nova issue](https://github.com/LeonardoPigatti/Calculadora-Numeros-Complexos/issues/new)
3. Descreva o problema ou sugestão detalhadamente

### Perguntas Frequentes (FAQ)

**P: Posso usar este projeto comercialmente?**  
R: Sim! O projeto está sob licença MIT, que permite uso comercial.

**P: Como posso adicionar novas operações?**  
R: Veja a seção de [Contribuindo](#-contribuindo) e a documentação da arquitetura.

**P: O projeto funciona em Python 2?**  
R: Não, é necessário Python 3.7 ou superior.

**P: Posso usar em trabalhos acadêmicos?**  
R: Sim! Mas lembre-se de dar os devidos créditos.

---

## 📊 Estatísticas do Projeto

![GitHub Stars](https://img.shields.io/github/stars/LeonardoPigatti/Calculadora-Numeros-Complexos?style=social)
![GitHub Forks](https://img.shields.io/github/forks/LeonardoPigatti/Calculadora-Numeros-Complexos?style=social)
![GitHub Issues](https://img.shields.io/github/issues/LeonardoPigatti/Calculadora-Numeros-Complexos)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/LeonardoPigatti/Calculadora-Numeros-Complexos)

---

## 🌟 Se Você Achou Útil

Se este projeto te ajudou de alguma forma:

- ⭐ Dê uma estrela no GitHub
- 🔄 Compartilhe com seus colegas
- 🐛 Reporte bugs e sugira melhorias
- 🤝 Contribua com código

---

<div align="center">

### Feito com ❤️ e ☕ por Leonardo Pigatti

**[⬆ Voltar ao topo](#-calculadora-de-números-complexos)**

---

*"A matemática é a linguagem com a qual Deus escreveu o universo."* - Galileu Galilei

</div>
