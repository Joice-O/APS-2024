# EnergyDash

Aplicação acadêmica para acompanhar o consumo de energia elétrica e metas de redução. Desenvolvida no terceiro semestre da graduação em Ciência da Computação.

## Funcionalidades

- Entrada do consumo mensal em kWh.
- Definição de uma meta percentual de redução.
- Visualização de gráficos de consumo, metas e projeções.

## Tecnologias

Java, Swing, JFreeChart e projeto NetBeans com Apache Ant. A configuração atual utiliza Java 21.

## Como executar

1. Instale um JDK 21 e o Apache NetBeans.
2. Clone este repositório:
   ```bash
   git clone https://github.com/Joice-O/APS-2024.git
   ```
3. Abra no NetBeans a pasta `APS - EnergyDash/EnergyDash_final`.
4. Confira as bibliotecas nas propriedades do projeto. Os arquivos de configuração apontam para JARs na pasta Downloads da máquina de desenvolvimento, que não estão incluídos no repositório.
5. Configure as dependências JFreeChart/JCommon utilizadas pelos imports do projeto. O arquivo `nbproject/project.properties` registra referências a JFreeChart 1.0.19, JCommon 1.0.23 e outros JARs locais; ajuste os caminhos para o seu ambiente.
6. Execute a classe principal `View.Principal`.

Sem ajustar as bibliotecas, a compilação pode falhar. O projeto requer interface gráfica.

## Estrutura

- `src/MODEL`: dados de consumo.
- `src/CONTROLLER`: cálculos e avaliação de metas.
- `src/View`: telas Swing e gráficos.
- `src/ImageLogo`: imagem utilizada pela aplicação.
- `build.xml` e `nbproject`: configuração do projeto.

## Autoria

Projeto acadêmico publicado por [Joice Oliveira Jardim](https://github.com/Joice-O). O histórico de commits registra as contribuições dos participantes.

## Limitações

As projeções são cálculos didáticos do projeto. As bibliotecas ainda dependem de configuração manual e não há suíte de testes automatizados documentada.

