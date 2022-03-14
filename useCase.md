A Stack Analytics, oferece um ambiente onde é possível coletar e analisar dados com velocidade e confiança. Reduzindo uma carga de meses de trabalho para horas.

Vale ressaltar que nossa Stack  não insere código em sua aplicação. Provisionamos infraestrutura necessária para ingestão e processamento dos dados analíticos da sua aplicação. 

### Visão Geral
O **datalake** adiciona em uma stack a capacidade de provisionar recursos de engenharia de dados.

### Pré-requisitos
Para utlizar esse template você precisa utilizar o `cli` do `StackSpot` que você pode baixar [**aqui**](https://stackspot.com.br/).
- docker
- credenciais AWS


Aplicando o projeto base pode-se adicionar capacidades ao seu template base tais como: 

#### Gateway Data Flow

Através do plugin Gateway Data Flow, é disponibilizada uma infraestrutura para obter dados de uma aplicação e organizar em um data lake, aplicando processos de limpeza de dados e catálogo de dados.
É possível aplicar este plugin "n" vezes a uma stack env de datalake, afim de criar varios fluxos de dados. Ex.: (Marketing, Finances)


Ao fim do ciclo de desenvolvimento utilizando todas as capacidades que nossa Stack oferece podemos ter uma estrutura completa como ilustra imagem abaixo:

![Caso de Uso](https://raw.githubusercontent.com/stack-spot/skynet-analytics-stack/main/use-case.png "Caso de Uso")

Veja mais detalhes de cada plugin disponível através do menu lateral esquerdo onde vocês podem ver detalhes mais aprofundados de cada um, casos de uso e formas de uso. 
