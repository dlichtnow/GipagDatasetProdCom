# GipagDatasetProdCom - Um Dataset Relacionado à Produção e Comercialização de Produtos da Horticultura e Fruticultura no Brasil

Dataset que reúne, em dois arquivos distintos, dados públicos relativos à produção e comercialização de frutas e hortaliças no Brasil. Para compor o dataset foram extraídos dados do Sistema IBGE de Recuperação Automática (SIDRA), da Companhia Nacional de Abastecimento (CONAB) e Censo Demográfico. O objetivo é reunir estes dados em um único dataset de forma a facilitar a análise de pesquisadores interessados evitando a necessidade de realização de diversas consultas. A extração foi feita com o uso de bibliotecas da linguagem Python, em especial Selenium

O dataset é formado por dois arquivos em formato CSV: um relacionado a fruticultura e outro a horticultura. Aqui eles estão disponibilizados no formato original e compactados (juntos e separados).   

<html>

<body lang=PT-BR>

<div>

<p class=MsoNormal style='margin-left:.1pt;text-indent:-.1pt'>            </p>

<p class=MsoCaption>Tabela 1. Descrição dos principais dados extraídos e
presentes no <i>dataset</i></p>

<div align=center>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0 width=579
 style='width:434.1pt;border-collapse:collapse;border:none'>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=center style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:center;
  text-indent:-.1pt;border:none'><b><span lang=EN-US style='font-size:10.0pt'>Dado
  Extraído</span></b></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border:solid black 1.0pt;
  border-left:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=center style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:center;
  text-indent:-.1pt;border:none'><b><span lang=EN-US style='font-size:10.0pt'>Descrição/Origem</span></b></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt;border:none'><span style='font-size:10.0pt'>Produto</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Nome do produto/cultura </span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt;border:none'><span style='font-size:10.0pt'>Sigla de
  Unidade Federativa</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Sigla UF</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt;border:none'><span style='font-size:10.0pt'>População Total
  da Unidade Federativa</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação retirada do
  Censo Demográfico em 2010.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt;border:none'><span style='font-size:10.0pt'>População
  Urbana da Unidade Federativa</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação proveniente do
  Censo Demográfico em 2010.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>População Rural da Unidade
  Federativa</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt;border:none'><span style='font-size:10.0pt'>Informação
  obtida pela subtração da população total pela população urbana.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Quantidade comercializada
  do produto na unidade da Ceasa na UF (em Kg)</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação retirada do
  CONAB e apresentada no <i>dataset</i> em 5 colunas: 2018, 2019, 2020, 2021 e
  2022.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Valor total da
  comercialização do produto pelas Ceasa na UF <br>
  (em R$)</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação retirada do
  CONAB e apresentada no <i>dataset </i>em 5 colunas: 2018, 2019, 2020, 2021 e
  2022.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Preço médio do produto
  praticado pelas Ceasa na UF<br>
  (em R$)</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação retirada do CONAB
  e apresentada no <i>dataset </i>em 5 colunas: 2018, 2019, 2020, 2021 e 2022.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Quantidade de
  estabelecimentos*</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação proveniente do
  SIDRA e apresentada na base de dados dividida em 3 colunas: Total, ligada a
  Agricultura Familiar e não ligada a Agricultura Familiar.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Quantidade produzida por
  produto na UF (em Toneladas)*</span></p>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>&nbsp;</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação proveniente do
  SIDRA e apresentada na base de dados dividida em 3 colunas: Total, ligada a
  Agricultura Familiar e não ligada a Agricultura Familiar.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Quantidade vendida do produto
  na UF (em Toneladas)*</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação proveniente do
  SIDRA e apresentada na base de dados dividida em 3 colunas: Total, ligada a Agricultura
  Familiar e não ligada a Agricultura Familiar.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Valor da produção do
  produto na UF (em R$)*</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação proveniente do
  SIDRA e apresentada na base de dados dividida em 3 colunas: Total, ligada a
  Agricultura Familiar e não ligada a Agricultura Familiar.</span></p>
  </td>
 </tr>
 <tr>
  <td width=204 valign=top style='width:153.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Valor das vendas do produto
  na UF<br>
  (em R$)*</span></p>
  </td>
  <td width=375 valign=top style='width:281.1pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt'>
  <p class=MsoNormal align=left style='margin-top:0cm;margin-right:0cm;
  margin-bottom:0cm;margin-left:.1pt;margin-bottom:.0001pt;text-align:left;
  text-indent:-.1pt'><span style='font-size:10.0pt'>Informação proveniente do
  SIDRA e apresentada na base de dados dividida em 3 colunas: Total, ligada a
  Agricultura Familiar e não ligada a Agricultura Familiar.</span></p>
  </td>
 </tr>
</table>

</div>

<p class=MsoNormal>*<span style='font-size:9.0pt'>No caso do arquivo com dados
da Fruticultura estes dados estão divididos em colunas por número de pés
existentes. Isto é valor discretizado em intervalos (até 50 pés e com 50 pés ou
mais). Futicultura envolve produtos agrícolas que possuem lavouras permanentes, isto é não precisam ser plantadas a cada safra, como ocorre com pés de laranja, por exemplo. Assim, no SIDRA para fruticultura estão presentes dados sobre o número de pés existentes. </span></p>

<p class=MsoNormal>&nbsp;</p>

</div>

</body>

</html>
