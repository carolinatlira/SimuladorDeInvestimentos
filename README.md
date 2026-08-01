# Simulador de Investimentos em Fundos Imobiliários (Excel)

## Descrição do Projeto

Este projeto consiste no desenvolvimento de uma planilha em Microsoft Excel para simulação de investimentos em Fundos de Investimento Imobiliário (FIIs). O objetivo é auxiliar investidores na análise de diferentes cenários de aplicação, permitindo estimar o patrimônio acumulado e os rendimentos futuros com base em informações fornecidas pelo usuário.

A ferramenta automatiza cálculos financeiros, proporcionando uma visão clara sobre o potencial crescimento do capital investido ao longo do tempo.

---

## Objetivos

* Simular investimentos em fundos imobiliários.
* Calcular o patrimônio acumulado ao longo dos anos.
* Estimar rendimentos futuros com base na taxa de retorno informada.
* Automatizar cálculos financeiros utilizando fórmulas do Excel.
* Facilitar a tomada de decisão do investidor por meio de projeções financeiras.

---

## Funcionalidades

A planilha permite que o usuário informe:

* Valor inicial do investimento;
* Valor dos aportes mensais;
* Prazo do investimento;
* Taxa de rendimento mensal.

Com base nesses dados, a ferramenta calcula automaticamente:

* Valor total investido;
* Patrimônio acumulado ao final do período;
* Estimativa de rendimentos mensais futuros.

---

## Fórmulas Utilizadas

### PROCV (Procura Vertical)

A função **PROCV** foi utilizada para buscar informações em tabelas auxiliares da planilha, permitindo recuperar dados automaticamente de acordo com critérios definidos pelo usuário.

**Sintaxe:**

```excel
=PROCV(valor_procurado; matriz_tabela; núm_índice_coluna; [procurar_intervalo])
```

### VF (Valor Futuro)

A função **VF** foi utilizada para calcular o valor futuro do investimento considerando aportes periódicos e uma taxa de rendimento constante.

**Sintaxe:**

```excel
=VF(taxa; nper; pgto; vp; tipo)
```

Essa função permite estimar quanto o patrimônio poderá valer ao final do período informado.

---

## Estrutura da Planilha

A planilha foi organizada em áreas específicas:

### Área de Entrada de Dados

Local onde o usuário informa:

* Valor inicial investido;
* Aporte mensal;
* Prazo do investimento;
* Taxa de rendimento.

### Área de Cálculos

Responsável por processar os dados informados utilizando as fórmulas financeiras implementadas.

### Área de Resultados

Exibe:

* Total investido;
* Patrimônio acumulado;
* Projeção de rendimentos mensais.

---

## Tecnologias Utilizadas

* Microsoft Excel
* Fórmulas Financeiras
* PROCV
* VF (Valor Futuro)

---

## Resultados Obtidos

A ferramenta permite realizar simulações rápidas e precisas, reduzindo erros manuais nos cálculos e fornecendo uma visão mais clara sobre o potencial de crescimento dos investimentos em fundos imobiliários.

Além disso, a planilha pode ser facilmente adaptada para diferentes perfis de investidores, tornando-se uma solução prática para planejamento financeiro.

---

## Aprendizados

Durante o desenvolvimento deste projeto foi possível:

* Aplicar conceitos de matemática financeira no Excel;
* Utilizar funções de busca para automatizar consultas de dados;
* Criar uma ferramenta prática voltada para investimentos;
* Melhorar a organização e documentação de projetos técnicos;
* Utilizar o GitHub para compartilhar projetos e documentação.

---
## Como utilizar
1. Comece preenchendo o valor do seu salário e uma sugestão de investimento será dada.
<br></br>
<img width="575" height="181" alt="Captura de tela 2026-08-01 174229" src="https://github.com/user-attachments/assets/44496a03-c603-46b1-9c96-28806934b37c" />
<br></br>
2. Preencha quanto pretende investir por mês como indicado na imagem abaixo.
<br></br>
<img width="575" height="127" alt="Captura de tela 2026-08-01 175028" src="https://github.com/user-attachments/assets/5d5d44e3-7687-4058-9d12-3d165d34ee06" />
<br></br>
3. Serão simulados alguns cenários, como mostrado na imagem a seguir.
<br></br>
<img width="577" height="120" alt="Captura de tela 2026-08-01 175203" src="https://github.com/user-attachments/assets/1c9ff86a-de39-4328-9f39-45aec3a9731d" />
<br></br>
4. Escolha o seu perfil: Conservador, Moderado ou Agressivo.
<br></br>
<img width="575" height="176" alt="Captura de tela 2026-08-01 175915" src="https://github.com/user-attachments/assets/bbdfd410-dc0a-4a09-b71a-67820a783313" />
<br></br>
5. Confira os percentuais sugeridos de investimento.
<br></br>
<img width="576" height="404" alt="Captura de tela 2026-08-01 180030" src="https://github.com/user-attachments/assets/e32aa623-546b-4c9e-973c-805ac3ddd4f6" />
<br></br>

## Conclusão

O desenvolvimento deste simulador permitiu consolidar conhecimentos em Excel e finanças, demonstrando como ferramentas simples podem ser utilizadas para apoiar a tomada de decisões de investimento. A automação dos cálculos proporciona maior agilidade, confiabilidade e facilidade de uso para investidores que desejam planejar seu futuro financeiro.

## Confira a ferramenta

[Simulador de Investimentos.xlsx](https://github.com/user-attachments/files/30623234/Simulador.de.Investimentos.xlsx)

