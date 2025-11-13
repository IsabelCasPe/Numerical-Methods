<!-- HERO -->
# Arte & Ciência em Movimento — Matemática Viva 💎🧮✨
[![USP](https://img.shields.io/badge/USP-Dissertação-0A3D91?logo=academia&logoColor=white)](https://teses.usp.br/teses/disponiveis/3/3151/tde-20102010-122044/en.php)
[![arXiv](https://img.shields.io/badge/arXiv-2504.01969-B31B1B?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.01969)
![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-gold)
![Made with ❤](https://img.shields.io/badge/Made%20with-❤-ff69b4) 

**PT · EN · ES** · [Galeria](#galeria--gifs) · [Instalação](#instalação--installation--instalación) · [Licença MIT](#licença--license--licencia)

---
Cálculo Numérico para Engenharia e Ciências Exatas
├── 1. Zeros de Funções
│   ├── 1.1 Introdução
│   ├── 1.2 Isolamento das Raízes
│   ├── 1.3 Método da Bisseção
│   ├── 1.4 Método da Iteração Linear
│   └── 1.5 Método de Newton-Raphson
│
├── 2. Sistemas de Equações Lineares
│   ├── 2.1 Introdução
│   ├── 2.2 Métodos Iterativos
│   │   ├── Estudo da Convergência
│   │   ├── Método de Gauss-Jacobi
│   │   └── Método de Gauss-Seidel
│   └── 2.3 Métodos Diretos
│       ├── Método da Eliminação de Gauss
│       └── Inversão de Matrizes
│
├── 3. Ajuste de Curvas – Método dos Quadrados Mínimos
│   ├── 3.1 Caso Discreto (Linear e Não-linear)
│   └── 3.2 Análise do Resultado (Coeficiente de Correlação)
│
├── 4. Interpolação Polinomial
│   ├── 4.1 Existência e Unicidade do Polinômio Interpolador
│   ├── 4.2 Polinômio de Lagrange
│   ├── 4.3 Fórmula de Newton com Diferenças Divididas
│   ├── 4.4 Estudo do Erro da Interpolação
│   └── 4.5 Interpolação Inversa
│
├── 5. Integração Numérica
│   ├── 5.1 Introdução
│   ├── 5.2 Método de Newton-Cotes
│   │   ├── Regra dos Trapézios
│   │   └── Regra 1/3 de Simpson
│   └── Estudo do Erro
│
├── 6. Equações Diferenciais Ordinárias
│   ├── 6.1 Introdução
│   ├── 6.2 Métodos da Série de Taylor
│   ├── 6.3 Método de Euler
│   ├── 6.4 Métodos de Runge-Kutta
│   └── 6.5 Métodos de Passo Múltiplo
│
├── README.md
├── códigos/
│   ├── zeros_de_funcoes.py
│   ├── sistemas_lineares.py
│   ├── ajuste_de_curvas.py
│   ├── interpolacao_polinomial.py
│   ├── integracao_numerica.py
│   └── edos.py
│
├── exemplos/
│   └── exemplos_calculo_numerico.ipynb
│
└── notas/
    └── resumo_calculo_numerico.md
    # Numerical-Methods: Cálculo Numérico para Engenharia, Finanças e Ciências Exatas

🌟 **Bem-vindo ao Numerical-Methods!** 🌟  
Desenvolvido pela **Prof. Ana Isabel Castillo**, este repositório é um guia completo de **Cálculo Numérico**, projetado para estudantes e profissionais de **Engenharia**, **Finanças** e **Ciências Exatas**. Com uma abordagem prática e **sofisticada**, o curso combina teoria, códigos Python e exemplos aplicados para resolver problemas reais, como otimização de portfólios financeiros, simulação de sistemas dinâmicos e análise de dados experimentais. Explore os materiais, experimente os códigos e domine as ferramentas numéricas que impulsionam a inovação!

## 🎯 Sobre o Curso
O **Numerical-Methods** oferece uma jornada estruturada por 6 módulos, cobrindo os principais métodos numéricos com aplicações em:
- **Finanças:** Modelagem de derivativos, análise de risco e regressão para previsão de preços.
- **Engenharia:** Solução de equações diferenciais para sistemas mecânicos e elétricos.
- **Ciências Exatas:** Interpolação, integração e resolução de sistemas complexos.

Os materiais incluem slides (PDFs), códigos Python na pasta [codigos/](codigos/), exemplos interativos em [exemplos/](exemplos/) e resumos em [notas/](notas/). Todos os recursos são projetados para aprendizado prático e acessível, com gráficos claros e implementações testadas.

## 📚 Conteúdo do Curso
O curso está organizado em 6 módulos, detalhados abaixo:

- **1. Zeros de Funções**  🔗 [MNZerosDFuncao.pdf](MNZerosDFuncao.pdf)
  Encontre raízes de equações não-lineares com métodos robustos.  
  - 1.1 Introdução  
  - 1.2 Isolamento das Raízes  
  - 1.3 Método da Bisseção  
  - 1.4 Método da Iteração Linear  
  - 1.5 Método de Newton-Raphson  
  🔗 Código: [zeros_de_funcoes.py](codigos/zeros_de_funcoes.py)

- **2. Sistemas de Equações Lineares**   🔗 [MNSisEqLineares.pdf](MNSisEqLineares.pdf)
  Resolva sistemas lineares com métodos iterativos e diretos.  
  - 2.1 Introdução  
  - 2.2 Métodos Iterativos  
    - Estudo da Convergência  
    - Método de Gauss-Jacobi  
    - Método de Gauss-Seidel  
  - 2.3 Métodos Diretos  
    - Método da Eliminação de Gauss  
    - Inversão de Matrizes  
  🔗 Código: [sistemas_lineares.py](codigos/sistemas_lineares.py)

- **3. Ajuste de Curvas – Método dos Quadrados Mínimos**   🔗 [MNAjustedeCurvasMQM.pdf](MNAjustedeCurvasMQM.pdf)
  Ajuste modelos a dados experimentais com regressão linear e não-linear.  
  - 3.1 Caso Discreto (Linear e Não-linear)  
  - 3.2 Análise do Resultado (Coeficiente de Correlação)  
  🔗 Código: [ajuste_de_curvas.py](codigos/ajuste_de_curvas.py)

- **4. Interpolação Polinomial**  🔗 [MNInterpolacaoP.pdf](MNInterpolacaoP.pdf)
  Construa polinômios para interpolar dados com precisão.  
  - 4.1 Existência e Unicidade do Polinômio Interpolador  
  - 4.2 Polinômio de Lagrange  
  - 4.3 Fórmula de Newton com Diferenças Divididas  
  - 4.4 Estudo do Erro da Interpolação  
  - 4.5 Interpolação Inversa  
  🔗 Código: [interpolacao_polinomial.py](codigos/interpolacao_polinomial.py)

- **5. Integração Numérica**  🔗[MNIntegracaoNum.pdf](MNIntegracaoNum.pdf)
  Calcule integrais com métodos eficientes e analise erros.  
  - 5.1 Introdução  
  - 5.2 Método de Newton-Cotes  
    - Regra dos Trapézios  
    - Regra 1/3 de Simpson  
  - Estudo do Erro  
  🔗 Código: [integracao_numerica.py](codigos/integracao_numerica.py)

- **6. Equações Diferenciais Ordinárias**   🔗[MNEDOs.pdf](MNEDOs.pdf)
  Resolva EDOs com métodos numéricos, aplicados a sistemas dinâmicos.  
  - 6.1 Introdução  
  - 6.2 Métodos da Série de Taylor  
  - 6.3 Método de Euler  
  - 6.4 Métodos de Runge-Kutta  
  - 6.5 Métodos de Passo Múltiplo  
  🔗 Códigos: [edos.py](codigos/edos.py), [Rk4_predador_presa.ipynb](Rk4_predador_presa.ipynb)
## Dinâmica da Esfera Quântica com Quadrinhos - Math-Dynamics
Esfera 3D com 1156 quadrinhos em Spectral, rotação harmoniosa.  [Sphere Quanrica](esferaquanticadf.pdf) e [veja o vídeo](sphere_dynamics_quadrinhos.mp4). 
---
## Inspiration.
> "Nos algoritmos do infinito, a precisão numérica organiza o caos  @NumericalMethods, onde a arte do cálculo revela a ordem do universo." 🌌
>  Copyright © 2025 Prof. Ana Isabel C. 💙
---

## 🚀 Como Usar
- **Materiais:** Baixe os slides (PDFs) e o resumo em [notas/resumo_calculo_numerico.md](notas/resumo_calculo_numerico.md) para estudar offline.
- **Códigos Python:** Explore a pasta [codigos/](codigos/) com implementações testadas, como o [Rk4_predador_presa.ipynb](Rk4_predador_presa.ipynb), que simula o modelo predador-presa com animação interativa.
- **Exemplos Interativos:** Rode o notebook [exemplos/exemplos_calculo_numerico.ipynb](exemplos/exemplos_calculo_numerico.ipynb) em Jupyter Notebook ou Google Colab para testar os métodos.
- **Requisitos:** Instale as bibliotecas Python:
  ```bash
  pip install numpy matplotlib scipy


