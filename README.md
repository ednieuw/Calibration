
### Regressions Excel calibration Logit / Rodbard, SRA and PLA

<div class=Section1>

<h1><font face="Verdana, Arial, Helvetica, sans-serif">Three Microsoft Excel calibration programs for the laboratory</font></h1>

<p><span class="style1" lang=EN-GB><font face="Verdana, Arial, Helvetica, sans-serif">This
      logit regression program in Excel is optimised to work with RIA and ELISA-data. </font></span><font face="Verdana, Arial, Helvetica, sans-serif"><span class="style1" lang=EN-GB><br>
The program can be used for fitting all sigmoid and half-sigmoid curves and even
a straight line.<br>
    </span></font><font face="Verdana, Arial, Helvetica, sans-serif"><a href="Logit/Logit.htm">Logit,
  4-parameter or Rodbard regression</a></font></p>
<p><span class="style1" lang=EN-GB><font face="Verdana, Arial, Helvetica, sans-serif">The
      PLA presented here is written in Microsoft Excel and is an copy of the
  method described by D.J. Finney.<br>
  Up to thirteen samples can be calculated </font></span><span class="style1" lang=EN-GB><font face="Verdana, Arial, Helvetica, sans-serif">by hand, from an ELISA plate reading or list of responses. <br>
  </font></span><font face="Verdana, Arial, Helvetica, sans-serif"><a href="PLA/PLA.htm">Parallel
  line assay PLA  </a></font></p>
<p><span class="style1" lang=EN-GB><font face="Verdana, Arial, Helvetica, sans-serif">The
      SRA presented here is written in Microsoft Excel and is an copy of the
  method described by D.J. Finney.<br>
</font></span><font face="Verdana, Arial, Helvetica, sans-serif"><a href="SRA/SRA.htm">Slope ratio assay SRA</a></font></p>
	<p class="auto-style1">
	<a href="#What_calibration_program_is_the_best_to_use">See below what is the 
	'best' calibration program to use.</a></p>
<table border="0" width="1024">
  <tr>
    <td width="1018" height="31" class="auto-style9" style="width: -1018">L<span class="auto-style8" lang=EN-GB>ogit</span></td>
    <td height="31" class="auto-style9" style="width: 97px">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
	PLA</td>
    <td width="1018" height="31" class="auto-style9" style="width: 339px">SRA</td>
  </tr>
  <tr>
    <td width="1018" height="31" style="width: -1018"><font face="Verdana, Arial, Helvetica, sans-serif"><a href="Logit/Logit.htm"><img src="Logit/logit-example.jpg" width="330" height="251" border="0"></a></font></td>
    <td height="31" style="width: 97px">
	<font face="Verdana, Arial, Helvetica, sans-serif"><a href="PLA/PLA.htm"><img src="PLA/PLA-example.jpg" width="330" height="251" border="0"></a></font></td>
    <td width="1018" height="31" style="width: 339px">
	<font face="Verdana, Arial, Helvetica, sans-serif"><a href="SRA/SRA.htm"><img src="SRA/SRA-example.jpg" width="330" height="250" border="0"></a></font></td>
  </tr>
