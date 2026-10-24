# 📘 Integração Numérica 🧠


---

## 🎯 1. Tema e Objetivo

**Tema:** Integração Numérica — Fórmulas de Newton–Cotes e Quadratura de Gauss-Legendre.

**Objetivo:** Desenvolver um segundo cérebro com inteligência artificial, utilizando o Google NotebookLM e fontes acadêmicas confiáveis, para auxiliar estudantes de Engenharia na compreensão dos fundamentos da integração numérica, no estudo das fórmulas de quadratura, na análise dos métodos de Newton–Cotes e Gauss-Legendre e na resolução de problemas matemáticos.

O projeto propõe um ambiente de aprendizagem interativo no qual os estudantes possam formular perguntas, consultar referências acadêmicas, desenvolver o raciocínio matemático e resolver exercícios com orientação de um tutor baseado em inteligência artificial.

A proposta integra fundamentação teórica, análise de erros, aplicações computacionais e produção de materiais educativos, promovendo a aprendizagem autônoma e a utilização responsável da inteligência artificial no ensino universitário.

---

## 📚 2. Fontes Selecionadas e Justificativa

O notebook reúne oito fontes acadêmicas em diferentes formatos, incluindo livros, materiais universitários e vídeos educativos.

As fontes foram selecionadas considerando sua relevância matemática, fundamentação teórica, aplicabilidade à Engenharia e contribuição para a compreensão dos métodos de integração numérica.

### Fontes utilizadas

### 1. Livro: Cálculo Numérico

- **Autora:** Neide Maria Bertoldi Franco.
- **Instituição:** Universidade de São Paulo (USP) — Instituto de Ciências Matemáticas e de Computação (ICMC).
- **Formato:** Livro em PDF.
- **Conteúdo utilizado:** Capítulo 11 — Integração Numérica, incluindo fórmulas de Newton–Cotes, quadratura interpolatória, Gauss-Legendre e análise de erros.
- **Por que confio:** É um material acadêmico elaborado por uma pesquisadora vinculada à USP, com fundamentação matemática rigorosa, demonstrações e exercícios aplicados.

### 2. Livro: Explorations in Numerical Analysis

- **Autores:** James V. Lambers e Amber C. Sumner.
- **Origem acadêmica:** Material desenvolvido a partir de notas de aulas universitárias de Análise Numérica.
- **Formato:** Livro digital em PDF (`book_ena.pdf`).
- **Conteúdo utilizado:** Interpolação polinomial, integração numérica, análise de erros e implementação computacional.
- **Por que confio:** Apresenta uma abordagem que integra teoria matemática e prática computacional, desenvolvida para cursos universitários avançados.

### 3. Livro: Algoritmos Numéricos

- **Autor:** Frederico Ferreira Campos Filho.
- **Instituição:** Universidade Federal de Minas Gerais (UFMG).
- **Formato:** Livro em PDF.
- **Conteúdo utilizado:** Capítulo 5 — Integração Numérica, com regras de Newton–Cotes, quadratura de Gauss-Legendre e algoritmos computacionais.
- **Por que confio:** É uma obra acadêmica de autoria de um professor universitário, com explicações dos métodos e procedimentos algorítmicos para aplicações numéricas.

### 4. Livro: Principles and Procedures of Numerical Analysis

- **Autores:** Ferenc Szidarovszky e Sidney Yakowitz.
- **Instituições:** Eötvös Loránd University e University of Arizona.
- **Editora:** Plenum Press, 1978; edição digital Springer.
- **Formato:** Livro acadêmico em PDF.
- **Conteúdo utilizado:** Capítulo 3 — Diferenciação e Integração Numérica, incluindo quadratura interpolatória, fórmulas de Newton–Cotes e quadratura gaussiana.
- **Por que confio:** É uma referência acadêmica publicada por editora científica reconhecida, com tratamento teórico dos algoritmos, propriedades matemáticas e análise de convergência.

### 5. Livro: Numerical Methods and Methods of Approximation in Science and Engineering

