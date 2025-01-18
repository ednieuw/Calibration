### Logit regression in Excel

<h1 align="left"><img src="Header.jpg" width="1024" alt="Header"><br>
A logit regression program in Microsoft Excel </h1>
<p class="style1"><a href="../Regression.htm">&lt;-- Back to calibration programs</a> </p>
<p><span class="style1" lang=EN-GB>  <span class="style1" lang=EN-GB>The program 
can be used for fitting sigmoid, half-sigmoid curves and even straight lines.<br>
</span></span><span class="style1" lang=EN-GB>This logit regression program in 
Excel is optimised to work with ELISA-data.<br>
  It is also very easy to use with lists like counts from radio immuno assays 
(RIA)</span><span class="style1" lang=EN-GB>.<br>
  The ELISA-logit worksheet can be adapted to be used with a LIMS; it supports 
input and output files.<br>
  </span><span class="style1" lang=EN-GB><br>
  Read the instructions in the sheet "Instructions" in the XLS-worksheet. <br>
  Several options can be set:<br>
  - the number of significant digits in the result, <br>
  - warning limit when signaling VC% of end result is above limit, <br>
  - extrapolation options,<br>
</span><span class="style1" lang=EN-GB>
  <br> 
    <strong><br>
  Advise (rules of thumb)</strong>: <br>
  Do not use more than 5 doses and a blank. (This logit needs a blank! (zero 
dose)). <br>
  If you want to use more data points invest in multiplos instead of more doses.<br>
  The lowest response of the calibration line must be higher than 6-10 times the 
standard deviations of the noise in your blank.<br>
  The highest response of your curves should be 10% higher in response than the 
second highest response.<br>
  Do not copy, move and paste in the worksheet.<br>
  </span><span class="style1" lang=EN-GB>If the program does not work properly 
use a new empty copy of it.<br>
<span lang=EN-GB><span class="style3" lang=EN-GB><span class="style4">Enable 
macro's to run the program!</span></span></span></span></p>
<p class="style1"><span lang=EN-GB>Several versions of the Logit program in an 
Excel-sheet are available.
    <br>
    The difference between version 2017 and 2018 is the calculation of the 
&lt;result and &gt;result. <br>
    In the 2017 and older versions the presentation of a &lt;result of &gt;result is 
based on the response (absorbance). <br>
    The 2018 version uses the values of the lowest and highest concentration of 
the calibration line.<br>
    Especially for validation purposes it is difficult to explain why lower and 
upper limits changes with every test. </span></p>
<p class="auto-style4">
	<a href="https://github.com/ednieuw/ELISA-logit-regression" class="auto-style3">These files on 
	Github</a></p>
<table width="1023" border="0">
  <tr>
    <td width="311" class="auto-style3">
	<a href="ELISA-Logit-V08Dec2021.xlsm">
	ELISA-Logit-V08Dec2021</a></td>
    <td width="702" class="auto-style3">Latest version. Corrected bug in &lt; and &gt; in 
	matrix results </td>
  </tr>
  <tr>
    <td class="style1"><a href="Manual%20ELISA-Logit-V01Jul2018%20in%20Microsoft%20Excel.docx">
	Manual in Dutch and English</a> as Docx </td>
    <td class="style1"><a href="Manual%20ELISA-Logit-V01Jul2018%20in%20Microsoft%20Excel.pdf" class="style5">
	As PDF</a> <a href="Linearity.xlsx"> </a></td>
  </tr>
  <tr>
    <td class="style1"><a href="Handleiding_Logit_in_Excel.pdf">
	Handleiding_Logit_in_Excel.pdf</a></td>
    <td class="style1">Manual in Dutch </td>
  </tr>
  <tr>
    <td class="style1">&nbsp;</td>
    <td class="style1">&nbsp;</td>
  </tr>
  <tr>
    <td class="style1">Older versions </td>
    <td class="style1">&nbsp;</td>
  </tr>
    <tr>
    <td class="auto-style1"><a href="ELISA-Logit-V01Jul2018.xlsm">
	ELISA-Logit-V01Jul2018</a></td>
    <td class="style1">&nbsp;<span class="auto-style2">version with spline. &lt; and &gt; 
	based on concentration of the calibration curve instead response 
	</span> </td>
    </tr>
  <tr>
    <td class="style1"><font size="-1"><span lang=EN-GB><a href="ELISA-Logit21042005.xls">
	ELISA-logit21042005</a></span></font></td>
    <td class="style1"><font size="-1">First validated program </font></td>
  </tr>
  <tr>
    <td class="style1"><font size="-1"><a href="ELISA-Logit-V04apr2007.xls">
	ELISA-Logit-V04apr2007</a></font></td>
    <td class="style1"><font size="-1">V21042005 --&gt; V04apr2007 absorbance file 
	input directly from two types of ELISA-readers. </font></td>
  </tr>
  <tr>
    <td class="style1"><font size="-1"><a href="ELISA-Logit-V25Oct2009.xls">
	ELISA-Logit-V25Oct2009</a></font></td>
    <td class="style1"><font size="-1">V04apr2007 --&gt; V25Oct2009 Corrected some 
	type errors in text</font></td>
  </tr>
  <tr>
    <td class="style1"><font size="-1"><a href="ELISA-Logit-V01Sept2012-Beta.xls">
	ELISA-Logit-V01Sept2012-Beta</a></font></td>
    <td class="style1"><p><font size="-1">      Added logit log graph. Corrected 
	minor issues      <br>
    </font></p>    </td>
  </tr>
  <tr>
    <td class="style1"><font size="-1"><a href="ELISA-Logit-V03Feb2013_1.xls">
	ELISA-Logit-V03Feb2013_1.xls</a></font></td>
    <td class="style1"><font size="-1">V03Feb2013_1. Small bug that data in 
	matrix result are sorted after "Sort on name". </font></td>
  </tr>
  <tr>
    <td class="style1"><a href="ELISA-Logit-V24May2017.xlsm">
	ELISA-Logit-V24May2017.xlsm</a></td>
    <td class="style1">&lt; and &gt; results based on the average respons </td>
  </tr>
  <tr>
    <td class="style1"><a href="ELISA-Logit-V20Jul2022.xlsm">
	ELISA-Logit-V20Jul2022.xlsm</a></td>
    <td class="style1">v08Dec2022 Without password protection on VBA (Copyright 
	2022)</td>
  </tr>
  <tr>
    <td class="style1">
	&nbsp;</td>
    <td class="style1">&nbsp;</td>
  </tr>
</table>
<p><span lang=EN-GB><span class="style3" lang=EN-GB><span class="style1"><a href="Linearity.xlsx">
Linearity.xlsx</a></span></span></span></p>
<p><img src="V01Sep2012.jpg" width="1024" alt="logit worksheet"></p>
<p><img src="V01Sep2012_Datasheet.jpg" width="1024" alt="logit data sheet"></p>
<p class="style1"><span lang=EN-GB>These programs can be used for non-profit 
purposes (Copyright 1998-2022)</span></p>
<p><span class="style1"><a href="../Regression.htm">&lt;-- Back to calibration 
programs</a></span></p>
<div align=center style='text-align:center'> 
  <hr size=2 width="100%" align=center>
</div>
<p><span lang=EN-GB>This page was revised 20 july 2022 by <a href="../../email.html">
Ed Nieuwenhuys</a></span></p>
</BODY>
</HTML>