</table>
<hr>
<p class="auto-style2"><strong>
<a name="What_calibration_program_is_the_best_to_use">What calibration program 
is the best to use?</a></strong></p>
	<p class="auto-style7" style="mso-ascii-font-family: Arial; mso-fareast-font-family: +mj-ea; mso-bidi-font-family: Arial; mso-ascii-theme-font: major-latin; mso-fareast-theme-font: major-fareast; mso-bidi-theme-font: major-bidi; mso-color-index: 3; language: nl; mso-style-textfill-type: solid; mso-style-textfill-fill-themecolor: text2; mso-style-textfill-fill-color: #FFFF99; mso-style-textfill-fill-alpha: 100.0%">
	SRA, PLA or Logit?</p>
	<p class="auto-style1">In following example the data from an ELISA was fed 
	into the three methods.<br>The calibration line is entered in the logit 
	regression program. <br>The data pairs that were suitable to be entered in 
	the SRA are marked purple and the dose-responses that could be used in the 
	PLA are coloured red in the picture below.<br>For the SRA and PLA only those 
	parts that are linear after transformation can be used resulting is a 
	smaller measuring range that can be entered.</p>
	<p class="auto-style1"><img alt="Logit,PLA or SRA" src="img3.jpg"></p>
	<p class="auto-style1"><img alt="SRA" src="img4.jpg"></p>
	<p class="auto-style1"><img alt="PLa" src="img5.jpg"></p>
	<p class="auto-style1">The results for the sample were calculated in:<br>PLA 
	as 265 ± 10%<br>SRA as 274 ± 10%<br>Logit as 261 ± 8%<br></p>
	<p class="auto-style5">My conclusions:</p>
	<p class="auto-style1">As to be expected the calculation method has no great 
	influence on the result. <br>All results fall well within in the&nbsp; 
	confidence limits of the three methods.<br><br><br>
	<span class="auto-style3">Benefits Logit</span><br>The measuring range is 
	large. <br>The rejection on SD of calculated result is based on historical 
	data.<br><span class="auto-style4">Cons Logit</span><br>Does not test 
	directly whether sample dilutes parallel with the standard. <br>Because of 
	the long measuring range one should be careful with the
	<a href="https://en.wikipedia.org/wiki/Hook_effect">hook effect or prozone 
	effect</a>.<br>NB both cons will be noted because the average will have a 
	bad standard deviation and be flagged) <br><br><span class="auto-style3">
	Benefits PLA</span><br>Robust accepted calculation method with descriptive 
	statistics.<br><span class="auto-style4">Disadvantages PLA</span><br>
	Relatively small measuring area. <br>The statistics is based on F-tests; 
	when a standard has perfect duplicates all sample results becomes invalid. 
	In practice this results is a rejection of a complete test so now and then 
	because the calibration line was so perfect by accident. And also the other 
	way round. Bad standard lines give valid results with large confidence 
	intervals.<br><br><span class="auto-style3">SRA benefits</span><br>Suitable 
	for low concentrations and activity measurements.<br>
	<span class="auto-style4">Cons SRA</span><br>Often very small measuring 
	range because the dose is linear.<br>The statistics is based on F-tests and 
	not on historical performances of the test.</p>
	<p class="auto-style1"><span class="auto-style3">Final conclusion</span><br>
	My choice to use logit regression as first option is its simplicity and long 
	measuring range. It is simple in its rejection criteria and it is easier to 
	use in LIMS systems.<br>SRA and PLA are a better choice if linearity is an 
	issue. </p>
	<p class="auto-style1">&nbsp;</p>
<p><font face="Verdana, Arial, Helvetica, sans-serif"><strong>HP41-C programs </strong></font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">I started learning programming
    on a HP-9715 desktop calculator at my laboratory in the end of the 1970's. <br>
  When the HP41C handheld calculator arrived on the market the same programming
  RPN-language was used and programming continued at home.<br>
  I made several programs and send them to the HP &quot;Users' program library
  Europe&quot; so
  they could be used by everyone. <br>
  Unfortunately this library is lost.
  I retained a copy of most of my listings.<br>
  These have been 
  scanned and they are available for reference and their formulas.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">If time comes I may
    add more. More in <a href="http://www.hpmuseum.org/">The museum of HP calculators</a> </font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif"><a href="HP41Cprograms/">Listing of files</a> </font></p>
	<p class="auto-style1">&nbsp;</p>
	<p class="auto-style1">&nbsp;</p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">November 2009 - 2021</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif"><a href="../index.html">&lt; --------
  Back home</a> </font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Ed Nieuwenhuys <a href="../email.html">Email</a> </font></p>
</div>

