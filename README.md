# Entrega1BIGDATA

# Pesquisa e Detalhamento do Dataset: SINAN - Tuberculose, 2022
   - Seleção do Dataset: O grupo deve um dataset de interesse público ou de relevância para alguma área específica (saúde, educação, finanças, etc.). Justifiquem a escolha do dataset e expliquem como ele pode ser útil para solucionar problemas ou responder perguntas importantes.

Justificativa:

   - Origem Confiável: O PySUS coleta dados de bases de dados públicas publicadas pelo DATASUS, que é o Departamento de Informática do Sistema Único de Saúde (SUS) no Brasil. Esses dados são confiáveis e amplamente utilizados para análises epidemiológicas e tomada de decisões em saúde pública

   - Acessibilidade: O PySUS facilita o acesso e a manipulação desses dados, tornando-os acessíveis para pesquisadores, profissionais de saúde e formuladores de políticas.

Utilidade: A base de dados sobre tuberculose do ano de 2022 do SINAN é de extrema importancia por muitas razões, incluindo:


   - Monitoramento Epidemiológico: O dataset permite monitorar a incidência, prevalência e tendências da tuberculose em diferentes regiões do Brasil. Isso é crucial para identificar áreas de maior risco, planejar intervenções e avaliar o impacto de programas de controle da doença.

   - Identificação de Grupos de Risco: Com os dados demográficos e clínicos disponíveis, é possível identificar grupos de risco, como faixas etárias mais afetadas, comorbidades associadas e padrões de transmissão.

   - Pesquisa Científica: Pesquisadores podem explorar o dataset para investigar questões específicas, como fatores de risco, genética da doença e impacto socioeconômico.

Em resumo, o dataset de tuberculose de 2022 pelo PySUS é uma ferramenta essencial para entender a epidemiologia da tuberculose no Brasil, informar políticas de saúde e melhorar a prevenção e o tratamento da doença


# Apresentação do Dicionário de Dados:
   - Definição: Criem um dicionário de dados completo, que detalhe cada variável presente no dataset. Especifiquem o tipo de dado (numérico, categórico, texto, data, etc.), uma descrição breve do que cada variável representa e qualquer peculiaridade ou observação relevante.

