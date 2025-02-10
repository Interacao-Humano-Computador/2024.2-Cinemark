## Artefato: Árvores de Tarefas Concorrentes

## Introdução  

A verificação desempenha um papel fundamental no desenvolvimento de um projeto, pois é nessa etapa que os artefatos criados são analisados para assegurar que atendam aos requisitos especificados. Diante disso, este documento detalha o planejamento da verificação dos artefatos desenvolvidos pelo [Grupo 4](https://github.com/Interacao-Humano-Computador/2024.2-Cinemark) pare o Artefato Árvorres de Tarefas Concorrentes.

## Objetivos  

Este documento tem como finalidade verificar o artefato Árvorres de Tarefas Concorrentes pelo [Grupo 4](https://github.com/Interacao-Humano-Computador/2024.2-Cinemark) estão em conformidade com os itens e padrões exigidos.  

## Metodologia  

A abordagem adotada para essa verificação é a inspeção. Essa técnica, criada por Fagan na IBM em 1976 para a revisão de códigos de software, consiste em uma análise formal dos artefatos com o objetivo de identificar possíveis defeitos. O processo é conduzido por meio de uma checklist contendo os erros mais recorrentes, que serão detectados, analisados e categorizados. É importante destacar que a leitura do artefato não deve ser realizada pelo próprio autor. Ao final da verificação, será gerado um gráfico apresentando os resultados obtidos.

### Participantes

Os responsáveis pelas verificações são os membros listados na tabela a seguir.

## Tabela relação integrante e verificação

| Integrante                                    | Atividade     |
| --------------------------------------------  | ------------- |
| [Ana Joyce](https://github.com/anajoyceamorim)  | Verificação do Artefato Árvores de Tarefas Concorrentes|

## Os artefatos alvos dessa verificação são:

- [**Árvores de Tarefas Concorrentes**]()

### Cronograma

A verificação foi realizada no dia 10/02/2025. A tabela 1 a seguir, apresenta o cronograma das atividades executadas.

<center>

**Tabela 1** - Cronograma das Atividades.

| Data       | Descrição                                         | Responsável                                                   |
| ---------- | ------------------------------------------------------------------------- | --------------------------------------------------------- |
| 10/02/2025 | Árvorres de Tarefas Concorrentes |  [Ana Joyce](https://github.com/anajoyceamorim)                               |

_Fonte: [Ana Joyce](https://github.com/anajoyceamorim), 2025._

</center>

## Checklists  

As checklists foram elaboradas com base nos padrões esperados para cada artefato, nas principais etapas envolvidas em sua construção e nas diretrizes de análise propostas por Simone e Silva<a id=anchor_1 href="#REF1"><sup>1</sup></a>.  

Para uma melhor organização do processo de verificação, as checklists foram divididas em 2 categorias, sendo uma delas de caráter geral, aplicável a todas as etapas. As verificações adotadas foram: uma geral e específicas para cada artefato do projeto. A tabela 2 e 3 apresentam todos os itens da verificação.

A verificação da entrega é necessária porque garante que o projeto atenda aos requisitos descritos no plano de ensino da disciplina.

<center>

**Tabela 2** - Itens da Verificação.

| Item | Descrição                                                     | Exemplo                                                   |     Fonte              | Staus                        |
| ---- | ------------------------------------------------------------- | --------------------------------------------------------- | ---------------------- |----------------------------- |
| 1    |  O CTT possui 4 tipos de tarefas (tarefas do usuário, do sistema, iterativas e abstratas)?   | Tarefas do usuário, são realizadas fora do sistema, tarefas do sistema, quando o sistema realiza um processamento sem interagir com o usuário, tarefas iterativas onde ocorre diálogos usuário-sistema e tarefas abstratas que não são tarefas em si, mas uma representação de uma composição de tarefas que auxilie a decomposição.  |  [Página: 173, Capítulo 8. Organização do Espaço de Problema. Livro: SIMONE DINIZ JUNQUEIRO BARBOSA, BRUNO SANTANA DA SILVA, Interacão Humano-Computador, 1a. Edicão, Editora Campus, 2010. Publicado em: 03/05/2021.  ](https://unbbr-my.sharepoint.com/:w:/g/personal/211031566_aluno_unb_br/EdnWkv3yVpdLvBBAIXIzJpcBq79O_jyvZxCTTYXWYIoAUQ?e=sgQot8)  |  sim   |
| 2    |  O CTT representa relações entre as tarefas?    |  O CTT permite representar diversas relações entre as tarefas como por exemplo de ativação e tarefas concorrentes.   |  [Página: 173, Capítulo 8. Organização do Espaço de Problema. Livro: SIMONE DINIZ JUNQUEIRO BARBOSA, BRUNO SANTANA DA SILVA, Interacão Humano-Computador, 1a. Edicão, Editora Campus, 2010. Publicado em: 03/05/2021.  ](https://unbbr-my.sharepoint.com/:w:/g/personal/211031566_aluno_unb_br/EdnWkv3yVpdLvBBAIXIzJpcBq79O_jyvZxCTTYXWYIoAUQ?e=sgQot8)  |  sim   |
| 3   |  As relações do CTT, estão devidamente representadas no diagrama (em relação ao design)?   |  O CTT permite a representação de relações entre as terefas para qual segue uma padronização dos elementos utilizados no diagrama.   |  [Página: 174, Capítulo 8. Organização do Espaço de Problema. Livro: SIMONE DINIZ JUNQUEIRO BARBOSA, BRUNO SANTANA DA SILVA, Interacão Humano-Computador, 1a. Edicão, Editora Campus, 2010. Publicado em: 03/05/2021.  ](https://unbbr-my.sharepoint.com/:w:/g/personal/211031566_aluno_unb_br/EdnWkv3yVpdLvBBAIXIzJpcBq79O_jyvZxCTTYXWYIoAUQ?e=sgQot8)  |  sim   |
| 4   |  As tarefas estão categorizadas corretamente como usuário, sistema, interativas e abstratas?   |  As tarefas são categorizadas seguindo tarefas realizadas fora do sistema, tarefas em que o sistema realiza processamentos, tarefas que tem diálogo sistema-usuário e representações.  |  [Página: 173, Capítulo 8. Organização do Espaço de Problema. Livro: SIMONE DINIZ JUNQUEIRO BARBOSA, BRUNO SANTANA DA SILVA, Interação Humano-Computador, 1a. Edição, Editora Campus, 2010. Publicado em: 03/05/2021.](https://docs.google.com/document/d/1H9dPdTs1-oUWtJE1_0oRHjBdduxNXuHVe2iA6DaI-Z8/edit?tab=t.0)  |  sim   |
| 5   |  O diagrama CTT utiliza corretamente os operadores para indicar a relação entre tarefas (por exemplo, concorrência, escolha, iteração)?  | Devem ser utilizados os operadores que indicam as relações entre tarefas. |  [Página: 173, Capítulo 8. Organização do Espaço de Problema. Livro: SIMONE DINIZ JUNQUEIRO BARBOSA, BRUNO SANTANA DA SILVA, Interação Humano-Computador, 1a. Edição, Editora Campus, 2010. Publicado em: 03/05/2021.](https://docs.google.com/document/d/1H9dPdTs1-oUWtJE1_0oRHjBdduxNXuHVe2iA6DaI-Z8/edit?tab=t.0)  |  sim   |
| 6  | O diagrama CTT apresenta relações como ativação, concorrência e passagem de informações?  |  Relações como ativação, concorrência e passagem de informações são necessárias para melhor compreensão.|  [Página: 173, Capítulo 8. Organização do Espaço de Problema. Livro: SIMONE DINIZ JUNQUEIRO BARBOSA, BRUNO SANTANA DA SILVA, Interação Humano-Computador, 1a. Edição, Editora Campus, 2010. Publicado em: 03/05/2021.](https://docs.google.com/document/d/1H9dPdTs1-oUWtJE1_0oRHjBdduxNXuHVe2iA6DaI-Z8/edit?tab=t.0)  |  sim   |

_Fonte: [Ana Joyce](https://github.com/anajoyceamorim), 2025._

</center>

# Gráfico dos itens do Árvores de Tarefas Concorrentes

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>

<div id="grafico5"></div>

<script>
  // Dados das respostas
  var data = [{
    values: [6, 0, 0],  // 11 respotas "sim" e 1 "não"
    labels: ["Sim", "Incompleto" ,"Não"],
    type: "pie",
    marker: {
      colors: ["#4CAF50", "#F44336"]  // Verde para "Sim" e Vermelho para "Não"
    }
  }];

  // Layout do gráfico
  var layout = {
    title: "Distribuição das Respostas - Itens de Desenvolvimento do Projeto",
    font: { size: 16 },
  };

  // Renderiza o gráfico
  Plotly.newPlot("grafico5", data, layout);
</script>


## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.  
> <a id="REF2" href="#anchor_2">2.</a> UNIVERSIDADE DE BRASÍLIA. Plano de ensino da disciplina Iteração Humano e Computador. Brasília, DF: UnB, 2024.  

| Versão |                 Descrição                 |                     Autor(es)                     |    Data    |                     Revisor(es)                     | Data de revisão |
| :----: | :--------------------------------------: | :-----------------------------------------------: | :--------: | :-------------------------------------------------: | :-------------: |
|  1.0   |   Documentação  | [Ana Joyce](https://github.com/anajoyceamorim)  | 10/02/2025 | [Nome](https://github.com/nome) |  xx/02/2025  |
