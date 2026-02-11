## Desafio - Ferramenta de Controle de Investimentos com Excel
Olá!<br>
Me chamo Sisley e vou detalhar um pouco sobre o primeiro Desafio do Bootcamp da Dio. Foi solicitada a criação de uma planilha para ajudar o usuário na simulação de investiments em fundos imoobiliários, aplicando os conceitos de Excel no desenvolvimento dessa ferramenta. A seguir, detalho como foi feito o passo a passo dessa ferramenta.<br>

## 📌 Objetivo
Aplicar os conceitos de Excel no desenvolvimento de uma ferramenta prática de simulação de investimentos em fundos imobiliários.<br>

## 🛠️ Como foi feito

1º Passo:

Definir as perguntas de negócio <br>
Por que isso está sendo feito? Resposta: Simular investimentos em fundos imobiliários. <br>
Quais informações eu preciso para fazer essas simulações? Resposta: Taxa de Rendimento Mensal, Por quantos Anos/Meses, Quanto investir por mês, Tipos de FII existentes.<br>
Quais informações terei como resultado dessas simulações? Resposta: Patrimônio acumulado no tempo estimado e Dividendos mensais.<br>
Quais perfis possíveis para esse investidor? Resposta: Moderado, Agressivo<br>
Além dessas informações, quais outras são necessárias para a ferramenta? Resposta: Salário, Sugestão de investimento (% com base no salário)<br>
É necessário uma demonstração gráfica? Resposta: Sim <br>
É necessário calcular Cenários? Resposta: Não é algo extremamente necessário, mas um detalhe a mais para que o usuário possa fazer projeções futuras de forma rápida e prática.<br>

2º Passo:<br>

Após definir perguntas de negócio, criar um fluxograma lógico para dar andamento no projeto.<br>

3º Passo:<br>

Separar em blocos as informações da ferramenta:<br>
- INFORMAÇÕES GERAIS<br>
- INVESTIMENTO<br>
- CENÁRIOS<br>
- PERFIL DO INVESTIDOR<br>

4º Passo: <br>

Definir quais informações aparecem em cada bloco: <br>
INFORMAÇÕES GERAIS: Salário, Rendimento Carteira, Sugestão de investimento.<br>
INVESTIMENTO: Quanto investir por mês;Taxa de rendimento mensal<br>
CENÁRIOS: Quanto em x anos; Patrimônio acumulado; Dividendo <br>

5º Passo:<br>
Montar Layout da Tabela no Excel<br>
- Criei os blocos e adionei as informações correspondentes em cada bloco.<br>
- Para "CENÁRIOS", utilizei de fórmula [="Quanto em "&C20&" anos"] e de Validação de dados para montar uma lista de 1 a 30 anos. Assim, ao selecionar a quantidade de anos automaticamente é calculado o Montante e Dividendo. <br>
- Para o Perfil do Investidor:<br>
  - extrai os tipos de perfis do site do banco Santander: <br>
  https://www.santander.com.br/blog/tipos-de-fundos-imobiliarios-fiis. Sendo enumerados: <br>
  - Os FIIs ficaram dessa forma: <br>
    1. FIIs de Tijolo (imóveis físicos como shoppings, galpões, escritórios, hospitais) <br>
    2. FIIs de Papel (títulos imobiliários — CRIs, LCIs)  <br>
    3. Fundos de Fundos (FoFs)  <br>
    4. FIIs Híbridos (misturam tijolo + papel)  <br>
    5. Fiagros (ativos ligados ao agronegócio)  <br>
    6. Fundos de Desenvolvimento (projetos em construção)  <br>
  - Pedi sugestões ao Chat GPT sobre porcentagens de investimento para os perfis Conservador, Moderador e Agressivo <br>
  - Utilizei a fórmula de PROCX para que ao selecionar o perfil, já puxe automaticamente as porcentagens relacionadas ao FII e tipo de perfil.<br>

Aplicar fórmulas e testar seus resultados<br>
Unanimidade visual, ou seja, deixar sua ferramenta visualmente coerente e agradável (transmite confiança no trabalho).<br>

6º Finalização <br>
Aplicar ajustes finos para que a ferramenta fique 100%.

## 🤖 Ferramentas utilizadas
- Github<br>
- Excel<br>
- Chat GPT<br>

## 📚 Aprendizados
Primeiramente: não conhecia muito sobre fundos de investimentos e através desse desse desafio pude conhecer e entender como funciona. Além disso, não tinha conhecimento sobre fundos imobiliários e seus tipos, já foi um incremento em meu conhecimento. Foi bem interessante explorar um pouco mais do Excel, ir além do básico e usar diferentes fórmulas e designs.<br>