1. **TP_NOT**: Tipo de notificação (Integer ou String)
2. **ID_AGRAVO**: Identificação do agravo de saúde (String)
3. **DT_NOTIFIC**: Data de notificação do caso (Date)
4. **NU_ANO**: Ano da notificação (Integer)
5. **SG_UF_NOT**: Sigla do estado onde foi feita a notificação (String)
6. **ID_MUNICIP**: Código do município onde foi feita a notificação (Integer ou String)
7. **ID_REGIONA**: Código da região de saúde responsável pela notificação (Integer ou String)
8. **DT_DIAG**: Data do diagnóstico (Date)
9. **ANO_NASC**: Ano de nascimento do paciente (Integer)
10. **NU_IDADE_N**: Idade do paciente no momento da notificação (Integer)
11. **CS_SEXO**: Sexo do paciente (String)
12. **CS_GESTANT**: Indicação se o paciente é gestante (Integer)
13. **CS_RACA**: Raça/cor do paciente (Integer)
14. **CS_ESCOL_N**: Nível de escolaridade do paciente (Integer)
15. **SG_UF**: Sigla do estado de residência do paciente (String)
16. **ID_MN_RESI**: Código do município de residência do paciente (Integer ou String)
17. **ID_RG_RESI**: Código da região de saúde de residência do paciente (Integer ou String)
18. **ID_PAIS**: Código do país de residência do paciente (Integer ou String)
19. **NDUPLIC_N**: Número de duplicações na notificação (Integer)
20. **IN_VINCULA**: Indica se a notificação foi vinculada a outro caso ou registro (Boolean ou Integer)
21. **DT_DIGITA**: Data de entrada dos dados no sistema (Date)
22. **DT_TRANSUS**: Data da transferência dos dados para o sistema do SUS (Date)
23. **DT_TRANSDM**: Data de transferência dos dados para o sistema municipal (Date)
24. **DT_TRANSSM**: Data de transferência dos dados para o sistema estadual (Date)
25. **DT_TRANSRM**: Data de transferência dos dados para o sistema regional (Date)
26. **DT_TRANSRS**: Data de transferência dos dados para outro sistema responsável (Date)
27. **DT_TRANSSE**: Data de transferência dos dados para o sistema de saúde especializado (Date)
28. **CS_FLXRET**: Código flexível de retorno (Integer)
29. **FLXRECEBI**: Indica se o formulário flexível foi recebido (Boolean ou Integer)
30. **MIGRADO_W**: Indica se o registro migrou para outro sistema ou plataforma (Boolean ou Integer)
31. **ID_OCUPA_N**: Código da ocupação do paciente (Integer ou String)
32. **TRATAMENTO**: Informações sobre o tratamento realizado (String)
33. **INSTITUCIO**: Instituição onde o paciente é tratado (String)
34. **RAIOX_TORA**: Resultado de raio-X torácico (String)
35. **TESTE_TUBE**: Resultado de teste tuberculínico (Integer)
36. **FORMA**: Forma clínica da tuberculose (String)
37. **EXTRAPU1_N**: Código da primeira doença extrapulmonar associada (Integer)
38. **EXTRAPU2_N**: Código da segunda doença extrapulmonar associada (Integer)
39. **EXTRAPUL_O**: Outras formas extrapulmonares observadas (String)
40. **AGRAVAIDS**: Indica se o paciente possui HIV/AIDS (Boolean ou Integer)
41. **AGRAVALCOO**: Indica se o paciente tem alcoolismo (Boolean ou Integer)
42. **AGRAVDIABE**: Indica se o paciente tem diabetes (Boolean ou Integer)
43. **AGRAVDOENC**: Outras doenças significativas associadas (String)
44. **AGRAVOUTRA**: Outras condições agravantes (String)
45. **AGRAVOUTDE**: Detalhes adicionais sobre outras condições agravantes (String)
46. **BACILOSC_E**: Resultado de exame baciloscópico (escarro) (String)
47. **BACILOS_E2**: Segundo resultado de exame baciloscópico (String)
48. **BACILOSC_O**: Outros resultados de exames baciloscópicos (String)
49. **CULTURA_ES**: Resultado da cultura de escarro (String)
50. **CULTURA_OU**: Resultado de outras culturas (String)
51. **HIV**: Status de HIV (Integer)
52. **HISTOPATOL**: Resultado de exame histopatológico (String)
53. **DT_INIC_TR**: Data de início do tratamento (Date)
54. **RIFAMPICIN**: Uso de rifampicina no tratamento (Integer)
55. **ISONIAZIDA**: Uso de isoniazida no tratamento (Integer)
56. **ETAMBUTOL**: Uso de etambutol no tratamento (Integer)
57. **ESTREPTOMI**: Uso de estreptomicina no tratamento (Integer)
58. **PIRAZINAMI**: Uso de pirazinamida no tratamento (Integer)
59. **ETIONAMIDA**: Uso de etionamida no tratamento (Integer)
60. **OUTRAS**: Outros medicamentos utilizados (String)
61. **OUTRAS_DES**: Descrição de outros medicamentos utilizados (String)
62. **TRAT_SUPER**: Indica se o tratamento foi supervisionado (Boolean ou Integer)
63. **NU_CONTATO**: Número de contatos do paciente (Integer)
64. **DOENCA_TRA**: Indica se houve transmissão da doença (Boolean ou Integer)
65. **SG_UF_AT**: Sigla do estado onde ocorreu a última atualização do caso (String)
66. **ID_MUNIC_A**: Código do município onde ocorreu a última atualização do caso (Integer ou String)
67. **DT_NOTI_AT**: Data da última notificação/atualização do caso (Date)
68. **SG_UF_2**: Outro estado relacionado ao paciente ou ao tratamento (String)
69. **ID_MUNIC_2**: Outro município relacionado ao paciente ou ao tratamento (Integer ou String)
70. **BACILOSC_1** a **BACILOSC_6**: Resultados sequenciais de exames baciloscópicos (String)
71. **TRATSUP_AT**: Indica se houve mudança no tratamento supervisionado (Boolean ou Integer)
72. **DT_MUDANCA**: Data da última mudança no registro (Date)
73. **NU_COMU_EX**: Número de comunicações externas (Integer)
74. **SITUA_9_M: Situação do paciente 9 meses após o diagnóstico (string)
75. **SITUA_12_M: Situação do paciente 12 meses após o diagnóstico (string)
76. **SITUA_ENCE: Situação específica para gestantes (string)
77. **DT_ENCERRA: Data de encerramento do caso (string)
78. **TPUNINOT: Tipo da unidade notificadora (string)
79. **POP_LIBER: Indica se o paciente pertence à população privada de liberdade (boolean)
80. **POP_RUA: Indica se o paciente é uma pessoa em situação de rua (boolean)
81. **POP_SAUDE: Indica se o paciente é um profissional de saúde (boolean)
82. **POP_IMIG: Indica se o paciente é um imigrante (boolean)
83. **BENEF_GOV:  Indica se o paciente recebe algum benefício governamental (boolean)
84. **AGRAVDROGA: Indica se há agravo por uso de drogas (boolean)
85. **AGRAVTABAC: Indica se há agravo por uso de tabaco (boolean)
86. **TEST_MOLEC:  Indica se foi realizado um teste molecular para diagnóstico (boolean)
87. **TEST_SENSI: Indica se foi realizado um teste de sensibilidade a medicamentos (boolean)
88. **ANT_RETRO: Indica se o paciente está em tratamento com antirretrovirais (boolean)
89. **BAC_APOS_6: Presença de bacilos após 6 meses de tratamento (boolean)
90. **TRANSF: Indica se houve transferência do paciente para outra unidade (boolean)
91. **UF_TRANSF: Unidade federativa para onde o paciente foi transferido (string)
92. **MUN_TRANSF: Município para onde o paciente foi transferido (string)





