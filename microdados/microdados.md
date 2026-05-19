Anos analisados: 2020, 2021, 2022, 2023, 2024

# 2022

# 2023

## Inconsistência 1
Aplicação regular<br>
Cor de referência: ROSA<br>
Questão: 138<br>
Item: ???<br>
Dia e Área: Dia 2, Área 1 (Ciências da Natureza e suas Tecnologias)

Comentário: Esta questão foi anulada e a tabela `ITENS_PROVA` indica corretamente `X` como gabarito.
Contudo, a tabela `RESULTADOS` indica a letra `D` como gabarito:
```
    gb = X (IN ITENS_PROVA TABLE)
    gb = D (IN RESULTADOS  TABLE)
```

Gabarito na tabela `ITENS_PROVA`:
`'BDBBABAAAEAAECBBEAACAAACEACBCACCCEDEDADBDBEEDDACCCABCDCBDACDAEACEECABADBEABADEBAABCDCABADCDAADECEDAEEDEECCEBADCCCABBABCAACDDDACDBEABDCDBEABDEBXEEBDADDABCCBCCABBADDBDDAEAEABCBEDECADCECCB'`

Gabarito na tabela `RESULTADOS`:
`'BDBBABAAAEAAECBBEAACAAACEACBCACCCEDEDADBDBEEDDACCCABCDCBDACDAEACEECABADBEABADEBAABCDCABADCDAADECEDAEEDEECCEBADCCCABBABCAACDDDACDBEABDCDBEABDEBDEEBDADDABCCBCCABBADDBDDAEAEABCBEDECADCECCB'`

Parâmetros da questão (TRI e Habilidade):
```
 ITEM         = ???
 question     = 138 (COR ROSA)
 gabarito     = X (ANULADA)
 A            = nan
 B            = nan
 C            = nan
 H            = 26
 motivo_aband = Exclusão pedagógica
```

## Inconsistência 2
O ou A estudante cujo índice na tabela `RESUTADOS` é `index = 2214483`

```
CO_PROVA_CN  1221 => CN - Azul
CO_PROVA_CH  1193 => CH - Branca
CO_PROVA_LC  1203 => LC - Rosa
CO_PROVA_MT  1211 => MT - Azul
```

As informações completas deste participante são:

```
NU_INSCRICAO                                                   210058315226
NU_ANO                                                                 2023
TP_FAIXA_ETARIA                                                           8
TP_SEXO                                                                   F
TP_ESTADO_CIVIL                                                           1
TP_COR_RACA                                                               3
TP_NACIONALIDADE                                                          1
TP_ST_CONCLUSAO                                                           3
TP_ANO_CONCLUIU                                                           0
TP_ESCOLA                                                                 1
TP_ENSINO                                                               NaN
IN_TREINEIRO                                                              1
CO_MUNICIPIO_ESC                                                        NaN
NO_MUNICIPIO_ESC                                                        NaN
CO_UF_ESC                                                               NaN
SG_UF_ESC                                                               NaN
TP_DEPENDENCIA_ADM_ESC                                                  NaN
TP_LOCALIZACAO_ESC                                                      NaN
TP_SIT_FUNC_ESC                                                         NaN
CO_MUNICIPIO_PROVA                                                  1501402
NO_MUNICIPIO_PROVA                                                    Belém
CO_UF_PROVA                                                              15
SG_UF_PROVA                                                              PA
TP_PRESENCA_CN                                                            1
TP_PRESENCA_CH                                                            1
TP_PRESENCA_LC                                                            1
TP_PRESENCA_MT                                                            1
CO_PROVA_CN                                                         1221.00
CO_PROVA_CH                                                         1193.00
CO_PROVA_LC                                                         1203.00
CO_PROVA_MT                                                         1211.00
NU_NOTA_CN                                                           384.80
NU_NOTA_CH                                                             0.00
NU_NOTA_LC                                                           289.40
NU_NOTA_MT                                                           342.80
TX_RESPOSTAS_CN               ABDBDEBCABBEDDBDABEEDDCCBCBCBAAECEBDE.EBCACEB
TX_RESPOSTAS_CH               .............................................
TX_RESPOSTAS_LC               BC..B........................................
TX_RESPOSTAS_MT               AEEACAAECCCAAACED...BCA.B.AEDDDCDAABCBCDCDBBC
TP_LINGUA                                                                 0
TX_GABARITO_CN                DBEABDABDCACDBECDDDBCAAABBACCCADEBECCCEDAEEED
TX_GABARITO_CH                ACEEABAADCDAADEABCDABCDCABCBDADEBAECABADBCDAE
TX_GABARITO_LC            BDBBABAAAEAAECBBEAACAAACEACBCACCCEDEDADBDBEEDD...
TX_GABARITO_MT                BCCDEEABCBEDCEABBEBDABDDADDADECAADDCCBEBEABCC
TP_STATUS_REDACAO                                                      1.00
NU_NOTA_COMP1                                                        100.00
NU_NOTA_COMP2                                                         80.00
NU_NOTA_COMP3                                                         80.00
NU_NOTA_COMP4                                                         80.00
NU_NOTA_COMP5                                                         40.00
NU_NOTA_REDACAO                                                      380.00
Q001                                                                      B
Q002                                                                      B
Q003                                                                      B
Q004                                                                      B
Q005                                                                      3
Q006                                                                      A
Q007                                                                      A
Q008                                                                      A
Q009                                                                      B
Q010                                                                      A
Q011                                                                      A
Q012                                                                      B
Q013                                                                      A
Q014                                                                      B
Q015                                                                      A
Q016                                                                      A
Q017                                                                      A
Q018                                                                      A
Q019                                                                      B
Q020                                                                      A
Q021                                                                      A
Q022                                                                      B
Q023                                                                      A
Q024                                                                      A
Q025                                                                      A
Name: 2214483, dtype: object
```