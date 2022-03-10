Para times que têm a necessidade de coletar e analisar dados a Stack Analytics oferece velocidade e confiança neste processo.

Vale ressaltar que nossa Stack  não insere código em sua aplicação, provisionamos infraestrutura necessaria para ingestão e processamento dos dados analiticos da sua aplicação. 

Para começar a utilizar nossa stack é necessario a criação de uma stack env utilizando o template skynet-analytics-stack/datalake:

```
stk create env [datalake-env-name] --template skynet-analytics-stack/datalake

```

Aplicando o projeto base pode-se adicionar capacidades ao seu template base tais como: 

#### Gateway Data Flow

Imagine estar em um ambiente descentralizado voltado à micro serviços e que possua diversas comunicações entre eles através de filas de mensagens. Configurar e implementar o manuseio dessas filas será mais simples com o queue plugin. Assim como criar uma classe, abstraindo toda a complexidade para comunicação com sua fila AWS SQS.


Ao fim do ciclo de desenvolvimento utilizando todas as capacidades que nossa Stack oferece podemos ter uma estrutura completa como ilustra imagem abaixo:

![Caso de Uso](https://raw.githubusercontent.com/stack-spot/skynet-dotnet-stack/main/use-case.png "Caso de Uso")

Veja mais detalhes de cada plugin disponível através do menu lateral esquerdo onde vocês podem ver detalhes mais aprofundados de cada um, casos de uso é forma de uso. 