- **Autor:** Karan S. Surana.
- **Instituição:** University of Kansas.
- **Editora:** CRC Press / Taylor & Francis.
- **Formato:** Livro acadêmico em PDF.
- **Conteúdo utilizado:** Métodos de integração numérica, aproximação matemática e aplicações em Ciências e Engenharia.
- **Por que confio:** É uma obra especializada em métodos numéricos aplicados, publicada por editora científica, que relaciona os fundamentos matemáticos à resolução de problemas de Engenharia.
### 6. Artigo Web: Cuadraturas de Gauss | Métodos Numéricos
- **Autor/Plataforma:** Jon Ramos — Métodos Numéricos.
- **Formato:** Artigo educacional disponível na web.
- **Conteúdo utilizado:** Fundamentos da quadratura gaussiana, polinômios ortogonais, determinação de nós e pesos, quadratura de Gauss-Legendre, análise de erros e comparação com Newton–Cotes.
- **Por que confio:** É um material didático especializado em Métodos Numéricos, que apresenta deduções matemáticas, fórmulas, tabelas de nós e pesos e exemplos resolvidos. Permite complementar os livros acadêmicos com explicações organizadas e aplicações práticas.
- **Link:** [https://metodosnumericos.jonramos.dev/es/articulos/integracion-gauss/]

---

## ⚙️ 3. Diretriz de Comportamento (Prompt do Notebook)

O NotebookLM foi personalizado para atuar como um **tutor acadêmico interativo de Integração Numérica**, destinado a estudantes de Engenharia.

Sua função é orientar a aprendizagem, desenvolver o raciocínio matemático e auxiliar na resolução de problemas, utilizando exclusivamente as fontes acadêmicas carregadas no notebook.

### Instruções de personalização

Você é um professor universitário especialista em Análise Numérica e Métodos Numéricos, com experiência no ensino de Engenharia.

Sua função é atuar como tutor acadêmico interativo de Integração Numérica, promovendo a aprendizagem autônoma, o raciocínio matemático e a resolução de problemas, utilizando **exclusivamente os documentos e materiais disponibilizados como fontes neste notebook**.

**Diretrizes pedagógicas:**

1. Explique exclusivamente o conteúdo solicitado pelo estudante, com base nas fontes disponíveis, sem abordar outros tópicos desnecessariamente.

2. Adote uma abordagem socrática e interativa. Faça perguntas orientadoras, uma de cada vez, aguarde a resposta do estudante e forneça feedback antes de avançar.

3. Apresente definições matemáticas rigorosas, fórmulas em LaTeX, demonstrações quando pertinentes, exemplos resolvidos e aplicações práticas de Engenharia.

4. Na resolução de exercícios, apresente os dados, as fórmulas utilizadas, os pontos de quadratura, os cálculos intermediários e a análise de erros, quando aplicável.

5. Identifique erros conceituais e de cálculo, explique suas causas e incentive o estudante a corrigir suas próprias respostas antes de apresentar a solução completa.

6. Proponha exercícios de dificuldade progressiva e incentive a comparação entre diferentes métodos quanto à precisão, ao erro e ao custo computacional.

**Regras obrigatórias sobre fontes e referências:**

7. Utilize exclusivamente os documentos, PDFs, artigos acadêmicos e vídeos carregados neste notebook. Não consulte fontes externas nem complemente as respostas com informações não fundamentadas nesses materiais.

8. Todas as respostas acadêmicas devem apresentar **citações verificáveis das fontes utilizadas**, posicionadas próximas às definições, fórmulas, teoremas, explicações e procedimentos correspondentes.

9. Sempre que possível, identifique o título do documento, capítulo, seção ou página correspondente. Para vídeos, indique o material e o trecho relevante, quando disponível.

10. Quando uma resposta utilizar informações de diferentes documentos, apresente as referências correspondentes a cada conteúdo abordado e adicione ao final das respostas com o numero das paginas.

11. Nunca invente referências bibliográficas, páginas, capítulos, citações, fórmulas ou informações que não estejam disponíveis nas fontes.

12. Quando uma pergunta não puder ser respondida com base nos materiais fornecidos, informe: **"Esta informação não está disponível nas fontes fornecidas neste notebook."**, ou apresente essa mensagem no idioma utilizado pelo estudante.

**Comunicação e aprendizagem:**

13. Responda preferencialmente no idioma utilizado pelo estudante, mantendo linguagem clara, objetiva, acadêmica e notação matemática adequada. Quando solicitado, utilize outro idioma.

14. Quando solicitado, produza resumos, guias de estudo, questionários, exercícios e materiais de revisão fundamentados exclusivamente nas fontes disponíveis.

15. Priorize a participação ativa do estudante. Durante atividades de aprendizagem guiada, não apresente imediatamente a solução completa. Quando o estudante solicitar explicitamente uma resolução integral, apresente-a de maneira detalhada e fundamentada nas fontes.

**REGRA FUNDAMENTAL:** Todas as explicações, definições, demonstrações, fórmulas, exemplos, exercícios e respostas acadêmicas devem ser fundamentados exclusivamente nas fontes fornecidas neste notebook e acompanhados de citações verificáveis. Caso não exista fundamento documental suficiente, informe a limitação sem inventar informações.

---

## 💬 4. Diálogos e Evidências com Citações

O notebook foi estruturado para investigar conceitos fundamentais da integração numérica por meio de perguntas acadêmicas e interações orientadas.

As respostas devem utilizar exclusivamente as fontes disponibilizadas e apresentar citações verificáveis, permitindo ao estudante consultar diretamente os materiais originais.

Para documentar o funcionamento da ferramenta, foram propostas cinco perguntas e uma atividade interativa. Cada teste deverá apresentar a resposta efetivamente obtida, as referências citadas e uma captura de tela.

### Pergunta 1 — O que é uma fórmula de quadratura?

**Resposta do NotebookLM:**  
Uma fórmula de quadratura é um procedimento matemático utilizado para aproximar o valor de uma integral definida por meio de uma soma ponderada de valores da função em pontos específicos, denominados nós de quadratura. Sua expressão geral é:
\[
\int_a^b \omega(x)f(x)\,dx
\approx \sum_{k=0}^{n} A_k f(x_k),
\]

em que \(x_k\) são os nós, \(A_k\) os pesos e \(\omega(x)\) a função peso. O notebook também destacou duas famílias principais: Newton–Cotes e quadratura gaussiana.

**Fonte citada:**  
Franco, Neide Maria Bertoldi. Cálculo Numérico. Capítulo 11, Seções 11.1–11.2, pp. 321–325; Seção 11.3, pp. 347–348.
Szidarovszky, Ferenc; Yakowitz, Sidney. Principles and Procedures of Numerical Analysis. Capítulo 3, Seção 3.2, p. 86.
Ramos, Jon. Cuadraturas de Gauss | Métodos Numéricos, seção “Idea general”.
book_ena.pdf. Capítulo 7, Seção 7.2, sobre fórmulas de quadratura interpolatória.

[📷 Ver Evidência 1_1](Evidencias/Pergunta1_1.png)
[📷 Ver Evidência 1_1](Evidencias/Pergunta1_2.png)

### Pergunta 2 — O que são as fórmulas de Newton–Cotes?

**Resposta do NotebookLM:**  
As fórmulas de Newton–Cotes constituem uma família de métodos de integração numérica fundamentados na interpolação polinomial. Sua principal característica é utilizar nós igualmente espaçados no intervalo de integração. A função é aproximada por um polinômio interpolador de Lagrange, cuja integração fornece uma fórmula de quadratura. Entre os principais exemplos estão as regras do trapézio, Simpson 1/3 e Simpson 3/8. O notebook também ressaltou que fórmulas de grau elevado podem apresentar instabilidade numérica, sendo frequentemente preferíveis regras compostas de grau baixo

**Fonte citada:**  
Franco, Neide Maria Bertoldi. Cálculo Numérico. Capítulo 11, Seções 11.1–11.2.2, pp. 321–338.
Szidarovszky, Ferenc; Yakowitz, Sidney. Principles and Procedures of Numerical Analysis. Capítulo 3, Seção 3.2, pp. 79–87.
book_ena.pdf. Capítulo 7, Seções 7.3–7.4, pp. 234–238.
algoritmos computacionales.pdf. Capítulo 5, Seção 5.1, pp. 212–215.
Surana, Karan S. Numerical Methods and Methods of Approximation in Science and Engineering. Capítulo 6, p. 276.
Garg, Harish. Gauss-Legendre Quadrature Rule | Numerical Linear Algebra. Vídeo educativo.

[📷 Ver Evidência 2_1](Evidencias/Pergunta2_1.png)
[📷 Ver Evidência 2_2](Evidencias/Pergunta2_2.png)

### Pergunta 3 — Qual é a diferença entre Newton–Cotes abertas e fechadas?

**Resposta do NotebookLM:**  
A diferença fundamental está na utilização dos extremos do intervalo de integração. As fórmulas fechadas incluem os pontos \(a\) e \(b\) como nós de avaliação, como ocorre nas regras do trapézio e de Simpson. Já as fórmulas abertas utilizam somente pontos interiores, como a regra do ponto médio. O notebook destacou que as fórmulas abertas podem ser úteis quando a função não está definida nos extremos do intervalo.

**Fonte citada:**  
Szidarovszky, Ferenc; Yakowitz, Sidney. Principles and Procedures of Numerical Analysis. Capítulo 3, Seção 3.2.1, pp. 80–81.
book_ena.pdf. Capítulo 7, Seções 7.2–7.3, pp. 234–235.
Franco, Neide Maria Bertoldi. Cálculo Numérico. Capítulo 11, Seção 11.2.1, p. 325; Capítulo 12, p. 338.

[📷 Ver Evidência 3_1](Evidencias/Pergunta3_1.png)
[📷 Ver Evidência 3_2](Evidencias/Pergunta3_2.png)

### Pergunta 4 — O que é a quadratura de Gauss-Legendre?

**Resposta do NotebookLM:**  
A quadratura de Gauss-Legendre é um método de integração numérica que seleciona adequadamente os nós e os pesos para maximizar o grau de exatidão da aproximação. Os nós correspondem às raízes dos polinômios de Legendre e, com \(n\) pontos, a fórmula integra exatamente polinômios de grau até \(2n-1\). Para intervalos diferentes de \([-1,1]\), utiliza-se uma transformação linear de variáveis.
\[
\int_{-1}^{1}f(x)\,dx
\approx \sum_{i=1}^{n}A_i f(x_i).
\]

**Fonte citada:**  
Franco, Neide Maria Bertoldi. Cálculo Numérico. Capítulo 11, Seção 11.3.1, p. 343; Seção 11.4.1, pp. 351–353.
algoritmos computacionales.pdf. Capítulo 5, Seção 5.2, pp. 229–236.
book_ena.pdf. Capítulo 6, Seção 6.2.3, p. 206; Capítulo 7, Seção 7.5, pp. 241–245.

[📷 Ver Evidência 4_1](Evidencias/Pergunta4_1.png)
[📷 Ver Evidência 4_2](Evidencias/Pergunta4_2.png)

### Pergunta 5 — Qual é a principal diferença entre Newton–Cotes e Gauss-Legendre?

**Resposta do NotebookLM:**  
A principal diferença está na escolha dos nós de integração e no grau de exatidão obtido. Nas fórmulas de Newton–Cotes, os nós são igualmente espaçados e previamente definidos. Na quadratura de Gauss-Legendre, os nós são escolhidos como raízes dos polinômios de Legendre, permitindo maior grau de exatidão para o mesmo número de avaliações da função. Com \(n\) nós, Gauss-Legendre alcança grau \(2n-1\), enquanto as fórmulas fechadas de Newton–Cotes apresentam grau \(n-1\) para \(n\) par e \(n\) para \(n\) ímpar. Assim, a quadratura gaussiana pode oferecer maior eficiência computacional em problemas adequados.

**Fontes citadas:**  
Szidarovszky, Ferenc; Yakowitz, Sidney. Principles and Procedures of Numerical Analysis. Capítulo 3, Seções 3.2.1–3.3, pp. 79–107.
algoritmos computacionales.pdf. Capítulo 5: Integração Numérica, Seções 5.1–5.3, pp. 212–245.
book_ena.pdf. Capítulo 7: Numerical Quadrature, Seções 7.2–7.5, pp. 233–245.
Ramos, Jon. Cuadraturas de Gauss | Métodos Numéricos. Seção “Idea general”.

[📷 Ver Evidência 5_1](Evidencias/Pergunta5_1.png)
[📷 Ver Evidência 5_2](Evidencias/Pergunta5_2.png)

---

## 🎨 5. Materiais Gerados no Estúdio

**🗺️ Mapa Mental — Integração Numérica**

[📷 Visualizar Mapa Mental](Materiales/Mapa_Mental.png)

**📊 Apresentação — Métodos de Integração Numérica**


[📄 Visualizar Apresentação](Materiales/Presentacao_Integración_Numérica.pdf)

**📘 Guia de Estudos — Integração Numérica**

[📖 Consultar Guia de Estudos](Materiales/guia_integracion_numerica.pdf)

**🎧 Resumo em Áudio — Integração Numérica**


[🎧 Ouvir Resumo em Áudio](Materiales/Por_qué_Gauss-Legendre_supera_a_Newton-Cotes.m4a)

---

## 🔗 6. Link do Notebook

[https://notebook.google.com/notebook/f1c9ba21-2f9f-4a1a-badf-ef51d1f5fe1a]



Um aspecto fundamental é a **rastreabilidade das informações**, assegurada por meio de citações verificáveis que permitem relacionar as respostas produzidas pelo tutor aos documentos e materiais utilizados no projeto.



