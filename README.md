# covid_vacinacao

Dados usados nos gráficos no twitter. 

- Última atualização: 10/05/2021


## Descrição das variáveis

- dataAplicacao: data de aplicação conforme consta na tabela original. Nenhuma informação foi modificada ou corrigida
- idadeAplicacao: idade do paciente na aplicação. Gerada a partir da data de nascimento informada
- uf: sigla da unidade federativa que aplicou a vacina
- dose: número da dose da vacina (0 = única, 1 = primeira dose, 2 = segunda dose)
- vacina: nome da vacina aplicada (Coronavac, Pfizer, Oxford, Oxford-Covishield e Janssen). Oxford e Oxford-Covishield é a mesma vacina. A segunda pode se referir às doses importadas da Índia, mas a consistência disso não foi averiguada
- n: número de doses aplicadas dada as demais variáveis da lista

## Atualizações

- 11/05/2021: alteração no nome do arquivo principal e ajustes na tabela. Observações duplicadas foram removidas do banco de dados original. Variável ``dose`` foi convertida para numeric. Dose única agora é representado por um ``0``
- 10/05/2021: banco de dados do dia 10/05 foi disponibilizado

## Fonte

Fonte: Open Datasus.

