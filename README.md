# Mortalidade infantil por anomalias congênitas no Ceará — painel (versão preliminar)

Painel interativo com óbitos de menores de 1 ano por anomalia congênita (capítulo XVII da CID-10) e nascidos vivos com
anomalia registrada, residentes no Ceará, 2001–2025 (2025 preliminar). É uma página única (`index.html`): os dados estão
embutidos nela, e os filtros funcionam no navegador, sem servidor e sem internet depois de aberta.

## Aviso

Este painel é um projeto pessoal de pesquisa, em **versão preliminar e de teste**. Não é um produto oficial, não foi
revisado nem aprovado por nenhuma instituição e não representa a posição da Secretaria da Saúde do Ceará, do Ministério
da Saúde, da Universidade de Fortaleza (Unifor) ou de qualquer outra instituição a que o autor esteja vinculado.

**Pode conter erros, e é provável que contenha.** A concepção, o método, a organização do projeto e a revisão são de
cgarciafilho; a extração, o código, os gráficos e o texto foram feitos com inteligência artificial. A aba
“Sobre esta versão” diz quem fez o quê. Use com cautela e confira os números nas fontes oficiais (TabNet do DATASUS,
IntegraSUS) antes de citar ou de decidir algo com base neles. As limitações estão na aba “Qualidade e métodos”.

## Fontes

- SIM e SINASC: microdados públicos do DATASUS, arquivos do Ceará, baixados do FTP em 26/09/2026. Não há identificação de pessoas.
- Malha municipal: IBGE.
- Regionalização: lista de Superintendências Regionais e Áreas Descentralizadas de Saúde da SESA-CE de 02/03/2022.

## Contato

Erros, dúvidas e sugestões: cgarciafilho@gmail.com

## Sobre este repositório

Aqui fica só a página publicada. Os scripts que baixam os dados, calculam as contagens e conferem o painel (com o TabNet,
com cálculo direto em Python e por 300 combinações de filtros) ficam no projeto de origem, que não está publicado.

## Licença

MIT (arquivo `LICENSE`), para a página e o código. Os dados de origem (SIM e SINASC do DATASUS, malha do IBGE,
regionalização da SESA-CE) são públicos e seguem os termos de cada fonte.
