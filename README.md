# Repositório OSCAL (EM CONSTRUÇÃO)

Repositório direcionado para o uso dos modelos OSCAL (NIST) em língua portuguesa, sua adoção e possíveis extensões.

## O que é OSCAL

OSCAL significa Open Security Controls Assessment Language, e é constituído de 7 modelos de representação de informações de conformidade em sistemas de informação.
Os modelos podem ser escritos em JSON, XML e YAML. Seu objetivo é formar descrições interpretáveis por máquina, mas que podem gerar documentos que são consumidos por humanos, em relatórios, dashboards e outras formas de representação gráfica.

**Catálogo**: O modelo descreve um catálogo de controles, como CIS Controls e NIST 800-53, porém qualquer conjunto de controles pode ser definido em um catálogo.


**Perfil**: O perfil é utilizado para selecionar controles de um ou mais catálogos a serem implantados em um sistema. Por exemplo, sistemas críticos podem ter uma seleção de controles mais abrangentes, enquanto sistemas menos críticos podem ter uma perfil com menos controles.


**Definição de Componentes**: A definição de componentes serve para formar um inventário de componentes de um mais sistemas.


**Plano de Segurança do Sistema** (SSP): pode ser considerado o modelo mais imporante, é onde o sistema é descrito e como os controles são aplicados.


**Plano de Avaliação**: O objetivo do Plano de Avaliação é planejar e documentar a execução da avaliação dos controles de segurança de um sistema


**Resultados da Avaliação**: O Resultado da Avaliação documenta as constatações obtidas durante a execução do Plano de Avaliação. Ele registra as evidências coletadas, os métodos aplicados, as observações realizadas e a conclusão sobre a implementação e a eficácia dos controles avaliados.


**Plano de Ação e marcos (POA&M)**: o Plano de Ação e Marcos (POA&M) documenta as deficiências identificadas durante a avaliação, as ações corretivas planejadas, os responsáveis, os prazos e o acompanhamento da implementação dessas ações até a sua conclusão.

