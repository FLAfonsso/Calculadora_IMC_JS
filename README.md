# Calculadora de IMC

Aplicação web desenvolvida com HTML, CSS e JavaScript para calcular o Índice de Massa Corporal (IMC) a partir do peso e da altura informados pelo usuário. Após o cálculo, a página apresenta o resultado e sua classificação, além de uma tabela de referência com as faixas de IMC.

## Funcionalidades

- **Cálculo de IMC:** calcula o índice usando o peso e a altura informados.
- **Aceita vírgula nos valores:** permite inserir números no formato comum em português, como `1,75` para altura e `70,5` para peso.
- **Classificação do resultado:** apresenta categorias como Magreza, Normal, Sobrepeso, Obesidade e Obesidade grave.
- **Tabela de referência:** exibe as faixas de IMC, suas classificações e os graus de obesidade correspondentes.
- **Indicação visual do resultado:** utiliza cores diferentes para destacar a classificação obtida.
- **Limpar campos:** permite apagar os valores preenchidos sem sair da calculadora.
- **Navegação entre formulário e resultado:** o botão “Voltar” retorna ao formulário para realizar outro cálculo.
- **Interface dinâmica:** a tabela de classificação é criada com JavaScript, e a área de resultado é exibida após o cálculo.

## Tecnologias utilizadas

- **HTML5:** estrutura e campos do formulário.
- **CSS3:** layout, cores, organização dos elementos e estilos para os resultados.
- **JavaScript:** validação básica dos campos, cálculo do IMC, classificação, manipulação do DOM e eventos.
- **Google Fonts — Lato:** tipografia utilizada na interface.

## Estrutura do projeto

```text
Calculadora_IMC_JS/
├── css/
│   └── styles.css
├── js/
│   └── scripts.js
├── index.html
└── README.md
```

## Como executar o projeto

O projeto utiliza HTML, CSS e JavaScript puros, sem necessidade de instalar dependências.

1. Clone o repositório:

   ```bash
   git clone https://github.com/FLAfonsso/Calculadora_IMC_JS.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd Calculadora_IMC_JS
   ```

3. Abra o arquivo `index.html` em um navegador moderno.

   Você também pode utilizar a extensão **Live Server** no Visual Studio Code para executar o projeto localmente.

## Como utilizar

1. Informe sua altura em metros, por exemplo, `1,75`.
2. Informe seu peso em quilogramas, por exemplo, `70,5`.
3. Clique em **Calcular**.
4. Consulte o valor do IMC, a classificação e a tabela de referência.
5. Clique em **Voltar** para retornar ao formulário e realizar outro cálculo. O botão **Limpar** apaga os valores digitados.

## Fórmula utilizada

O IMC é calculado dividindo o peso, em quilogramas, pelo quadrado da altura, em metros:

```text
IMC = peso (kg) / altura² (m)
```

Por exemplo, para uma pessoa com 70 kg e 1,75 m:

```text
IMC = 70 / (1,75 × 1,75) ≈ 22,9
```

## Objetivo do projeto

Projeto educacional criado para praticar lógica de programação e desenvolvimento front-end, com foco em manipulação do DOM, eventos, funções, validação de entradas e atualização dinâmica de conteúdo.

**Observação:** o IMC é uma medida de referência e, isoladamente, não determina o estado geral de saúde de uma pessoa.

## Autor

Desenvolvido por Pedro Afonso.
