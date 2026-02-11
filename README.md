## Desafio - Ferramenta de Controle de Investimentos com Excel
Olá!</p>
Me chamo Sisley e vou detalhar um pouco sobre o primeiro Desafio do Bootcamp da Dio. Foi solicitada a criação de uma planilha para ajudar o usuário na simulação de investiments em fundos imoobiliários, aplicando os conceitos de Excel no desenvolvimento dessa ferramenta. A seguir, detalho como foi feito o passo a passo dessa ferramenta.</p>

## 📌 Objetivo
Aplicar os conceitos de Excel no desenvolvimento de uma ferramenta prática de simulação de investimentos em fundos imobiliários.</p>


## 🛠️ Como foi feito

1º Passo:

Definir as perguntas de negócio </p>
Por que isso está sendo feito? Resposta: Simular investimentos em fundos imobiliários. </p>
Quais informações eu preciso para fazer essas simulações? Resposta: Taxa de Rendimento Mensal, Por quantos Anos/Meses, Quanto investir por mês, Tipos de FII existentes.</p>
Quais informações terei como resultado dessas simulações? Resposta: Patrimônio acumulado no tempo estimado e Dividendos mensais.</p>
Quais perfis possíveis para esse investidor? Resposta: Moderado, Agressivo</p>
Além dessas informações, quais outras são necessárias para a ferramenta? Resposta: Salário, Sugestão de investimento (% com base no salário)</p>
É necessário uma demonstração gráfica? Resposta: Sim </p>
É necessário calcular Cenários? Resposta: Não é algo extremamente necessário, mas um detalhe a mais para que o usuário possa fazer projeções futuras de forma rápida e prática.</p>
2º Passo:</p>

Após definir perguntas de negócio, criar um fluxograma lógico para dar andamento no projeto.</p>

3º Passo:</p>

Separar em blocos as informações da ferramenta: </p>
- INFORMAÇÕES GERAIS</p>
- INVESTIMENTO</p>
- CENÁRIOS</p>
- PERFIL DO INVESTIDOR</p>

4º Passo: </p>

Definir quais informações aparecem em cada bloco: </p>
INFORMAÇÕES GERAIS: Salário, Rendimento Carteira, Sugestão de investimento.</p>
INVESTIMENTO: Quanto investir por mês; Por quantos anos; Taxa de rendimento mensal; Patrimônio acumulado; Dividendos mensais</p>
CENÁRIOS: Quanto em x anos; Montante; Dividendo </p>

5º Passo:</p>
Montar Layout da Tabela no Excel</p>
- Criei os blocos e adionei as informações correspondentes em cada bloco.</p>
- Para "CENÁRIOS", utilizei de fórmula [="Quanto em "&C20&" anos"] e de Validação de dados para montar uma lista de 1 a 30 anos. Assim, ao selecionar a quantidade de anos automaticamente é calculado o Montante e Dividendo.
- Para o Perfil do Investidor, extrai os tipos de perfis do site do banco Santander: https://www.santander.com.br/blog/tipos-de-fundos-imobiliarios-fiis. Sendo enumerados: </p>
1. FIIs de Tijolo (imóveis físicos como shoppings, galpões, escritórios, hospitais)  </p>
2. FIIs de Papel (títulos imobiliários — CRIs, LCIs)  </p>
3. Fundos de Fundos (FoFs)  </p>
4. FIIs Híbridos (misturam tijolo + papel)  </p>
5. Fiagros (ativos ligados ao agronegócio)  </p>
6. Fundos de Desenvolvimento (projetos em construção)  </p>

Aplicar fórmulas e testar seus resultados</p>
Unanimidade visual, ou seja, deixar sua ferramenta visualmente coerente e agradável (transmite confiança no trabalho).</p>

## 🤖 Ferramentas utilizadas
- Github</p>
- Excel</p>
- Chat GPT

## 📚 Aprendizados
Primeiramente: não conhecia muito sobre fundos de investimentos e através desse desse desafio pude conhecer e entender como funciona. Além disso, não tinha conhecimento sobre fundos imobiliários e seus tipos, já foi um incremento em meu conhecimento. Foi bem interessante explorar um pouco mais do Excel, ir além do básico e usar diferentes fórmulas e designs.</p>
