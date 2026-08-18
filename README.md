# 📊 Farol de Inadimplência — Automação de Relatórios

![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-8B0000?style=flat&logo=visual-studio-code&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-F2C811?style=flat&logo=powerquery&logoColor=black)

> Automação completa do processo de geração do "Farol de Inadimplência" — um painel usado diariamente pelo time de vendas para acompanhar clientes inadimplentes por setor e região.

## 📌 Sobre o projeto

Este projeto foi desenvolvido durante minha atuação como **Aprendiz Financeiro na Ambev S.A.**, dando suporte ao time financeiro e de vendas em 4 cidades (Araraquara, Ribeirão Preto, Presidente Prudente e Araçatuba).

O processo de gerar o relatório de inadimplência era feito manualmente todos os dias: importar a base, tratar os dados, relacionar cada cliente ao seu respectivo vendedor/setor, montar os painéis e distribuir aos times. Um processo repetitivo, sujeito a erro humano e que consumia tempo operacional todos os dias.

A solução automatiza esse fluxo do início ao fim.

## 🎯 Problema

- Processo manual, repetido diariamente
- Alto risco de erro humano no tratamento e cruzamento dos dados
- Tempo operacional gasto em uma tarefa que não exigia análise, só execução repetitiva
- Distribuição do relatório também feita manualmente para cada vendedor

## 🛠️ Solução

Automação construída com **Excel + VBA + Power Query**, que:

1. **Importa automaticamente** a base de dados diária
2. **Trata os dados** (limpeza, padronização, remoção de inconsistências)
3. **Relaciona clientes** aos respectivos setores e vendedores
4. **Atualiza os painéis dinâmicos** com os dados do dia
5. **Gera relatórios em formato PNG**, prontos para distribuição
6. Envia/disponibiliza automaticamente os relatórios aos vendedores

## ⚙️ Tecnologias utilizadas

- **Excel** — estrutura dos painéis e dashboards
- **Power Query** — ETL (extração, transformação e carga dos dados)
- **VBA** — automação do fluxo completo (importação → tratamento → geração → distribuição)

## 📈 Resultados

| Métrica | Antes | Depois |
|---|---|---|
| Tempo de execução (por rodada) | 15–20 minutos | 2–5 minutos |
| Frequência | Diária | Diária (automatizada) |
| Alcance | ~100 vendedores em 4 cidades | ~100 vendedores em 4 cidades |

A automação reduziu o tempo de execução em **cerca de 75–85%**, eliminando uma tarefa manual repetitiva do dia a dia do time e reduzindo o risco de erro humano no tratamento dos dados. Como o processo é diário, o ganho de tempo se acumula significativamente ao longo do mês.

## 🧠 Aprendizados

- Aplicação prática de **Power Query** para automatizar rotinas de ETL que antes eram manuais
- Estruturação de lógica em **VBA** para orquestrar um fluxo completo (importar → tratar → gerar → distribuir)
- Entendimento de como pequenas automações geram impacto real de negócio quando aplicadas a processos recorrentes
- Importância de desenhar a solução pensando em manutenção futura (o processo precisava continuar funcionando mesmo com pequenas variações na base diária)

## 🔒 Nota sobre confidencialidade

Este projeto foi implementado em ambiente corporativo real, utilizando dados e estruturas internas da empresa. Por isso, **o código-fonte, as planilhas e os dados originais não são públicos**, respeitando os acordos de confidencialidade da empresa.

Este README documenta a arquitetura, o problema resolvido e os resultados obtidos, servindo como case de portfólio.

📍 Projeto desenvolvido durante a atuação como Aprendiz Financeiro na **Ambev S.A.**
