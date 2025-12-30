# **FERRAMENTA DE CONTROLE DE INVESTIMENTOS NO EXCEL (DIO)**
![Logo](<Arquivos de imagens/logo-site-dux-300x169.png>)
## Intuito de calcular os retornos financeiros em determinados períodos de tempo, baseado em fundos de investimentos imobiliários (FIIs).📈
## **Índice**
-  <a href="#Para quem serve?">Para quem serve esta ferramenta?</a>
- <a href="#Fórmulas utilizadas">Fórmulas utilizadas no Excel para automatização dos informes na planilha.</a>
-  <a href="#Como utilizar">Como utilizar a ferramenta.</a>
- <a href="#Conclusão/referências">Conclusão/referências.</a>
## **Para quem serve?**
Voltado para quem deseja investir em fundos imobiliários(**FII**). 
### categorias específicas listadas na ferramenta:
![Print excel](<Arquivos de imagens/Captura de tela 2025-12-28 212336-2.png>)
1. Em papel.
2. Em tijolo.
3. Em HÍbridos (diferentes tipos de ativos no setor imobiliário).

4. Fofs (fundos imobiliários que não investem diretamente em imóveis físicos, mas sim em cotas de outros fundos imobiliários).
5. Desenvolvimento.
6. Hotelarias.

## **Fórmulas utilizadas**
Para devida automatização e facilidade no uso da planilha, foi aplicado tanto as fórmulas mais simples do Excel (Multiplicação, soma, subtração) quanto as mais elaboradas (=VF-valor futuro, =PROCV-procular na coluna vertical, =CONCATENAR-agrupa várias cadeias de texto em uma única sequência).
## **COMO UTILIZAR A FERRAMENTA**
### Há no total 6 módulos na planilha, para estar realizando as projeções de investimentos. Seguindo a coluna de "Configurações", posterior a de "investimentos mensais", passando pela simulação de "cenários" e etc. Listarei uma por uma para explicar a devida funcionalidade de cada um desses módulos.
**1.** Configurações ![alt text](<Arquivos de imagens/Captura de tela 2025-12-29 214700.png>)
- O primeiro demonstra as configurações iniciais necessárias para que o restante da planilha funcione corretamente. Nela contém 3 categorias:
1. **Salário** = Serve justamente para calcular o valor principal aplicado em toda a planilha, podendo ser o salário atual que ganha ou o qual desejar.
2. **Rendimento carteira** = Diz respeito a taxa de rendimento mensal em FIIs (0,5% a 1% dependendo da instituição e carteira em que for investir).
3. **Sugestão de investimento** = Serve justamente para indicar qual valor ideal para investir mensalmente, com base em um salário líquido (20%).

**Obs.:** A linha que está grifada em um tom mais escuro, não deve ser modificada, para evitar que ocorra erros de cálculos. Tão somente modificar, caso tenha conhecimentos em fórmulas. 

**Atenção!⚠️** Este mesmo princípio aplica-se para os demais módulos inseridos na planilha.

**2.** Investimentos mensais
![alt text](<Arquivos de imagens/Captura de tela 2025-12-29 220746.png>)
 - O segundo apresenta cálculos baseados no percentual investido mensalmente, referindo-se aos "20%" do salário utilizado para investimento e indicado no primeiro módulo. As perguntas formuladas ajudam na compreensão dos cálculos, deixando a planilha mais intuitiva.
 1. **Quanto investir por mês?** Valor referencial da simulação desejável.

 2. **Por quantos anos?** Tempo que poderá determinar para identificar os ganhos futuros.
 3. **Taxa rendimento mensal?** Diz respeito a taxa de rendimento mensal em FIIs (0,5% a 1% dependendo da instituição e carteira em que for investir).
 4. **Patrimônio acumulado?** Expressa um valor determinado, de acordo com as projeções em "anos" que executar.
 5. **Dividendos mensais?** Retorno que irá obter de renda passiva, após investir por determinado período de tempo.

 **3.** Cenários
 ![alt text](<Captura de tela 2025-12-29 224848.png>)
 - Este módulo envolve mais parâmetros, no que concerne os dividendos ganhos, renda passiva, mensalmente e após determinado período de tempo investindo. Apresenta o valor investido de 2 anos à 30 anos e seus possíveis ganhos.

 **Atenção!⚠️** Vale ressaltar que essas projeções tratam-se de valores aproximados, pondendo variar conforme a época, inflação, dentre outras situações que podem influenciar nestes indicadores.

#### **4.** Perfil de investidor
 ![alt text](<Arquivos de imagens/Captura de tela 2025-12-29 230225.png>)
- Uma tabela exclusiva para acionar qual o perfil de cada investidor, seja ele conservador, moderado e agressivo (arrojado). Na parte direita, poderá ser selecionado o filtro, para que altere entre os perfis e na linha abaixo, poderá ser aplicado um valor exclusivo e que coincidirá com a planilha, a qual demonstrarei na sequência.

**5.** Tipos de carteira de investimentos (FII)
![alt text](<Arquivos de imagens/Captura de tela 2025-12-29 231243.png>)
- A base detalhada dos tipos mais comuns de fundos imobiliários mais investidos, o percentual sugerido e valores repartidos entre os tipos de investimentos. Foi aplicado uma planilha à parte, para que houvesse formatações automatizadas neste módulo. Na sequência mostrarei brevemente do que se trata.

**5.1.** 2ª planilha "formulações"
![alt text](<Arquivos de imagens/Captura de tela 2025-12-29 232521.png>)
- Nesta planilha está configurado e concatenado, os tipos de FIIs juntamento com os perfis de investimentos. É importante que nesta planilha também não haja alterações, exceto na coluna de "Percentual % que poderá ser alterado dependo do perfil do investidor e risco assumido conforme investimento aplicado em cada tipo de FII.

**6.** Gráfico em Pizza
![alt text](<Arquivos de imagens/Captura de tela 2025-12-29 233236.png>)
- Neste último módulo da planilha, foi acrescentado um gráfico, meramente informativo, que gera informações de forma automática de acordo com os dados que foram inseridos no módulo 4 e 5, distribuirá os indicadores após alterar o perfil de investidor.

## **Conclusão/referências**

Agradeço à instituição Santander e plataforma DIO, por terem feito esta colaboração, e por estarem ajudando diversos alunos, incluindo-me, em suas jornadas profissionais!.

https://www.dio.me 

https://github.com/digitalinnovationone/github-quickstart.git

https://github.com/digitalinnovationone/github-quickstart/commits?author=felipeAguiarCode
