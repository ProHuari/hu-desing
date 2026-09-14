# Huari AI
 Hub Unificado de Auditoria e Relatórios de Inteligência

## visão geral

No cenário político contemporâneo, analistas, pesquisadores, assessores parlamentares, consultores eleitorais e estudantes enfrentam três desafios estruturais:
sobrecarga e pulverização de informações: pesquisas eleitorais, relatórios de conjuntura, discursos, propostas e dados públicos estão dispersos, sem padronização e de difícil cruzamento. 
Ausência de ferramentas especializadas: soluções genéricas de Inteligência Artificial não possuem o contexto, o vocabulário nem os filtros necessários para análises políticas, eleitorais e de políticas públicas, e as poucas ferramentas existentes sobre o tema possui uma visão enviesada . Escassez de capacitação prática e sequencial: há poucas trilhas estruturadas, ministradas por especialistas e institutos de referência, que combinem teoria, interpretação de dados e aplicação estratégica. 

Nossa plataforma tem a função de integrar os dados públicos junto com uma ánalise para garantir a fácil interpretação por parte de jornalista políticos, membros de orgãos oficiais e a todo membro da sociedade civil que gostaria de ser uma pessoa mais informada, e também ofertar por meio de conteúdos educativos  e cursos uma eduação política inicial para todo e qualquer úsuario que quiser utilizar a huari. 

Para melhor informar nossos úsuarios, alguns termos podém váriar de plataforma para plataforma ou de acordo com a bagagem de cada pessoa:

Gasto Suspeito: se trata de todo gasto superior a média comum, com fins não bens esclarecidos.

## arquitetura e dados

Utilizaremos dados de 6 apis governamentais ofciais, sendo elas Controladoria-Geral da União (CGU), Senado Federal do Brasil, Tribunal Superior Eleitoral (TSE),Receita Federal do Brasil, Câmara dos Deputados, esses dados são extraidos de forma semanais por meio de scripts em python de forma a cruzar sua atuação, seus projetos, sua presença e investigar qualquer aumento de patrimonio.

## inteligencia artificial

Será utilizada LLM da api o google ai studio, devido a sua maior capacidade de processamento de dados. como prompts principais será utilizados um para realizar uma biografia simples com formação, área de principais projetos, e informações básicas

### pesos e métricas

### mecanismos de logs e decisões 

## telas individuais e funcionalidades

**admin** : 
- gestão de cursos: essa página é dedicada ao controle dos cursos de toda a huari, gerenciando categoria de cursos, autores, podendo adicionar, modificar e excluir cursos, e gerenciar sua estruturas como aulas, materiais de apoio, módulos, questionários e a emissões de certificados 
- usuario: tela feita para criação de usuarios, modificações necessarias como senhas nomes e históricos, exclusões, banimentos, gerenciamentos de pesquisas e matriculas 
- dashboard: página para a monitoração de todos os leads e insights do site, como taxas de egajamento e rejeição, tempo na página, origem do trafego, visualizações , temas de pesquisa, reclamações, cursos vistos e certificados emitidos
  
**usuario:**
- home: página inicial apresentando o projeto e com resumos como call to action para a paginas de cursos, parlamentares, e chat huari 
- cursos home: página que mostra todos os cursos disponizveis em cards como imagem titulo e uma breve descrição 
- cursos aulas: o curso propriamente dito, aonde o usuario ve a aula em video 
- cursos questionario: questionario liberado após o final da aula ou do curso para que seja possivel emitir o certificado 
- chat:  chat huari, aonde nossa ia responderia as questões levantadas pelo usuaario sobre politica
- reclamações: pagina caso o usuario decida reclamar sobre qualquer erro do site ou de seus conteudos 
- parlamentares: pagina que assim como o cursos home, o usuario poderá filtrar por cxargo e estado e assim mostra todos os politicos do mesmo estado, ou "casa"


## Guia de desenvolvimento e setup
Sistema Operacional recomendado: Windows 11 e 10
Ferramentas de ambiente: Java versão 25, html5, css3 , Mysql, springboot 4.1.1  

dependencias: mysql driver, jpa, validation, lombok, spring web 
## Segurança, LGPD e Compliance


### documentações importantes 
[Link do Figma projeto landpage](https://www.figma.com/design/7HsIXNsC1cgzRGn2UIdKlA/Huari-ia--Novo-?node-id=1-2&p=f&t=BopaZzYlran4nnOQ-0)





