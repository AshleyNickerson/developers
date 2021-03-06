---
id: page-plugin
title: Language Plural Rules
header_title: EE Canary Release
header_icon: /assets/images/icons/plugins/ee-canary-release.png
breadcrumbs:
  Plugins: /plugins
nav:
  - label: Getting Started
    items:
      - label: Requesting Access
---

# Language Plural Rules


Languages vary in how they handle plurals of nouns or unit expressions ("hours", "meters", and so on). Some languages have two forms, like English; some languages have only a single form; and some languages have multiple forms (see Slovenian below). They also vary between cardinals (such as 1, 2, or 3) and ordinals (such as 1st, 2nd, or 3rd), and in ranges of cardinals (such as "1-2", used in expressions like "1-2 meters long").

<style>
.page-navigation{
	display: none;
}
.page-content-container {
     padding-right:10px !important;
}      


</style>

<table width="90%" cellpadding="0" cellspacing="0" border="0">
	<tbody><tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Afrikaans</td><td rowspan="6"><a name="af" href="#af">af</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 dag<br>1,0 dag</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 dae<br>0,9 dae</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Neem die 15e afdraai na regs.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1–2 dae</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 dae</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 dae</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Akan</td><td rowspan="3"><a name="ak" href="#ak">ak</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 0..1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="8">Albanian</td><td rowspan="8"><a name="sq" href="#sq">sq</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 libër<br>1,0 libër</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 libra<br>0,9 libra</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">ordinal</td><td>one</td><td>1</td><td>Merrni kthesën e 1-rë në të djathtë.</td><td nowrap="">n = 1</td></tr>
	<tr><td>many</td><td>4, 24, 34, 44, 54, 64, 74, 84, 104, 1004, …</td><td>Merrni kthesën e 4-t në të djathtë.</td><td nowrap="">n % 10 = 4 and<br>&nbsp;&nbsp;n % 100 != 14</td></tr>
	<tr><td>other</td><td>0, 2, 3, 5~17, 100, 1000, 10000, 100000, 1000000, …</td><td>Merrni kthesën e 2-të në të djathtë.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1-2 libra</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0-1 libër</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0-2 libra</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Amharic</td><td rowspan="6"><a name="am" href="#am">am</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td>1 ቀን<br>1.0 ቀን</td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 ቀናት<br>1.1 ቀናት</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>በቀኝ በኩል ባለው በ15ኛው መታጠፊያ ግባ።</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>0–1 ቀን</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>0–2 ቀናት</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>1.1–2</td><td>1.1–2 ቀናት</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="30">Arabic</td><td rowspan="30"><a name="ar" href="#ar">ar</a></td><td rowspan="6">cardinal</td><td>zero</td><td>0<br>0.0, 0.00, 0.000, 0.0000</td><td>&#8235;٠ كتاب<br>٠٫٠٠٠٠ كتاب&#8236;</td><td nowrap="">n = 0</td></tr>
	<tr><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>&#8235;ولد واحد حضر<br>ولد واحد حضر&#8236;</td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td>&#8235;ولدان حضرا<br>ولدان حضرا&#8236;</td><td nowrap="">n = 2</td></tr>
	<tr><td>few</td><td>3~10, 103~110, 1003, …<br>3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0, 103.0, 1003.0, …</td><td>&#8235;٣ أولاد حضروا<br>٣٫٠ أولاد حضروا&#8236;</td><td nowrap="">n % 100 = 3..10</td></tr>
	<tr><td>many</td><td>11~26, 111, 1011, …<br>11.0, 12.0, 13.0, 14.0, 15.0, 16.0, 17.0, 18.0, 111.0, 1011.0, …</td><td>&#8235;١١ ولدًا حضروا<br>١١٫٠ ولدًا حضروا&#8236;</td><td nowrap="">n % 100 = 11..99</td></tr>
	<tr><td>other</td><td>100~102, 200~202, 300~302, 400~402, 500~502, 600, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.1, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>&#8235;١٠٠ ولد حضروا<br>٠٫١ ولد حضروا&#8236;</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>&#8235;اتجه إلى المنعطف الـ ١٥ يمينًا.&#8236;</td><td nowrap=""></td></tr>
	<tr><td rowspan="23">range</td><td>zero+one</td><td>0–1</td><td>&#8235;٠–١ كتاب&#8236;</td><td nowrap="">zero + one → zero</td></tr>
	<tr><td>zero+two</td><td>0–2</td><td>&#8235;٠–٢ كتاب&#8236;</td><td nowrap="">zero + two → zero</td></tr>
	<tr><td>zero+few</td><td>0–3</td><td>&#8235;٠–٣ أولاد حضروا&#8236;</td><td nowrap="">zero + few → few</td></tr>
	<tr><td>zero+many</td><td>0–11</td><td>&#8235;٠–١١ ولدًا حضروا&#8236;</td><td nowrap="">zero + many → many</td></tr>
	<tr><td>zero+other</td><td>0–100</td><td>&#8235;٠–١٠٠ ولد حضروا&#8236;</td><td nowrap="">zero + other → other</td></tr>
	<tr><td>one+two</td><td>1–2</td><td>&#8235;١–٢ ولد حضروا&#8236;</td><td nowrap="">one + two → other</td></tr>
	<tr><td>one+few</td><td>1–3</td><td>&#8235;١–٣ أولاد حضروا&#8236;</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–11</td><td>&#8235;١–١١ ولدًا حضروا&#8236;</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–100</td><td>&#8235;١–١٠٠ ولد حضروا&#8236;</td><td nowrap="">one + other → other</td></tr>
	<tr><td>two+few</td><td>2–3</td><td>&#8235;٢–٣ أولاد حضروا&#8236;</td><td nowrap="">two + few → few</td></tr>
	<tr><td>two+many</td><td>2–11</td><td>&#8235;٢–١١ ولدًا حضروا&#8236;</td><td nowrap="">two + many → many</td></tr>
	<tr><td>two+other</td><td>2–100</td><td>&#8235;٢–١٠٠ ولد حضروا&#8236;</td><td nowrap="">two + other → other</td></tr>
	<tr><td>few+few</td><td>3–103</td><td>&#8235;٣–١٠٣ أولاد حضروا&#8236;</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>3–11</td><td>&#8235;٣–١١ ولدًا حضروا&#8236;</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>3–100</td><td>&#8235;٣–١٠٠ ولد حضروا&#8236;</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+few</td><td>11–103</td><td>&#8235;١١–١٠٣ أولاد حضروا&#8236;</td><td nowrap="">many + few → few</td></tr>
	<tr><td>many+many</td><td>11–111</td><td>&#8235;١١–١١١ ولدًا حضروا&#8236;</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>11–100</td><td>&#8235;١١–١٠٠ ولد حضروا&#8236;</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0.1–1</td><td>&#8235;٠٫١–١ ولد حضروا&#8236;</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+two</td><td>0.1–2</td><td>&#8235;٠٫١–٢ ولد حضروا&#8236;</td><td nowrap="">other + two → other</td></tr>
	<tr><td>other+few</td><td>0.1–3</td><td>&#8235;٠٫١–٣ أولاد حضروا&#8236;</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0.1–11</td><td>&#8235;٠٫١–١١ ولدًا حضروا&#8236;</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0.1–100</td><td>&#8235;٠٫١–١٠٠ ولد حضروا&#8236;</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Armenian</td><td rowspan="7"><a name="hy" href="#hy">hy</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.5</td><td>այդ 1 ժամը<br>այդ 1,5 ժամը</td><td nowrap="">i = 0,1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>2.0~3.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>այդ 2 ժամերը<br>այդ 2,0 ժամերը</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1</td><td>Թեքվեք աջ 1-ին խաչմերուկից:</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …</td><td>Թեքվեք աջ 2-րդ խաչմերուկից:</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>այդ 0–1 ժամը</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>այդ 0–2 ժամերը</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>2–100</td><td>այդ 2–100 ժամերը</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="8">Assamese</td><td rowspan="8"><a name="as" href="#as">as</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td rowspan="5">ordinal</td><td>one</td><td>1, 5, 7~10</td><td rowspan="5"><i>Not available.</i></td><td nowrap="">n = 1,5,7,8,9,10</td></tr>
	<tr><td>two</td><td>2, 3</td><td nowrap="">n = 2,3</td></tr>
	<tr><td>few</td><td>4</td><td nowrap="">n = 4</td></tr>
	<tr><td>many</td><td>6</td><td nowrap="">n = 6</td></tr>
	<tr><td>other</td><td>0, 11~25, 100, 1000, 10000, 100000, 1000000, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Asturian</td><td rowspan="3"><a name="ast" href="#ast">ast</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 día</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 díes<br>1,5 díes</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Asu</td><td rowspan="3"><a name="asa" href="#asa">asa</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="9">Azerbaijani</td><td rowspan="9"><a name="az" href="#az">az</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>Alış-veriş katınızda 1 X var.<br>Almaq istəyirsiniz?<br>Alış-veriş katınızda 1,0 X var.<br>Almaq istəyirsiniz?</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>Alış-veriş kartınızda 2 X var.<br>Almaq istəyirsiniz?<br>Alış-veriş kartınızda 0,9 X var.<br>Almaq istəyirsiniz?</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">ordinal</td><td>one</td><td>1, 2, 5, 7, 8, 11, 12, 15, 17, 18, 20~22, 25, 101, 1001, …</td><td>1-ci sağ döngəni seçin.</td><td nowrap="">i % 10 = 1,2,5,7,8 or<br>i % 100 = 20,50,70,80</td></tr>
	<tr><td>few</td><td>3, 4, 13, 14, 23, 24, 33, 34, 43, 44, 53, 54, 63, 64, 73, 74, 100, 1003, …</td><td>3-cü sağ döngəni seçin.</td><td nowrap="">i % 10 = 3,4 or<br>i % 1000 = 100,200,300..etc</td></tr>
	<tr><td>many</td><td>0, 6, 16, 26, 36, 40, 46, 56, 106, 1006, …</td><td>6-cı sağ döngəni seçin.</td><td nowrap="">i = 0 or<br>i % 10 = 6 or<br>i % 100 = 40,60,90</td></tr>
	<tr><td>other</td><td>9, 10, 19, 29, 30, 39, 49, 59, 69, 79, 109, 1000, 10000, 100000, 1000000, …</td><td>9-cu sağ döngəni seçin.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>Alış-veriş kartınızda 1–2 X var.<br>Almaq istəyirsiniz?</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>Alış-veriş katınızda 0–1 X var.<br>Almaq istəyirsiniz?</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>Alış-veriş kartınızda 0–2 X var.<br>Almaq istəyirsiniz?</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Bambara</td><td rowspan="2"><a name="bm" href="#bm">bm</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="10">Bangla</td><td rowspan="10"><a name="bn" href="#bn">bn</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td>সসে ১টি আপেল খেল, সেটা ভাল<br>সসে ১.০টি আপেল খেল, সেটা ভাল</td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>সসে ২টি আপেল খেল, সেগুলি ভাল<br>সসে ১.১টি আপেল খেল, সেগুলি ভাল</td><td nowrap=""></td></tr>
	<tr><td rowspan="5">ordinal</td><td>one</td><td>1, 5, 7~10</td><td>ডান দিকে ১ম বাঁকটি নিন।</td><td nowrap="">n = 1,5,7,8,9,10</td></tr>
	<tr><td>two</td><td>2, 3</td><td>ডান দিকে ২য় বাঁকটি নিন।</td><td nowrap="">n = 2,3</td></tr>
	<tr><td>few</td><td>4</td><td>ডান দিকে ৪র্থ বাঁকটি নিন।</td><td nowrap="">n = 4</td></tr>
	<tr><td>many</td><td>6</td><td>ডান দিকে ৬ষ্ঠ বাঁকটি নিন।</td><td nowrap="">n = 6</td></tr>
	<tr><td>other</td><td>0, 11~25, 100, 1000, 10000, 100000, 1000000, …</td><td>ডান দিকে ১১তম বাঁকটি নিন।</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>সসে ০–১টি আপেল খেল, সেটা ভাল</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>সসে ০–২টি আপেল খেল, সেগুলি ভাল</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>1.1–2</td><td>সসে ১.১–২টি আপেল খেল, সেগুলি ভাল</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Basque</td><td rowspan="6"><a name="eu" href="#eu">eu</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>Nire 1 lagunarekin nago<br>Nire 1,0 lagunarekin nago</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>Nire 2 lagunekin nago<br>Nire 0,9 lagunekin nago</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15.<br>bira eskuinetara</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>Nire 1–2 lagunekin nago</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>Nire 0–1 lagunekin nago</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>Nire 0–2 lagunekin nago</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="22">Belarusian</td><td rowspan="22"><a name="be" href="#be">be</a></td><td rowspan="4">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …<br>1.0, 21.0, 31.0, 41.0, 51.0, 61.0, 71.0, 81.0, 101.0, 1001.0, …</td><td>з 1 кнігі за 1 дзень<br>з 1,0 кнігі за 1,0 дзень</td><td nowrap="">n % 10 = 1 and<br>&nbsp;&nbsp;n % 100 != 11</td></tr>
	<tr><td>few</td><td>2~4, 22~24, 32~34, 42~44, 52~54, 62, 102, 1002, …<br>2.0, 3.0, 4.0, 22.0, 23.0, 24.0, 32.0, 33.0, 102.0, 1002.0, …</td><td>з 2 кніг за 2 дні<br>з 2,0 кніг за 2,0 дні</td><td nowrap="">n % 10 = 2..4 and<br>&nbsp;&nbsp;n % 100 != 12..14</td></tr>
	<tr><td>many</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0, 11.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>з 5 кніг за 5 дзён<br>з 5,0 кніг за 5,0 дзён</td><td nowrap="">n % 10 = 0 or<br>n % 10 = 5..9 or<br>n % 100 = 11..14</td></tr>
	<tr><td>other</td><td>0.1~0.9, 1.1~1.7, 10.1, 100.1, 1000.1, …</td><td>з 0,1 кніги за 0,1 дні</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>few</td><td>2, 3, 22, 23, 32, 33, 42, 43, 52, 53, 62, 63, 72, 73, 82, 83, 102, 1002, …</td><td>2-і дом злева</td><td nowrap="">n % 10 = 2,3 and<br>&nbsp;&nbsp;n % 100 != 12,13</td></tr>
	<tr><td>other</td><td>0, 1, 4~17, 100, 1000, 10000, 100000, 1000000, …</td><td>1-ы дом злева</td><td nowrap=""></td></tr>
	<tr><td rowspan="16">range</td><td>one+one</td><td>1–21</td><td>з 1–21 кнігі за 1–21 дзень</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+few</td><td>1–2</td><td>з 1–2 кніг за 1–2 дні</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–5</td><td>з 1–5 кніг за 1–5 дзён</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–1.1</td><td>з 1–1,1 кніги за 1–1,1 дні</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+one</td><td>2–21</td><td>з 2–21 кнігі за 2–21 дзень</td><td nowrap="">few + one → one</td></tr>
	<tr><td>few+few</td><td>2–22</td><td>з 2–22 кніг за 2–22 дні</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>2–5</td><td>з 2–5 кніг за 2–5 дзён</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>2–10.1</td><td>з 2–10,1 кніги за 2–10,1 дні</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+one</td><td>0–1</td><td>з 0–1 кнігі за 0–1 дзень</td><td nowrap="">many + one → one</td></tr>
	<tr><td>many+few</td><td>0–2</td><td>з 0–2 кніг за 0–2 дні</td><td nowrap="">many + few → few</td></tr>
	<tr><td>many+many</td><td>0–5</td><td>з 0–5 кніг за 0–5 дзён</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>0–0.1</td><td>з 0–0,1 кніги за 0–0,1 дні</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0.1–1</td><td>з 0,1–1 кнігі за 0,1–1 дзень</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0.1–2</td><td>з 0,1–2 кніг за 0,1–2 дні</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0.1–5</td><td>з 0,1–5 кніг за 0,1–5 дзён</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0.1–1.1</td><td>з 0,1–1,1 кніги за 0,1–1,1 дні</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Bemba</td><td rowspan="3"><a name="bem" href="#bem">bem</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Bena</td><td rowspan="3"><a name="bez" href="#bez">bez</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td>Bihari</td><td><a name="bh" href="#bh">bh</a></td><td><i>=<a href="#bho">bho</a></i></td><td><i>=<a href="#bho">bho</a></i></td><td><i>=<a href="#bho">bho</a></i></td><td><i>=<a href="#bho">bho</a></i></td><td nowrap=""><i>=<a href="#bho">bho</a></i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Bodo</td><td rowspan="3"><a name="brx" href="#brx">brx</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="13">Bosnian</td><td rowspan="13"><a name="bs" href="#bs">bs</a></td><td rowspan="3">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …<br>0.1, 1.1, 2.1, 3.1, 4.1, 5.1, 6.1, 7.1, 10.1, 100.1, 1000.1, …</td><td>za 1 mjesec<br>za 0,1 mjesec</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 1 and<br>&nbsp;&nbsp;i % 100 != 11 or<br>f % 10 = 1 and<br>&nbsp;&nbsp;f % 100 != 11</td></tr>
	<tr><td>few</td><td>2~4, 22~24, 32~34, 42~44, 52~54, 62, 102, 1002, …<br>0.2~0.4, 1.2~1.4, 2.2~2.4, 3.2~3.4, 4.2~4.4, 5.2, 10.2, 100.2, 1000.2, …</td><td>za 2 mjeseca<br>za 0,2 mjeseca</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 2..4 and<br>&nbsp;&nbsp;i % 100 != 12..14 or<br>f % 10 = 2..4 and<br>&nbsp;&nbsp;f % 100 != 12..14</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 0.5~1.0, 1.5~2.0, 2.5~2.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>za 5 mjeseci<br>za 0,5 mjeseci</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Skrenite na 15.<br>križanju desno.</td><td nowrap=""></td></tr>
	<tr><td rowspan="9">range</td><td>one+one</td><td>0.1–1</td><td>za 0,1 – 1 mjesec</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+few</td><td>0.1–2</td><td>za 0,1 – 2 mjeseca</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+other</td><td>0.1–5</td><td>za 0,1 – 5 mjeseci</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+one</td><td>0.2–1</td><td>za 0,2 – 1 mjesec</td><td nowrap="">few + one → one</td></tr>
	<tr><td>few+few</td><td>0.2–2</td><td>za 0,2 – 2 mjeseca</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+other</td><td>0.2–5</td><td>za 0,2 – 5 mjeseci</td><td nowrap="">few + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>za 0 – 1 mjesec</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0–2</td><td>za 0 – 2 mjeseca</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+other</td><td>0–5</td><td>za 0 – 5 mjeseci</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Breton</td><td rowspan="6"><a name="br" href="#br">br</a></td><td rowspan="5">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 81, 101, 1001, …<br>1.0, 21.0, 31.0, 41.0, 51.0, 61.0, 81.0, 101.0, 1001.0, …</td><td>1 deiz<br>1,0 deiz</td><td nowrap="">n % 10 = 1 and<br>&nbsp;&nbsp;n % 100 != 11,71,91</td></tr>
	<tr><td>two</td><td>2, 22, 32, 42, 52, 62, 82, 102, 1002, …<br>2.0, 22.0, 32.0, 42.0, 52.0, 62.0, 82.0, 102.0, 1002.0, …</td><td>2 zeiz<br>2,0 zeiz</td><td nowrap="">n % 10 = 2 and<br>&nbsp;&nbsp;n % 100 != 12,72,92</td></tr>
	<tr><td>few</td><td>3, 4, 9, 23, 24, 29, 33, 34, 39, 43, 44, 49, 103, 1003, …<br>3.0, 4.0, 9.0, 23.0, 24.0, 29.0, 33.0, 34.0, 103.0, 1003.0, …</td><td>3 deiz<br>3,0 deiz</td><td nowrap="">n % 10 = 3..4,9 and<br>&nbsp;&nbsp;n % 100 != 10..19,70..79,90..99</td></tr>
	<tr><td>many</td><td>1000000, …<br>1000000.0, 1000000.00, 1000000.000, …</td><td>1&nbsp;000&nbsp;000 a zeizioù<br>1&nbsp;000&nbsp;000,0 a zeizioù</td><td nowrap="">n != 0 and<br>&nbsp;&nbsp;n % 1000000 = 0</td></tr>
	<tr><td>other</td><td>0, 5~8, 10~20, 100, 1000, 10000, 100000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, …</td><td>5 deiz<br>0,9 deiz</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Bulgarian</td><td rowspan="6"><a name="bg" href="#bg">bg</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 ден<br>1,0 ден</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 дена<br>0,9 дена</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Завийте надясно по 15-ата пресечка.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1 – 2 дена</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0 – 1 дена</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0 – 2 дена</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Burmese</td><td rowspan="3"><a name="my" href="#my">my</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>၁၅ရက္<br>၁.၅ရက္</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>၁၅ အုပ်မြောက်</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>၀ - ၁၀၀ရက္</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Cantonese</td><td rowspan="3"><a name="yue" href="#yue">yue</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15 本書<br>1.5 本書</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>第 15 本書</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0-100 本書</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="9">Catalan</td><td rowspan="9"><a name="ca" href="#ca">ca</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 dia</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 dies<br>1,5 dies</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">ordinal</td><td>one</td><td>1, 3</td><td>Agafa el 1r a la dreta.</td><td nowrap="">n = 1,3</td></tr>
	<tr><td>two</td><td>2</td><td>Agafa el 2n a la dreta.</td><td nowrap="">n = 2</td></tr>
	<tr><td>few</td><td>4</td><td>Agafa el 4t a la dreta.</td><td nowrap="">n = 4</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>Agafa el 5è a la dreta.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1-2 dies</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0-1 dies</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0-2 dies</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Central Atlas Tamazight</td><td rowspan="3"><a name="tzm" href="#tzm">tzm</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1, 11~24<br>0.0, 1.0, 11.0, 12.0, 13.0, 14.0, 15.0, 16.0, 17.0, 18.0, 19.0, 20.0, 21.0, 22.0, 23.0, 24.0</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 0..1 or<br>n = 11..99</td></tr>
	<tr><td>other</td><td>2~10, 100~106, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Central Kurdish</td><td rowspan="3"><a name="ckb" href="#ckb">ckb</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Chechen</td><td rowspan="4"><a name="ce" href="#ce">ce</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Cherokee</td><td rowspan="3"><a name="chr" href="#chr">chr</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Chiga</td><td rowspan="3"><a name="cgg" href="#cgg">cgg</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Chinese</td><td rowspan="3"><a name="zh" href="#zh">zh</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15 天<br>1.5 天</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>在第 15 个路口右转。</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0-100 天</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Colognian</td><td rowspan="4"><a name="ksh" href="#ksh">ksh</a></td><td rowspan="3">cardinal</td><td>zero</td><td>0<br>0.0, 0.00, 0.000, 0.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 0</td></tr>
	<tr><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Cornish</td><td rowspan="4"><a name="kw" href="#kw">kw</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="13">Croatian</td><td rowspan="13"><a name="hr" href="#hr">hr</a></td><td rowspan="3">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …<br>0.1, 1.1, 2.1, 3.1, 4.1, 5.1, 6.1, 7.1, 10.1, 100.1, 1000.1, …</td><td>za 1 mjesec<br>za 0,1 mjesec</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 1 and<br>&nbsp;&nbsp;i % 100 != 11 or<br>f % 10 = 1 and<br>&nbsp;&nbsp;f % 100 != 11</td></tr>
	<tr><td>few</td><td>2~4, 22~24, 32~34, 42~44, 52~54, 62, 102, 1002, …<br>0.2~0.4, 1.2~1.4, 2.2~2.4, 3.2~3.4, 4.2~4.4, 5.2, 10.2, 100.2, 1000.2, …</td><td>za 2 mjeseca<br>za 0,2 mjeseca</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 2..4 and<br>&nbsp;&nbsp;i % 100 != 12..14 or<br>f % 10 = 2..4 and<br>&nbsp;&nbsp;f % 100 != 12..14</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 0.5~1.0, 1.5~2.0, 2.5~2.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>za 5 mjeseci<br>za 0,5 mjeseci</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Skrenite na 15.<br>križanju desno.</td><td nowrap=""></td></tr>
	<tr><td rowspan="9">range</td><td>one+one</td><td>0.1–1</td><td>za 0,1 – 1 mjesec</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+few</td><td>0.1–2</td><td>za 0,1 – 2 mjeseca</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+other</td><td>0.1–5</td><td>za 0,1 – 5 mjeseci</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+one</td><td>0.2–1</td><td>za 0,2 – 1 mjesec</td><td nowrap="">few + one → one</td></tr>
	<tr><td>few+few</td><td>0.2–2</td><td>za 0,2 – 2 mjeseca</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+other</td><td>0.2–5</td><td>za 0,2 – 5 mjeseci</td><td nowrap="">few + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>za 0 – 1 mjesec</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0–2</td><td>za 0 – 2 mjeseca</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+other</td><td>0–5</td><td>za 0 – 5 mjeseci</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="19">Czech</td><td rowspan="19"><a name="cs" href="#cs">cs</a></td><td rowspan="4">cardinal</td><td>one</td><td>1</td><td>1 den</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>few</td><td>2~4</td><td>2 dny</td><td nowrap="">i = 2..4 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>many</td><td>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>1,5 dne</td><td nowrap="">v != 0</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>5 dní</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Na 15.<br>křižovatce odbočte vpravo.</td><td nowrap=""></td></tr>
	<tr><td rowspan="14">range</td><td>one+few</td><td>1–2</td><td>1–2 dny</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–10.0</td><td>1–10,0 dne</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–5</td><td>1–5 dní</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+few</td><td>2–4</td><td>2–4 dny</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>2–10.0</td><td>2–10,0 dne</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>2–5</td><td>2–5 dní</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+one</td><td>0.0–1</td><td>0,0–1 den</td><td nowrap="">many + one → one</td></tr>
	<tr><td>many+few</td><td>0.0–2</td><td>0,0–2 dny</td><td nowrap="">many + few → few</td></tr>
	<tr><td>many+many</td><td>0.0–10.0</td><td>0,0–10,0 dne</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>0.0–5</td><td>0,0–5 dní</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 den</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0–2</td><td>0–2 dny</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0–10.0</td><td>0–10,0 dne</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0–5</td><td>0–5 dní</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Danish</td><td rowspan="7"><a name="da" href="#da">da</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>0.1~1.6</td><td>1 dag<br>0,1 dag</td><td nowrap="">n = 1 or<br>t != 0 and<br>&nbsp;&nbsp;i = 0,1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 2.0~3.4, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 dage<br>2,0 dage</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Tag den 15.<br>vej til højre.</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">range</td><td>one+one</td><td>0.1–1</td><td>0,1-1 dag</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0.1–2</td><td>0,1-2 dage</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0-1 dag</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0-2 dage</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Divehi</td><td rowspan="3"><a name="dv" href="#dv">dv</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Dutch</td><td rowspan="6"><a name="nl" href="#nl">nl</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 dag</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 dagen<br>1,5 dagen</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Neem de 15e afslag rechts.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1-2 dagen</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0-1 dag</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0-2 dagen</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Dzongkha</td><td rowspan="2"><a name="dz" href="#dz">dz</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>ཉིནམ་ ༡༥ <br>ཉིནམ་ ༡.༥ </td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="9">English</td><td rowspan="9"><a name="en" href="#en">en</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 day</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 days<br>1.5 days</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">ordinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …</td><td>Take the 1st right.</td><td nowrap="">n % 10 = 1 and<br>&nbsp;&nbsp;n % 100 != 11</td></tr>
	<tr><td>two</td><td>2, 22, 32, 42, 52, 62, 72, 82, 102, 1002, …</td><td>Take the 2nd right.</td><td nowrap="">n % 10 = 2 and<br>&nbsp;&nbsp;n % 100 != 12</td></tr>
	<tr><td>few</td><td>3, 23, 33, 43, 53, 63, 73, 83, 103, 1003, …</td><td>Take the 3rd right.</td><td nowrap="">n % 10 = 3 and<br>&nbsp;&nbsp;n % 100 != 13</td></tr>
	<tr><td>other</td><td>0, 4~18, 100, 1000, 10000, 100000, 1000000, …</td><td>Take the 4th right.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1–2 days</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 days</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 days</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Esperanto</td><td rowspan="3"><a name="eo" href="#eo">eo</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Estonian</td><td rowspan="6"><a name="et" href="#et">et</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 ööpäev</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 ööpäeva<br>1,5 ööpäeva</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Tehke 15.<br>parempööre.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1‒2 ööpäeva</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0‒1 ööpäeva</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0‒2 ööpäeva</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="5">European Portuguese</td><td rowspan="5"><a name="pt_PT" href="#pt_PT">pt_PT</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 ponto</td><td nowrap="">n = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 pontos<br>1,5 pontos</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1 - 2 pontos</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0 - 1 ponto</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0 - 2 pontos</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Ewe</td><td rowspan="3"><a name="ee" href="#ee">ee</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Faroese</td><td rowspan="3"><a name="fo" href="#fo">fo</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="8">Filipino</td><td rowspan="8"><a name="fil" href="#fil">fil</a></td><td rowspan="2">cardinal</td><td>one</td><td>0~3, 5, 7, 8, 10~13, 15, 17, 18, 20, 21, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.3, 0.5, 0.7, 0.8, 1.0~1.3, 1.5, 1.7, 1.8, 2.0, 2.1, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>3 mansanas<br>0.3 mansanas</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i = 1,2,3 or<br>v = 0 and<br>&nbsp;&nbsp;i % 10 != 4,6,9 or<br>v != 0 and<br>&nbsp;&nbsp;f % 10 != 4,6,9</td></tr>
	<tr><td>other</td><td>4, 6, 9, 14, 16, 19, 24, 26, 104, 1004, …<br>0.4, 0.6, 0.9, 1.4, 1.6, 1.9, 2.4, 2.6, 10.4, 100.4, 1000.4, …</td><td>4 na mansanas<br>0.4 na mansanas</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1</td><td>Lumiko sa unang kanan.</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …</td><td>Lumiko sa ika-2 kanan.</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">range</td><td>one+one</td><td>0–5</td><td>0-5 mansanas</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–4</td><td>0-4 na mansanas</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0.4–5</td><td>0.4-5 mansanas</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0.4–4</td><td>0.4-4 na mansanas</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Finnish</td><td rowspan="6"><a name="fi" href="#fi">fi</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 päivä</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 päivää<br>1,5 päivää</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Käänny 15.<br>risteyksestä oikealle.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1‒2 päivää</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0‒1 päivää</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0‒2 päivää</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">French</td><td rowspan="7"><a name="fr" href="#fr">fr</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.5</td><td>1 jour<br>1,5 jour</td><td nowrap="">i = 0,1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>2.0~3.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 jours<br>2,0 jours</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1</td><td>Prenez la 1re à droite.</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …</td><td>Prenez la 2e à droite.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>0–1 jour</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>0–2 jours</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>2–100</td><td>2–100 jours</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Friulian</td><td rowspan="3"><a name="fur" href="#fur">fur</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Fulah</td><td rowspan="3"><a name="ff" href="#ff">ff</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.5</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">i = 0,1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>2.0~3.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Galician</td><td rowspan="6"><a name="gl" href="#gl">gl</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 día</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 días<br>1,5 días</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Colle a 15.ª curva á dereita.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1–2 días</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 día</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 días</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Ganda</td><td rowspan="3"><a name="lg" href="#lg">lg</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="8">Georgian</td><td rowspan="8"><a name="ka" href="#ka">ka</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>კალათში 1 X-ია.<br>შეიძენთ მას?<br>კალათში 1,0 X-ია.<br>შეიძენთ მას?</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>კალათში 2 X-ია.<br>შეიძენთ მათ?<br>კალათში 0,9 X-ია.<br>შეიძენთ მათ?</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">ordinal</td><td>one</td><td>1</td><td>1-ლი</td><td nowrap="">i = 1</td></tr>
	<tr><td>many</td><td>0, 2~16, 102, 1002, …</td><td>მე-2</td><td nowrap="">i = 0 or<br>i % 100 = 2..20,40,60,80</td></tr>
	<tr><td>other</td><td>21~36, 100, 1000, 10000, 100000, 1000000, …</td><td>21-ე</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>კალათში 1-2 X-ია.<br>შეიძენთ მას?</td><td nowrap="">one + other → one</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>კალათში 0-1 X-ია.<br>შეიძენთ მათ?</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>კალათში 0-2 X-ია.<br>შეიძენთ მათ?</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">German</td><td rowspan="6"><a name="de" href="#de">de</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 Tag</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 Tage<br>1,5 Tage</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15.<br>Abzweigung nach rechts nehmen</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1–2 Tage</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 Tag</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 Tage</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Greek</td><td rowspan="6"><a name="el" href="#el">el</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 ημέρα<br>1,0 ημέρα</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 ημέρες<br>0,9 ημέρες</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Στρίψτε στην 15η γωνία δεξιά.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1–2 ημέρες</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 ημέρα</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 ημέρες</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="10">Gujarati</td><td rowspan="10"><a name="gu" href="#gu">gu</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td>1 કિલોગ્રામ<br>1.0 કિલોગ્રામ</td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 કિલોગ્રામ્સ<br>1.1 કિલોગ્રામ્સ</td><td nowrap=""></td></tr>
	<tr><td rowspan="5">ordinal</td><td>one</td><td>1</td><td>જમણી બાજુએ 1લો વળાંક લો.</td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2, 3</td><td>જમણી બાજુએ 2જો વળાંક લો.</td><td nowrap="">n = 2,3</td></tr>
	<tr><td>few</td><td>4</td><td>જમણી બાજુએ 4થો વળાંક લો.</td><td nowrap="">n = 4</td></tr>
	<tr><td>many</td><td>6</td><td>જમણી બાજુએ 6ઠો વળાંક લો.</td><td nowrap="">n = 6</td></tr>
	<tr><td>other</td><td>0, 5, 7~20, 100, 1000, 10000, 100000, 1000000, …</td><td>જમણી બાજુએ 5મો વળાંક લો.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>0-1 કિલોગ્રામ</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>0-2 કિલોગ્રામ્સ</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>1.1–2</td><td>1.1-2 કિલોગ્રામ્સ</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Gun</td><td rowspan="3"><a name="guw" href="#guw">guw</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 0..1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Hausa</td><td rowspan="3"><a name="ha" href="#ha">ha</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Hawaiian</td><td rowspan="3"><a name="haw" href="#haw">haw</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="17">Hebrew</td><td rowspan="16"><a name="he" href="#he">he</a></td><td rowspan="4">cardinal</td><td>one</td><td>1</td><td>&#8235;שנה&#8236;</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>two</td><td>2</td><td>&#8235;שנתיים&#8236;</td><td nowrap="">i = 2 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>many</td><td>20, 30, 40, 50, 60, 70, 80, 90, 100, 1000, 10000, 100000, 1000000, …</td><td>&#8235;20 שנה&#8236;</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;n != 0..10 and<br>&nbsp;&nbsp;n % 10 = 0</td></tr>
	<tr><td>other</td><td>0, 3~17, 101, 1001, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>&#8235;3 שנים<br>1.5 שנים&#8236;</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>&#8235;פנה ימינה בפנייה ה-15&#8236;</td><td nowrap=""></td></tr>
	<tr><td rowspan="11">range</td><td>one+two</td><td>1–2</td><td>&#8235;1–2 שנים&#8236;</td><td nowrap="">one + two → other</td></tr>
	<tr><td>one+many</td><td>1–20</td><td>&#8235;1–20 שנה&#8236;</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–3</td><td>&#8235;1–3 שנים&#8236;</td><td nowrap="">one + other → other</td></tr>
	<tr><td>two+many</td><td>2–20</td><td>&#8235;2–20 שנים&#8236;</td><td nowrap="">two + many → other</td></tr>
	<tr><td>two+other</td><td>2–3</td><td>&#8235;2–3 שנים&#8236;</td><td nowrap="">two + other → other</td></tr>
	<tr><td>many+many</td><td>20–30</td><td>&#8235;20–30 שנה&#8236;</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>20–101</td><td>&#8235;20–101 שנה&#8236;</td><td nowrap="">many + other → many</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>&#8235;0–1 שנים&#8236;</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+two</td><td>0–2</td><td>&#8235;0–2 שנים&#8236;</td><td nowrap="">other + two → other</td></tr>
	<tr><td>other+many</td><td>0–20</td><td>&#8235;0–20 שנה&#8236;</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0–3</td><td>&#8235;0–3 שנים&#8236;</td><td nowrap="">other + other → other</td></tr>
	<tr><td><a name="iw" href="#iw">iw</a></td><td><i>=<a href="#he">he</a></i></td><td><i>=<a href="#he">he</a></i></td><td><i>=<a href="#he">he</a></i></td><td><i>=<a href="#he">he</a></i></td><td nowrap=""><i>=<a href="#he">he</a></i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="10">Hindi</td><td rowspan="10"><a name="hi" href="#hi">hi</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td>1 घंटा<br>1.0 घंटा</td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 घंटे<br>1.1 घंटे</td><td nowrap=""></td></tr>
	<tr><td rowspan="5">ordinal</td><td>one</td><td>1</td><td>1ला दाहिना मोड़ लें.</td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2, 3</td><td>2रा दाहिना मोड़ लें.</td><td nowrap="">n = 2,3</td></tr>
	<tr><td>few</td><td>4</td><td>4था दाहिना मोड़ लें.</td><td nowrap="">n = 4</td></tr>
	<tr><td>many</td><td>6</td><td>6ठा दाहिना मोड़ लें.</td><td nowrap="">n = 6</td></tr>
	<tr><td>other</td><td>0, 5, 7~20, 100, 1000, 10000, 100000, 1000000, …</td><td>5वां दाहिना मोड़ लें.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>0–1 घंटा</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>0–2 घंटे</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>1.1–2</td><td>1.1–2 घंटे</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Hungarian</td><td rowspan="7"><a name="hu" href="#hu">hu</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>A kosár tartalma: 1 X.<br>Megveszi?<br>A kosár tartalma: 1,0 X.<br>Megveszi?</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>A kosár tartalma: 2 X.<br>Megveszi őket?<br>A kosár tartalma: 0,9 X.<br>Megveszi őket?</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1, 5</td><td>Az 1.<br>lehetőségnél forduljon jobbra.</td><td nowrap="">n = 1,5</td></tr>
	<tr><td>other</td><td>0, 2~4, 6~17, 100, 1000, 10000, 100000, 1000000, …</td><td>A 2.<br>lehetőségnél forduljon jobbra.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>A kosár tartalma: 1–2 X.<br>Megveszi őket?</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>A kosár tartalma: 0–1 X.<br>Megveszi?</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>A kosár tartalma: 0–2 X.<br>Megveszi őket?</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Icelandic</td><td rowspan="7"><a name="is" href="#is">is</a></td><td rowspan="2">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …<br>0.1~1.6, 10.1, 100.1, 1000.1, …</td><td>1 dagur<br>0,1 dagur</td><td nowrap="">t = 0 and<br>&nbsp;&nbsp;i % 10 = 1 and<br>&nbsp;&nbsp;i % 100 != 11 or<br>t != 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 dagar<br>2,0 dagar</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Taktu 15.<br>beygju til hægri.</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">range</td><td>one+one</td><td>0.1–1</td><td>0,1–1 dagur</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0.1–2</td><td>0,1–2 dagar</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 dagur</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 dagar</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Igbo</td><td rowspan="2"><a name="ig" href="#ig">ig</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Inari Sami</td><td rowspan="4"><a name="smn" href="#smn">smn</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Indonesian</td><td rowspan="3"><a name="id" href="#id">id</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15 hari<br>1,5 hari</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Ambil belokan kanan ke-15.</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0–100 hari</td><td nowrap="">other + other → other</td></tr>
	<tr><td><a name="in" href="#in">in</a></td><td><i>=<a href="#id">id</a></i></td><td><i>=<a href="#id">id</a></i></td><td><i>=<a href="#id">id</a></i></td><td><i>=<a href="#id">id</a></i></td><td nowrap=""><i>=<a href="#id">id</a></i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Inuktitut</td><td rowspan="4"><a name="iu" href="#iu">iu</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="24">Irish</td><td rowspan="24"><a name="ga" href="#ga">ga</a></td><td rowspan="5">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 ci, 1 gath<br>1.0 ci, 1.0 gath</td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td>2 gi, 2 gath<br>2.0 gi, 2.0 gath</td><td nowrap="">n = 2</td></tr>
	<tr><td>few</td><td>3~6<br>3.0, 4.0, 5.0, 6.0, 3.00, 4.00, 5.00, 6.00, 3.000, 4.000, 5.000, 6.000, 3.0000, 4.0000, 5.0000, 6.0000</td><td>3 chi, 3 cath<br>3.0 chi, 3.0 cath</td><td nowrap="">n = 3..6</td></tr>
	<tr><td>many</td><td>7~10<br>7.0, 8.0, 9.0, 10.0, 7.00, 8.00, 9.00, 10.00, 7.000, 8.000, 9.000, 10.000, 7.0000, 8.0000, 9.0000, 10.0000</td><td>7 chi, 7 chath<br>7.0 chi, 7.0 chath</td><td nowrap="">n = 7..10</td></tr>
	<tr><td>other</td><td>0, 11~25, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.1, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>11 ci, 11 cath<br>0.9 ci, 0.9 cath</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1</td><td>Glac an 1ú chasadh ar dheis.</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …</td><td>Glac an 2ú casadh ar dheis.</td><td nowrap=""></td></tr>
	<tr><td rowspan="17">range</td><td>one+two</td><td>1–2</td><td>1–2 gi, 1–2 gath</td><td nowrap="">one + two → two</td></tr>
	<tr><td>one+few</td><td>1–3</td><td>1–3 chi, 1–3 cath</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–7</td><td>1–7 chi, 1–7 chath</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–11</td><td>1–11 ci, 1–11 cath</td><td nowrap="">one + other → other</td></tr>
	<tr><td>two+few</td><td>2–3</td><td>2–3 chi, 2–3 cath</td><td nowrap="">two + few → few</td></tr>
	<tr><td>two+many</td><td>2–7</td><td>2–7 chi, 2–7 chath</td><td nowrap="">two + many → many</td></tr>
	<tr><td>two+other</td><td>2–11</td><td>2–11 ci, 2–11 cath</td><td nowrap="">two + other → other</td></tr>
	<tr><td>few+few</td><td>3–6</td><td>3–6 chi, 3–6 cath</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>3–7</td><td>3–7 chi, 3–7 chath</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>3–11</td><td>3–11 ci, 3–11 cath</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+many</td><td>7–10</td><td>7–10 chi, 7–10 chath</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>7–11</td><td>7–11 ci, 7–11 cath</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 ci, 0–1 gath</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+two</td><td>0–2</td><td>0–2 gi, 0–2 gath</td><td nowrap="">other + two → two</td></tr>
	<tr><td>other+few</td><td>0–3</td><td>0–3 chi, 0–3 cath</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0–7</td><td>0–7 chi, 0–7 chath</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0–11</td><td>0–11 ci, 0–11 cath</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Italian</td><td rowspan="7"><a name="it" href="#it">it</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>1 giorno</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 giorni<br>1,5 giorni</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>many</td><td>8, 11, 80, 800</td><td>Prendi l'8° a destra.</td><td nowrap="">n = 11,8,80,800</td></tr>
	<tr><td>other</td><td>0~7, 9, 10, 12~17, 100, 1000, 10000, 100000, 1000000, …</td><td>Prendi la 7° a destra.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1-2 giorni</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0-1 giorno</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0-2 giorni</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Japanese</td><td rowspan="3"><a name="ja" href="#ja">ja</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15日<br>1.5日</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15 番目の角を右折します。</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0～100日</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Javanese</td><td rowspan="2"><a name="jv" href="#jv">jv</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><td><a name="jw" href="#jw">jw</a></td><td><i>=<a href="#jv">jv</a></i></td><td><i>=<a href="#jv">jv</a></i></td><td><i>=<a href="#jv">jv</a></i></td><td><i>=<a href="#jv">jv</a></i></td><td nowrap=""><i>=<a href="#jv">jv</a></i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Jju</td><td rowspan="3"><a name="kaj" href="#kaj">kaj</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Kabuverdianu</td><td rowspan="2"><a name="kea" href="#kea">kea</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Kabyle</td><td rowspan="3"><a name="kab" href="#kab">kab</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.5</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">i = 0,1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>2.0~3.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Kako</td><td rowspan="3"><a name="kkj" href="#kkj">kkj</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Kalaallisut</td><td rowspan="3"><a name="kl" href="#kl">kl</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 Ulloq<br>1,0 Ulloq</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 Ullut<br>0,9 Ullut</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Kannada</td><td rowspan="6"><a name="kn" href="#kn">kn</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td>1 ದಿನ<br>1.0 ದಿನ</td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 ದಿನಗಳು<br>1.1 ದಿನಗಳು</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15ನೇ ಬಲತಿರುವನ್ನು ತೆಗೆದುಕೊಳ್ಳಿ.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>0–1 ದಿನ</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>0–2 ದಿನಗಳು</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>1.1–2</td><td>1.1–2 ದಿನಗಳು</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Kashmiri</td><td rowspan="3"><a name="ks" href="#ks">ks</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Kazakh</td><td rowspan="7"><a name="kk" href="#kk">kk</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>Cебетте 1 Х бар.<br>Ол сіздікі ме?<br>Cебетте 1,0 Х бар.<br>Ол сіздікі ме?</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>Себетте 2 Х бар.<br>Олар сіздікі ме?<br>Себетте 0,9 Х бар.<br>Олар сіздікі ме?</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>many</td><td>6, 9, 10, 16, 19, 20, 26, 29, 30, 36, 39, 40, 100, 1000, 10000, 100000, 1000000, …</td><td>6-ші бұрылыстан оңға бұрылыңыз.</td><td nowrap="">n % 10 = 6 or<br>n % 10 = 9 or<br>n % 10 = 0 and<br>&nbsp;&nbsp;n != 0</td></tr>
	<tr><td>other</td><td>0~5, 7, 8, 11~15, 17, 18, 21, 101, 1001, …</td><td>5-шы бұрылыстан оңға бұрылыңыз.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>Себетте 1–2 Х бар.<br>Олар сіздікі ме?</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>Cебетте 0–1 Х бар.<br>Ол сіздікі ме?</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>Себетте 0–2 Х бар.<br>Олар сіздікі ме?</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Khmer</td><td rowspan="3"><a name="km" href="#km">km</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15 ថ្ងៃ<br>1,5 ថ្ងៃ</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>បត់&#8203;ស្តាំ&#8203;លើក&#8203;ទី&#8203; 15</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0–100 ថ្ងៃ</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Korean</td><td rowspan="3"><a name="ko" href="#ko">ko</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15일<br>1.5일</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15번째 길목에서 우회전하세요.</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0~100일</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Koyraboro Senni</td><td rowspan="2"><a name="ses" href="#ses">ses</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Kurdish</td><td rowspan="3"><a name="ku" href="#ku">ku</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Kyrgyz</td><td rowspan="6"><a name="ky" href="#ky">ky</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>Себетте 1 Х бар.<br>Аны аласызбы?<br>Себетте 1,0 Х бар.<br>Аны аласызбы?</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>Себетте 2 Х бар.<br>Аларды аласызбы?<br>Себетте 0,9 Х бар.<br>Аларды аласызбы?</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15-бурулуштан оңго бурулуңуз.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>Себетте 1–2 Х бар.<br>Аларды аласызбы?</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>Себетте 0–1 Х бар.<br>Аны аласызбы?</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>Себетте 0–2 Х бар.<br>Аларды аласызбы?</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Lakota</td><td rowspan="2"><a name="lkt" href="#lkt">lkt</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Langi</td><td rowspan="4"><a name="lag" href="#lag">lag</a></td><td rowspan="3">cardinal</td><td>zero</td><td>0<br>0.0, 0.00, 0.000, 0.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 0</td></tr>
	<tr><td>one</td><td>1<br>0.1~1.6</td><td nowrap="">i = 0,1 and<br>&nbsp;&nbsp;n != 0</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>2.0~3.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Lao</td><td rowspan="4"><a name="lo" href="#lo">lo</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15 ມື້<br>1,5 ມື້</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1</td><td>ລ້ຽວຂວາທຳອິດ.</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …</td><td>ລ້ຽວຂວາທີ 2.</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0–100 ມື້</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="13">Latvian</td><td rowspan="13"><a name="lv" href="#lv">lv</a></td><td rowspan="3">cardinal</td><td>zero</td><td>0, 10~20, 30, 40, 50, 60, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 10.0, 11.0, 12.0, 13.0, 14.0, 15.0, 16.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>10 diennakšu<br>10,0 diennakšu</td><td nowrap="">n % 10 = 0 or<br>n % 100 = 11..19 or<br>v = 2 and<br>&nbsp;&nbsp;f % 100 = 11..19</td></tr>
	<tr><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …<br>0.1, 1.0, 1.1, 2.1, 3.1, 4.1, 5.1, 6.1, 7.1, 10.1, 100.1, 1000.1, …</td><td>1 diennakts<br>0,1 diennakts</td><td nowrap="">n % 10 = 1 and<br>&nbsp;&nbsp;n % 100 != 11 or<br>v = 2 and<br>&nbsp;&nbsp;f % 10 = 1 and<br>&nbsp;&nbsp;f % 100 != 11 or<br>v != 2 and<br>&nbsp;&nbsp;f % 10 = 1</td></tr>
	<tr><td>other</td><td>2~9, 22~29, 102, 1002, …<br>0.2~0.9, 1.2~1.9, 10.2, 100.2, 1000.2, …</td><td>2 diennaktis<br>0,2 diennaktis</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Dodieties 15.<br>pagriezienā pa labi.</td><td nowrap=""></td></tr>
	<tr><td rowspan="9">range</td><td>zero+zero</td><td>0–10</td><td>0–10 diennaktis</td><td nowrap="">zero + zero → other</td></tr>
	<tr><td>zero+one</td><td>0–1</td><td>0–1 diennakts</td><td nowrap="">zero + one → one</td></tr>
	<tr><td>zero+other</td><td>0–2</td><td>0–2 diennaktis</td><td nowrap="">zero + other → other</td></tr>
	<tr><td>one+zero</td><td>0.1–10</td><td>0,1–10 diennaktis</td><td nowrap="">one + zero → other</td></tr>
	<tr><td>one+one</td><td>0.1–1</td><td>0,1–1 diennakts</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0.1–2</td><td>0,1–2 diennaktis</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+zero</td><td>0.2–10</td><td>0,2–10 diennaktis</td><td nowrap="">other + zero → other</td></tr>
	<tr><td>other+one</td><td>0.2–1</td><td>0,2–1 diennakts</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0.2–2</td><td>0,2–2 diennaktis</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Lingala</td><td rowspan="3"><a name="ln" href="#ln">ln</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 0..1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="21">Lithuanian</td><td rowspan="21"><a name="lt" href="#lt">lt</a></td><td rowspan="4">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …<br>1.0, 21.0, 31.0, 41.0, 51.0, 61.0, 71.0, 81.0, 101.0, 1001.0, …</td><td>1 obuolys<br>1,0 obuolys</td><td nowrap="">n % 10 = 1 and<br>&nbsp;&nbsp;n % 100 != 11..19</td></tr>
	<tr><td>few</td><td>2~9, 22~29, 102, 1002, …<br>2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 22.0, 102.0, 1002.0, …</td><td>2 obuoliai<br>2,0 obuoliai</td><td nowrap="">n % 10 = 2..9 and<br>&nbsp;&nbsp;n % 100 != 11..19</td></tr>
	<tr><td>many</td><td>0.1~0.9, 1.1~1.7, 10.1, 100.1, 1000.1, …</td><td>0,1 obuolio</td><td nowrap="">f != 0</td></tr>
	<tr><td>other</td><td>0, 10~20, 30, 40, 50, 60, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 10.0, 11.0, 12.0, 13.0, 14.0, 15.0, 16.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>10 obuolių<br>10,0 obuolių</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15-ame posūkyje sukite į dešinę.</td><td nowrap=""></td></tr>
	<tr><td rowspan="16">range</td><td>one+one</td><td>1–21</td><td>1–21 obuolys</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+few</td><td>1–2</td><td>1–2 obuoliai</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–1.1</td><td>1–1,1 obuolio</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–10</td><td>1–10 obuolių</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+one</td><td>2–21</td><td>2–21 obuolys</td><td nowrap="">few + one → one</td></tr>
	<tr><td>few+few</td><td>2–22</td><td>2–22 obuoliai</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>2–10.1</td><td>2–10,1 obuolio</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>2–10</td><td>2–10 obuolių</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+one</td><td>0.1–1</td><td>0,1–1 obuolys</td><td nowrap="">many + one → one</td></tr>
	<tr><td>many+few</td><td>0.1–2</td><td>0,1–2 obuoliai</td><td nowrap="">many + few → few</td></tr>
	<tr><td>many+many</td><td>0.1–1.1</td><td>0,1–1,1 obuolio</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>0.1–10</td><td>0,1–10 obuolių</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 obuolys</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0–2</td><td>0–2 obuoliai</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0–0.1</td><td>0–0,1 obuolio</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0–10</td><td>0–10 obuolių</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Lojban</td><td rowspan="2"><a name="jbo" href="#jbo">jbo</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Lower Sorbian</td><td rowspan="6"><a name="dsb" href="#dsb">dsb</a></td><td rowspan="4">cardinal</td><td>one</td><td>1, 101, 201, 301, 401, 501, 601, 701, 1001, …<br>0.1, 1.1, 2.1, 3.1, 4.1, 5.1, 6.1, 7.1, 10.1, 100.1, 1000.1, …</td><td rowspan="4"><i>Not available.</i></td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 1 or<br>f % 100 = 1</td></tr>
	<tr><td>two</td><td>2, 102, 202, 302, 402, 502, 602, 702, 1002, …<br>0.2, 1.2, 2.2, 3.2, 4.2, 5.2, 6.2, 7.2, 10.2, 100.2, 1000.2, …</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 2 or<br>f % 100 = 2</td></tr>
	<tr><td>few</td><td>3, 4, 103, 104, 203, 204, 303, 304, 403, 404, 503, 504, 603, 604, 703, 704, 1003, …<br>0.3, 0.4, 1.3, 1.4, 2.3, 2.4, 3.3, 3.4, 4.3, 4.4, 5.3, 5.4, 6.3, 6.4, 7.3, 7.4, 10.3, 100.3, 1000.3, …</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 3..4 or<br>f % 100 = 3..4</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 0.5~1.0, 1.5~2.0, 2.5~2.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Lule Sami</td><td rowspan="4"><a name="smj" href="#smj">smj</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Luxembourgish</td><td rowspan="3"><a name="lb" href="#lb">lb</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="10">Macedonian</td><td rowspan="10"><a name="mk" href="#mk">mk</a></td><td rowspan="2">cardinal</td><td>one</td><td>1, 11, 21, 31, 41, 51, 61, 71, 101, 1001, …<br>0.1, 1.1, 2.1, 3.1, 4.1, 5.1, 6.1, 7.1, 10.1, 100.1, 1000.1, …</td><td>1 ден<br>0,1 ден</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 1 or<br>f % 10 = 1</td></tr>
	<tr><td>other</td><td>0, 2~10, 12~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 0.2~1.0, 1.2~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 дена<br>0,2 дена</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">ordinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …</td><td>Сврти на 1-вата улица десно.</td><td nowrap="">i % 10 = 1 and<br>&nbsp;&nbsp;i % 100 != 11</td></tr>
	<tr><td>two</td><td>2, 22, 32, 42, 52, 62, 72, 82, 102, 1002, …</td><td>Сврти на 2-рата улица десно.</td><td nowrap="">i % 10 = 2 and<br>&nbsp;&nbsp;i % 100 != 12</td></tr>
	<tr><td>many</td><td>7, 8, 27, 28, 37, 38, 47, 48, 57, 58, 67, 68, 77, 78, 87, 88, 107, 1007, …</td><td>Сврти на 7-мата улица десно.</td><td nowrap="">i % 10 = 7,8 and<br>&nbsp;&nbsp;i % 100 != 17,18</td></tr>
	<tr><td>other</td><td>0, 3~6, 9~19, 100, 1000, 10000, 100000, 1000000, …</td><td>Сврти на 3-тата улица десно.</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">range</td><td>one+one</td><td>0.1–1</td><td>0,1–1 дена</td><td nowrap="">one + one → other</td></tr>
	<tr><td>one+other</td><td>0.1–2</td><td>0,1–2 дена</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 дена</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 дена</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Machame</td><td rowspan="3"><a name="jmc" href="#jmc">jmc</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Makonde</td><td rowspan="2"><a name="kde" href="#kde">kde</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Malagasy</td><td rowspan="3"><a name="mg" href="#mg">mg</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 0..1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Malay</td><td rowspan="4"><a name="ms" href="#ms">ms</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15 hari<br>1.5 hari</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1</td><td>Ambil belokan kanan yang pertama.</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …</td><td>Ambil belokan kanan yang ke-2.</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0–100 hari</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Malayalam</td><td rowspan="6"><a name="ml" href="#ml">ml</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 വ്യക്തി<br>1.0 വ്യക്തി</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 വ്യക്തികൾ<br>0.9 വ്യക്തികൾ</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15-ാമത്തെ വലത്തേക്ക് തിരിയുക.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1-2 വ്യക്തികൾ</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0-1 വ്യക്തി</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0-2 വ്യക്തികൾ</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="5">Maltese</td><td rowspan="5"><a name="mt" href="#mt">mt</a></td><td rowspan="4">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="4"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>few</td><td>0, 2~10, 102~107, 1002, …<br>0.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 10.0, 102.0, 1002.0, …</td><td nowrap="">n = 0 or<br>n % 100 = 2..10</td></tr>
	<tr><td>many</td><td>11~19, 111~117, 1011, …<br>11.0, 12.0, 13.0, 14.0, 15.0, 16.0, 17.0, 18.0, 111.0, 1011.0, …</td><td nowrap="">n % 100 = 11..19</td></tr>
	<tr><td>other</td><td>20~35, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.1, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Manx</td><td rowspan="6"><a name="gv" href="#gv">gv</a></td><td rowspan="5">cardinal</td><td>one</td><td>1, 11, 21, 31, 41, 51, 61, 71, 101, 1001, …</td><td>1 thunnag/vuc/ooyl</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 1</td></tr>
	<tr><td>two</td><td>2, 12, 22, 32, 42, 52, 62, 72, 102, 1002, …</td><td>2 hunnag/vuc/ooyl</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 2</td></tr>
	<tr><td>few</td><td>0, 20, 40, 60, 80, 100, 120, 140, 1000, 10000, 100000, 1000000, …</td><td>20 thunnag/muc/ooyl</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 0,20,40,60,80</td></tr>
	<tr><td>many</td><td>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>1.5 dy hunnagyn/dy vucyn/dy ooylyn</td><td nowrap="">v != 0</td></tr>
	<tr><td>other</td><td>3~10, 13~19, 23, 103, 1003, …</td><td>3 thunnagyn/mucyn/ooylyn</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="9">Marathi</td><td rowspan="9"><a name="mr" href="#mr">mr</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td>१ घर<br>१.० घर</td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>२ घरे<br>१.१ घरे</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">ordinal</td><td>one</td><td>1</td><td>१ले उजवे वळण घ्या.</td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2, 3</td><td>२रे उजवे वळण घ्या.</td><td nowrap="">n = 2,3</td></tr>
	<tr><td>few</td><td>4</td><td>४थे उजवे वळण घ्या.</td><td nowrap="">n = 4</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>५वे उजवे वळण घ्या.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>०–१ घर</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>०–२ घरे</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>1.1–2</td><td>१.१–२ घरे</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Masai</td><td rowspan="3"><a name="mas" href="#mas">mas</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Metaʼ</td><td rowspan="3"><a name="mgo" href="#mgo">mgo</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td>Moldavian</td><td><a name="mo" href="#mo">mo</a></td><td><i>=<a href="#ro_MD">ro_MD</a></i></td><td><i>=<a href="#ro_MD">ro_MD</a></i></td><td><i>=<a href="#ro_MD">ro_MD</a></i></td><td><i>=<a href="#ro_MD">ro_MD</a></i></td><td nowrap=""><i>=<a href="#ro_MD">ro_MD</a></i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Mongolian</td><td rowspan="6"><a name="mn" href="#mn">mn</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>Картанд 1 Х байна.<br>Үүнийг авах уу?<br>Картанд 1.0 Х байна.<br>Үүнийг авах уу?</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>Картанд 2 Х байна.<br>Тэднийг авах уу?<br>Картанд 0.9 Х байна.<br>Тэднийг авах уу?</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15-р баруун эргэлтээр орно уу</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>Картанд 1–2 Х байна.<br>Тэднийг авах уу?</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>Картанд 0–1 Х байна.<br>Үүнийг авах уу?</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>Картанд 0–2 Х байна.<br>Тэднийг авах уу?</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">N’Ko</td><td rowspan="2"><a name="nqo" href="#nqo">nqo</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Nahuatl</td><td rowspan="3"><a name="nah" href="#nah">nah</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Najdi Arabic</td><td rowspan="7"><a name="ars" href="#ars">ars</a></td><td rowspan="6">cardinal</td><td>zero</td><td>0<br>0.0, 0.00, 0.000, 0.0000</td><td rowspan="6"><i>Not available.</i></td><td nowrap="">n = 0</td></tr>
	<tr><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>few</td><td>3~10, 103~110, 1003, …<br>3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0, 103.0, 1003.0, …</td><td nowrap="">n % 100 = 3..10</td></tr>
	<tr><td>many</td><td>11~26, 111, 1011, …<br>11.0, 12.0, 13.0, 14.0, 15.0, 16.0, 17.0, 18.0, 111.0, 1011.0, …</td><td nowrap="">n % 100 = 11..99</td></tr>
	<tr><td>other</td><td>100~102, 200~202, 300~302, 400~402, 500~502, 600, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.1, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Nama</td><td rowspan="4"><a name="naq" href="#naq">naq</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Nepali</td><td rowspan="7"><a name="ne" href="#ne">ne</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>तपाईँसँग १ निम्तो छ<br>तपाईँसँग १.० निम्तो छ</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>तपाईँसँग २ निम्ता छन््<br>तपाईँसँग ०.९ निम्ता छन््</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1~4</td><td>१ ओ दायाँ घुम्ति लिनुहोस्</td><td nowrap="">n = 1..4</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>५ औं दायाँ घुम्ति लिनुहोस्</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>तपाईँसँग १–२ निम्ता छन््</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>तपाईँसँग ०–१ निम्तो छ</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>तपाईँसँग ०–२ निम्ता छन््</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Ngiemboon</td><td rowspan="3"><a name="nnh" href="#nnh">nnh</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Ngomba</td><td rowspan="3"><a name="jgo" href="#jgo">jgo</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">North Ndebele</td><td rowspan="3"><a name="nd" href="#nd">nd</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Northern Sami</td><td rowspan="4"><a name="se" href="#se">se</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Northern Sotho</td><td rowspan="3"><a name="nso" href="#nso">nso</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 0..1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td>Norwegian</td><td><a name="no" href="#no">no</a></td><td><i>=<a href="#nb">nb</a></i></td><td><i>=<a href="#nb">nb</a></i></td><td><i>=<a href="#nb">nb</a></i></td><td><i>=<a href="#nb">nb</a></i></td><td nowrap=""><i>=<a href="#nb">nb</a></i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Norwegian Bokmål</td><td rowspan="6"><a name="nb" href="#nb">nb</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 dag<br>1,0 dag</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 dager<br>0,9 dager</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Ta 15.<br>svingen til høyre.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1–2 dager</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 dager</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 dager</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Norwegian Nynorsk</td><td rowspan="3"><a name="nn" href="#nn">nn</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Nyanja</td><td rowspan="3"><a name="ny" href="#ny">ny</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Nyankole</td><td rowspan="3"><a name="nyn" href="#nyn">nyn</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Odia</td><td rowspan="3"><a name="or" href="#or">or</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Oromo</td><td rowspan="3"><a name="om" href="#om">om</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Ossetic</td><td rowspan="3"><a name="os" href="#os">os</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Papiamento</td><td rowspan="3"><a name="pap" href="#pap">pap</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Pashto</td><td rowspan="3"><a name="ps" href="#ps">ps</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Persian</td><td rowspan="6"><a name="fa" href="#fa">fa</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td>&#8235;او ۱ فیلم در هفته می&zwnj;بیند که کمدی است.<br>او ۱٫۰ فیلم در هفته می&zwnj;بیند که کمدی است.&#8236;</td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>&#8235;او ۲ فیلم در هفته می&zwnj;بیند که کمدی هستند.<br>او ۱٫۱ فیلم در هفته می&zwnj;بیند که کمدی هستند.&#8236;</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>&#8235;در پیچ ۱۵ام سمت راست بپیچید.&#8236;</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>&#8235;او ۰–۱ فیلم در هفته می&zwnj;بیند که کمدی هستند.&#8236;</td><td nowrap="">one + one → other</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>&#8235;او ۰–۲ فیلم در هفته می&zwnj;بیند که کمدی هستند.&#8236;</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>1.1–2</td><td>&#8235;او ۱٫۱–۲ فیلم در هفته می&zwnj;بیند که کمدی هستند.&#8236;</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="19">Polish</td><td rowspan="19"><a name="pl" href="#pl">pl</a></td><td rowspan="4">cardinal</td><td>one</td><td>1</td><td>1 miesiąc</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>few</td><td>2~4, 22~24, 32~34, 42~44, 52~54, 62, 102, 1002, …</td><td>2 miesiące</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 2..4 and<br>&nbsp;&nbsp;i % 100 != 12..14</td></tr>
	<tr><td>many</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>5 miesięcy</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i != 1 and<br>&nbsp;&nbsp;i % 10 = 0..1 or<br>v = 0 and<br>&nbsp;&nbsp;i % 10 = 5..9 or<br>v = 0 and<br>&nbsp;&nbsp;i % 100 = 12..14</td></tr>
	<tr><td>other</td><td>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>1,5 miesiąca</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Skręć w 15 w prawo.</td><td nowrap=""></td></tr>
	<tr><td rowspan="14">range</td><td>one+few</td><td>1–2</td><td>1–2 miesiące</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–5</td><td>1–5 miesięcy</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–10.0</td><td>1–10,0 miesiąca</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+few</td><td>2–22</td><td>2–22 miesiące</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>2–5</td><td>2–5 miesięcy</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>2–10.0</td><td>2–10,0 miesiąca</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+one</td><td>0–1</td><td>0–1 miesiąc</td><td nowrap="">many + one → one</td></tr>
	<tr><td>many+few</td><td>0–2</td><td>0–2 miesiące</td><td nowrap="">many + few → few</td></tr>
	<tr><td>many+many</td><td>0–5</td><td>0–5 miesięcy</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>0–10.0</td><td>0–10,0 miesiąca</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0.0–1</td><td>0,0–1 miesiąc</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0.0–2</td><td>0,0–2 miesiące</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0.0–5</td><td>0,0–5 miesięcy</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0.0–10.0</td><td>0,0–10,0 miesiąca</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Portuguese</td><td rowspan="7"><a name="pt" href="#pt">pt</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td>1 ponto<br>1,0 ponto</td><td nowrap="">n = 0..2 and<br>&nbsp;&nbsp;n != 2</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 pontos<br>0,1 pontos</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15º livro</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">range</td><td>one+one</td><td>0–1</td><td>0–1 ponto</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>0–2 pontos</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0.1–1</td><td>0,1–1 ponto</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0.1–2</td><td>0,1–2 pontos</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="5">Prussian</td><td rowspan="5"><a name="prg" href="#prg">prg</a></td><td rowspan="3">cardinal</td><td>zero</td><td>0, 10~20, 30, 40, 50, 60, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 10.0, 11.0, 12.0, 13.0, 14.0, 15.0, 16.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n % 10 = 0 or<br>n % 100 = 11..19 or<br>v = 2 and<br>&nbsp;&nbsp;f % 100 = 11..19</td></tr>
	<tr><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …<br>0.1, 1.0, 1.1, 2.1, 3.1, 4.1, 5.1, 6.1, 7.1, 10.1, 100.1, 1000.1, …</td><td nowrap="">n % 10 = 1 and<br>&nbsp;&nbsp;n % 100 != 11 or<br>v = 2 and<br>&nbsp;&nbsp;f % 10 = 1 and<br>&nbsp;&nbsp;f % 100 != 11 or<br>v != 2 and<br>&nbsp;&nbsp;f % 10 = 1</td></tr>
	<tr><td>other</td><td>2~9, 22~29, 102, 1002, …<br>0.2~0.9, 1.2~1.9, 10.2, 100.2, 1000.2, …</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Punjabi</td><td rowspan="7"><a name="pa" href="#pa">pa</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td>1 ਘੰਟਾ<br>1.0 ਘੰਟਾ</td><td nowrap="">n = 0..1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 ਘੰਟੇ<br>0.1 ਘੰਟੇ</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>ਸਜੇ ਪਾਸੇ 15 ਮੋੜ ਲਵੋ</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">range</td><td>one+one</td><td>0–1</td><td>0–1 ਘੰਟਾ</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>0–2 ਘੰਟੇ</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0.1–1</td><td>0.1–1 ਘੰਟਾ</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0.1–2</td><td>0.1–2 ਘੰਟੇ</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="12">Romanian</td><td rowspan="12"><a name="ro" href="#ro">ro</a></td><td rowspan="3">cardinal</td><td>one</td><td>1</td><td>1 zi</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>few</td><td>0, 2~16, 101, 1001, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 zile<br>1,5 zile</td><td nowrap="">v != 0 or<br>n = 0 or<br>n != 1 and<br>&nbsp;&nbsp;n % 100 = 1..19</td></tr>
	<tr><td>other</td><td>20~35, 100, 1000, 10000, 100000, 1000000, …</td><td>20 de zile</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1</td><td>Faceţi virajul nr.<br>1 la dreapta.</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …</td><td>Faceţi virajul al 2-lea la dreapta.</td><td nowrap=""></td></tr>
	<tr><td rowspan="7">range</td><td>one+few</td><td>1–2</td><td>1 - 2 zile</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+other</td><td>1–20</td><td>1 - 20 de zile</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+one</td><td>0–1</td><td>0 - 1 zile</td><td nowrap="">few + one → few</td></tr>
	<tr><td>few+few</td><td>0–2</td><td>0 - 2 zile</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+other</td><td>0–20</td><td>0 - 20 de zile</td><td nowrap="">few + other → other</td></tr>
	<tr><td>other+few</td><td>20–101</td><td>20 - 101 zile</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+other</td><td>20–100</td><td>20 - 100 de zile</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Romansh</td><td rowspan="3"><a name="rm" href="#rm">rm</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Rombo</td><td rowspan="3"><a name="rof" href="#rof">rof</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="21">Russian</td><td rowspan="21"><a name="ru" href="#ru">ru</a></td><td rowspan="4">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …</td><td>из 1 книги за 1 день</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 1 and<br>&nbsp;&nbsp;i % 100 != 11</td></tr>
	<tr><td>few</td><td>2~4, 22~24, 32~34, 42~44, 52~54, 62, 102, 1002, …</td><td>из 2 книг за 2 дня</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 2..4 and<br>&nbsp;&nbsp;i % 100 != 12..14</td></tr>
	<tr><td>many</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>из 5 книг за 5 дней</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 0 or<br>v = 0 and<br>&nbsp;&nbsp;i % 10 = 5..9 or<br>v = 0 and<br>&nbsp;&nbsp;i % 100 = 11..14</td></tr>
	<tr><td>other</td><td>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>из 1,5 книги за 1,5 дня</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Сверните направо на 15-м перекрестке.</td><td nowrap=""></td></tr>
	<tr><td rowspan="16">range</td><td>one+one</td><td>1–21</td><td>из 1–21 книги за 1–21 день</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+few</td><td>1–2</td><td>из 1–2 книг за 1–2 дня</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–5</td><td>из 1–5 книг за 1–5 дней</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–10.0</td><td>из 1–10,0 книги за 1–10,0 дня</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+one</td><td>2–21</td><td>из 2–21 книги за 2–21 день</td><td nowrap="">few + one → one</td></tr>
	<tr><td>few+few</td><td>2–22</td><td>из 2–22 книг за 2–22 дня</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>2–5</td><td>из 2–5 книг за 2–5 дней</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>2–10.0</td><td>из 2–10,0 книги за 2–10,0 дня</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+one</td><td>0–1</td><td>из 0–1 книги за 0–1 день</td><td nowrap="">many + one → one</td></tr>
	<tr><td>many+few</td><td>0–2</td><td>из 0–2 книг за 0–2 дня</td><td nowrap="">many + few → few</td></tr>
	<tr><td>many+many</td><td>0–5</td><td>из 0–5 книг за 0–5 дней</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>0–10.0</td><td>из 0–10,0 книги за 0–10,0 дня</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0.0–1</td><td>из 0,0–1 книги за 0,0–1 день</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0.0–2</td><td>из 0,0–2 книг за 0,0–2 дня</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0.0–5</td><td>из 0,0–5 книг за 0,0–5 дней</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0.0–10.0</td><td>из 0,0–10,0 книги за 0,0–10,0 дня</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Rwa</td><td rowspan="3"><a name="rwk" href="#rwk">rwk</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Saho</td><td rowspan="3"><a name="ssy" href="#ssy">ssy</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Sakha</td><td rowspan="2"><a name="sah" href="#sah">sah</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Samburu</td><td rowspan="3"><a name="saq" href="#saq">saq</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Sami languages [Other]</td><td rowspan="4"><a name="smi" href="#smi">smi</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Sango</td><td rowspan="2"><a name="sg" href="#sg">sg</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="5">Scottish Gaelic</td><td rowspan="5"><a name="gd" href="#gd">gd</a></td><td rowspan="4">cardinal</td><td>one</td><td>1, 11<br>1.0, 11.0, 1.00, 11.00, 1.000, 11.000, 1.0000</td><td rowspan="4"><i>Not available.</i></td><td nowrap="">n = 1,11</td></tr>
	<tr><td>two</td><td>2, 12<br>2.0, 12.0, 2.00, 12.00, 2.000, 12.000, 2.0000</td><td nowrap="">n = 2,12</td></tr>
	<tr><td>few</td><td>3~10, 13~19<br>3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0, 13.0, 14.0, 15.0, 16.0, 17.0, 18.0, 19.0, 3.00</td><td nowrap="">n = 3..10,13..19</td></tr>
	<tr><td>other</td><td>0, 20~34, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.1, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Sena</td><td rowspan="3"><a name="seh" href="#seh">seh</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="13">Serbian</td><td rowspan="13"><a name="sr" href="#sr">sr</a></td><td rowspan="3">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …<br>0.1, 1.1, 2.1, 3.1, 4.1, 5.1, 6.1, 7.1, 10.1, 100.1, 1000.1, …</td><td>1 сат<br>0,1 сат</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 1 and<br>&nbsp;&nbsp;i % 100 != 11 or<br>f % 10 = 1 and<br>&nbsp;&nbsp;f % 100 != 11</td></tr>
	<tr><td>few</td><td>2~4, 22~24, 32~34, 42~44, 52~54, 62, 102, 1002, …<br>0.2~0.4, 1.2~1.4, 2.2~2.4, 3.2~3.4, 4.2~4.4, 5.2, 10.2, 100.2, 1000.2, …</td><td>2 сата<br>0,2 сата</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 2..4 and<br>&nbsp;&nbsp;i % 100 != 12..14 or<br>f % 10 = 2..4 and<br>&nbsp;&nbsp;f % 100 != 12..14</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 0.5~1.0, 1.5~2.0, 2.5~2.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>5 сати<br>0,5 сати</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Скрените у 15.<br>десно.</td><td nowrap=""></td></tr>
	<tr><td rowspan="9">range</td><td>one+one</td><td>0.1–1</td><td>0,1–1 сат</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+few</td><td>0.1–2</td><td>0,1–2 сата</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+other</td><td>0.1–5</td><td>0,1–5 сати</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+one</td><td>0.2–1</td><td>0,2–1 сат</td><td nowrap="">few + one → one</td></tr>
	<tr><td>few+few</td><td>0.2–2</td><td>0,2–2 сата</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+other</td><td>0.2–5</td><td>0,2–5 сати</td><td nowrap="">few + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 сат</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0–2</td><td>0–2 сата</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+other</td><td>0–5</td><td>0–5 сати</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td>Serbo-Croatian</td><td><a name="sh" href="#sh">sh</a></td><td><i>=<a href="#sr_Latn">sr_Latn</a></i></td><td><i>=<a href="#sr_Latn">sr_Latn</a></i></td><td><i>=<a href="#sr_Latn">sr_Latn</a></i></td><td><i>=<a href="#sr_Latn">sr_Latn</a></i></td><td nowrap=""><i>=<a href="#sr_Latn">sr_Latn</a></i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Shambala</td><td rowspan="3"><a name="ksb" href="#ksb">ksb</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Shona</td><td rowspan="3"><a name="sn" href="#sn">sn</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Sichuan Yi</td><td rowspan="2"><a name="ii" href="#ii">ii</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Sinhala</td><td rowspan="7"><a name="si" href="#si">si</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 0.1, 1.0, 0.00, 0.01, 1.00, 0.000, 0.001, 1.000, 0.0000, 0.0001, 1.0000</td><td>1 පොතක් ඇත.<br>එය කියවීමි.<br>0.1 පොතක් ඇත.<br>එය කියවීමි.</td><td nowrap="">n = 0,1 or<br>i = 0 and<br>&nbsp;&nbsp;f = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.2~0.9, 1.1~1.8, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>පොත් 2ක් ඇත.<br>ඒවා කියවීමි.<br>පොත් 0.2ක් ඇත.<br>ඒවා කියවීමි.</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15 වන හැරවුම දකුණට</td><td nowrap=""></td></tr>
	<tr><td rowspan="4">range</td><td>one+one</td><td>0–1</td><td>0–1 පොතක් ඇත.<br>එය කියවීමි.</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>පොත් 0–2ක් ඇත.<br>ඒවා කියවීමි.</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0.2–1</td><td>පොත් 0.2–1ක් ඇත.<br>ඒවා කියවීමි.</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0.2–2</td><td>පොත් 0.2–2ක් ඇත.<br>ඒවා කියවීමි.</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Skolt Sami</td><td rowspan="4"><a name="sms" href="#sms">sms</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="19">Slovak</td><td rowspan="19"><a name="sk" href="#sk">sk</a></td><td rowspan="4">cardinal</td><td>one</td><td>1</td><td>1 deň</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>few</td><td>2~4</td><td>2 dni</td><td nowrap="">i = 2..4 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>many</td><td>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>1,5 dňa</td><td nowrap="">v != 0</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>5 dní</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Na 15.<br>križovatke odbočte doprava.</td><td nowrap=""></td></tr>
	<tr><td rowspan="14">range</td><td>one+few</td><td>1–2</td><td>1 – 2 dni</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–10.0</td><td>1 – 10,0 dňa</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–5</td><td>1 – 5 dní</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+few</td><td>2–4</td><td>2 – 4 dni</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>2–10.0</td><td>2 – 10,0 dňa</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>2–5</td><td>2 – 5 dní</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+one</td><td>0.0–1</td><td>0,0 – 1 deň</td><td nowrap="">many + one → one</td></tr>
	<tr><td>many+few</td><td>0.0–2</td><td>0,0 – 2 dni</td><td nowrap="">many + few → few</td></tr>
	<tr><td>many+many</td><td>0.0–10.0</td><td>0,0 – 10,0 dňa</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>0.0–5</td><td>0,0 – 5 dní</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0 – 1 deň</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0–2</td><td>0 – 2 dni</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0–10.0</td><td>0 – 10,0 dňa</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0–5</td><td>0 – 5 dní</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="21">Slovenian</td><td rowspan="21"><a name="sl" href="#sl">sl</a></td><td rowspan="4">cardinal</td><td>one</td><td>1, 101, 201, 301, 401, 501, 601, 701, 1001, …</td><td>1 ura</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 1</td></tr>
	<tr><td>two</td><td>2, 102, 202, 302, 402, 502, 602, 702, 1002, …</td><td>2 uri</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 2</td></tr>
	<tr><td>few</td><td>3, 4, 103, 104, 203, 204, 303, 304, 403, 404, 503, 504, 603, 604, 703, 704, 1003, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>3 ure<br>1,5 ure</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 3..4 or<br>v != 0</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>5 ur</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>V 15.<br>križišču zavijte desno.</td><td nowrap=""></td></tr>
	<tr><td rowspan="16">range</td><td>one+one</td><td>1–101</td><td>1–101 ure</td><td nowrap="">one + one → few</td></tr>
	<tr><td>one+two</td><td>1–2</td><td>1–2 uri</td><td nowrap="">one + two → two</td></tr>
	<tr><td>one+few</td><td>1–3</td><td>1–3 ure</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+other</td><td>1–5</td><td>1–5 ur</td><td nowrap="">one + other → other</td></tr>
	<tr><td>two+one</td><td>2–101</td><td>2–101 ure</td><td nowrap="">two + one → few</td></tr>
	<tr><td>two+two</td><td>2–102</td><td>2–102 uri</td><td nowrap="">two + two → two</td></tr>
	<tr><td>two+few</td><td>2–3</td><td>2–3 ure</td><td nowrap="">two + few → few</td></tr>
	<tr><td>two+other</td><td>2–5</td><td>2–5 ur</td><td nowrap="">two + other → other</td></tr>
	<tr><td>few+one</td><td>0.0–1</td><td>0,0–1 ure</td><td nowrap="">few + one → few</td></tr>
	<tr><td>few+two</td><td>0.0–2</td><td>0,0–2 uri</td><td nowrap="">few + two → two</td></tr>
	<tr><td>few+few</td><td>0.0–3</td><td>0,0–3 ure</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+other</td><td>0.0–5</td><td>0,0–5 ur</td><td nowrap="">few + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 ure</td><td nowrap="">other + one → few</td></tr>
	<tr><td>other+two</td><td>0–2</td><td>0–2 uri</td><td nowrap="">other + two → two</td></tr>
	<tr><td>other+few</td><td>0–3</td><td>0–3 ure</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+other</td><td>0–5</td><td>0–5 ur</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Soga</td><td rowspan="3"><a name="xog" href="#xog">xog</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Somali</td><td rowspan="3"><a name="so" href="#so">so</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">South Ndebele</td><td rowspan="3"><a name="nr" href="#nr">nr</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Southern Kurdish</td><td rowspan="3"><a name="sdh" href="#sdh">sdh</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Southern Sami</td><td rowspan="4"><a name="sma" href="#sma">sma</a></td><td rowspan="3">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td nowrap="">n = 2</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Southern Sotho</td><td rowspan="3"><a name="st" href="#st">st</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Spanish</td><td rowspan="6"><a name="es" href="#es">es</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 día<br>1,0 día</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 días<br>0,9 días</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Toma la 15.ª a la derecha.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1-2 días</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0-1 días</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0-2 días</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Swahili</td><td rowspan="6"><a name="sw" href="#sw">sw</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>siku 1 iliyopita</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>siku 2 zilizopita<br>siku 1.5 zilizopita</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Chukua mpinduko wa 15 kulia.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>siku 1–2 zilizopita</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>siku 0–1 iliyopita</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>siku 0–2 zilizopita</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Swati</td><td rowspan="3"><a name="ss" href="#ss">ss</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="7">Swedish</td><td rowspan="7"><a name="sv" href="#sv">sv</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>om 1 dag</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>om 2 dagar<br>om 1,5 dagar</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1, 2, 21, 22, 31, 32, 41, 42, 51, 52, 61, 62, 71, 72, 81, 82, 101, 1001, …</td><td>Ta 1:a svängen till höger</td><td nowrap="">n % 10 = 1,2 and<br>&nbsp;&nbsp;n % 100 != 11,12</td></tr>
	<tr><td>other</td><td>0, 3~17, 100, 1000, 10000, 100000, 1000000, …</td><td>Ta 3:e svängen till höger</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>om 1‒2 dagar</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>om 0‒1 dagar</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>om 0‒2 dagar</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Swiss German</td><td rowspan="3"><a name="gsw" href="#gsw">gsw</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Syriac</td><td rowspan="3"><a name="syr" href="#syr">syr</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Tachelhit</td><td rowspan="4"><a name="shi" href="#shi">shi</a></td><td rowspan="3">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td rowspan="3"><i>Not available.</i></td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>few</td><td>2~10<br>2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0, 2.00, 3.00, 4.00, 5.00, 6.00, 7.00, 8.00</td><td nowrap="">n = 2..10</td></tr>
	<tr><td>other</td><td>11~26, 100, 1000, 10000, 100000, 1000000, …<br>1.1~1.9, 2.1~2.7, 10.1, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td>Tagalog</td><td><a name="tl" href="#tl">tl</a></td><td><i>=<a href="#fil">fil</a></i></td><td><i>=<a href="#fil">fil</a></i></td><td><i>=<a href="#fil">fil</a></i></td><td><i>=<a href="#fil">fil</a></i></td><td nowrap=""><i>=<a href="#fil">fil</a></i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Tamil</td><td rowspan="6"><a name="ta" href="#ta">ta</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 நாள்<br>1.0 நாள்</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 நாட்கள்<br>0.9 நாட்கள்</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15வது வலது திருப்பத்தை எடு.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1–2 நாட்கள்</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 நாள்</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 நாட்கள்</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Telugu</td><td rowspan="6"><a name="te" href="#te">te</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 రోజు<br>1.0 రోజు</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 రోజులు<br>0.9 రోజులు</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15వ కుడి మలుపు తీసుకోండి.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>1–2 రోజులు</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>0–1 రోజు</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>0–2 రోజులు</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Teso</td><td rowspan="3"><a name="teo" href="#teo">teo</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Thai</td><td rowspan="3"><a name="th" href="#th">th</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>15 วัน<br>1.5 วัน</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>เลี้ยวขวาที่ทางเลี้ยวที่ 15</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>0-100 วัน</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Tibetan</td><td rowspan="2"><a name="bo" href="#bo">bo</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Tigre</td><td rowspan="3"><a name="tig" href="#tig">tig</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Tigrinya</td><td rowspan="3"><a name="ti" href="#ti">ti</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 0..1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Tongan</td><td rowspan="2"><a name="to" href="#to">to</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Tsonga</td><td rowspan="3"><a name="ts" href="#ts">ts</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Tswana</td><td rowspan="3"><a name="tn" href="#tn">tn</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Turkish</td><td rowspan="6"><a name="tr" href="#tr">tr</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>Sepetinizde 1 X var.<br>Bunu almak istiyor musunuz?<br>Sepetinizde 1,0 X var.<br>Bunu almak istiyor musunuz?</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>Sepetinizde 2 X var.<br>Bunları almak istiyor musunuz?<br>Sepetinizde 0,9 X var.<br>Bunları almak istiyor musunuz?</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15.<br>sağdan dönün.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>Sepetinizde 1–2 X var.<br>Bunları almak istiyor musunuz?</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>Sepetinizde 0–1 X var.<br>Bunu almak istiyor musunuz?</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>Sepetinizde 0–2 X var.<br>Bunları almak istiyor musunuz?</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Turkmen</td><td rowspan="3"><a name="tk" href="#tk">tk</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Tyap</td><td rowspan="3"><a name="kcg" href="#kcg">kcg</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="22">Ukrainian</td><td rowspan="22"><a name="uk" href="#uk">uk</a></td><td rowspan="4">cardinal</td><td>one</td><td>1, 21, 31, 41, 51, 61, 71, 81, 101, 1001, …</td><td>1 день</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 1 and<br>&nbsp;&nbsp;i % 100 != 11</td></tr>
	<tr><td>few</td><td>2~4, 22~24, 32~34, 42~44, 52~54, 62, 102, 1002, …</td><td>2 дні</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 2..4 and<br>&nbsp;&nbsp;i % 100 != 12..14</td></tr>
	<tr><td>many</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …</td><td>5 днів</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 10 = 0 or<br>v = 0 and<br>&nbsp;&nbsp;i % 10 = 5..9 or<br>v = 0 and<br>&nbsp;&nbsp;i % 100 = 11..14</td></tr>
	<tr><td>other</td><td>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>1,5 дня</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>few</td><td>3, 23, 33, 43, 53, 63, 73, 83, 103, 1003, …</td><td>3-я дивізія, 3-є коло</td><td nowrap="">n % 10 = 3 and<br>&nbsp;&nbsp;n % 100 != 13</td></tr>
	<tr><td>other</td><td>0~2, 4~16, 100, 1000, 10000, 100000, 1000000, …</td><td>2-а дивізія, 2-е коло</td><td nowrap=""></td></tr>
	<tr><td rowspan="16">range</td><td>one+one</td><td>1–21</td><td>1–21 день</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+few</td><td>1–2</td><td>1–2 дні</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–5</td><td>1–5 днів</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–10.0</td><td>1–10,0 дня</td><td nowrap="">one + other → other</td></tr>
	<tr><td>few+one</td><td>2–21</td><td>2–21 день</td><td nowrap="">few + one → one</td></tr>
	<tr><td>few+few</td><td>2–22</td><td>2–22 дні</td><td nowrap="">few + few → few</td></tr>
	<tr><td>few+many</td><td>2–5</td><td>2–5 днів</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>2–10.0</td><td>2–10,0 дня</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+one</td><td>0–1</td><td>0–1 день</td><td nowrap="">many + one → one</td></tr>
	<tr><td>many+few</td><td>0–2</td><td>0–2 дні</td><td nowrap="">many + few → few</td></tr>
	<tr><td>many+many</td><td>0–5</td><td>0–5 днів</td><td nowrap="">many + many → many</td></tr>
	<tr><td>many+other</td><td>0–10.0</td><td>0–10,0 дня</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0.0–1</td><td>0,0–1 день</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+few</td><td>0.0–2</td><td>0,0–2 дні</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0.0–5</td><td>0,0–5 днів</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0.0–10.0</td><td>0,0–10,0 дня</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Upper Sorbian</td><td rowspan="6"><a name="hsb" href="#hsb">hsb</a></td><td rowspan="4">cardinal</td><td>one</td><td>1, 101, 201, 301, 401, 501, 601, 701, 1001, …<br>0.1, 1.1, 2.1, 3.1, 4.1, 5.1, 6.1, 7.1, 10.1, 100.1, 1000.1, …</td><td rowspan="4"><i>Not available.</i></td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 1 or<br>f % 100 = 1</td></tr>
	<tr><td>two</td><td>2, 102, 202, 302, 402, 502, 602, 702, 1002, …<br>0.2, 1.2, 2.2, 3.2, 4.2, 5.2, 6.2, 7.2, 10.2, 100.2, 1000.2, …</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 2 or<br>f % 100 = 2</td></tr>
	<tr><td>few</td><td>3, 4, 103, 104, 203, 204, 303, 304, 403, 404, 503, 504, 603, 604, 703, 704, 1003, …<br>0.3, 0.4, 1.3, 1.4, 2.3, 2.4, 3.3, 3.4, 4.3, 4.4, 5.3, 5.4, 6.3, 6.4, 7.3, 7.4, 10.3, 100.3, 1000.3, …</td><td nowrap="">v = 0 and<br>&nbsp;&nbsp;i % 100 = 3..4 or<br>f % 100 = 3..4</td></tr>
	<tr><td>other</td><td>0, 5~19, 100, 1000, 10000, 100000, 1000000, …<br>0.0, 0.5~1.0, 1.5~2.0, 2.5~2.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Urdu</td><td rowspan="6"><a name="ur" href="#ur">ur</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td>&#8235;1 گھنٹہ&#8236;</td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>&#8235;2 گھنٹے<br>1.5 گھنٹے&#8236;</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>&#8235;دایاں موڑ نمبر 15 مڑیں۔&#8236;</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>&#8235;1–2 گھنٹے&#8236;</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>&#8235;0–1 گھنٹے&#8236;</td><td nowrap="">other + one → other</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>&#8235;0–2 گھنٹے&#8236;</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="5">Uyghur</td><td rowspan="5"><a name="ug" href="#ug">ug</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>&#8235;1  كىتاب<br>1.0  كىتاب&#8236;</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>&#8235;2 بېلىق كۆردۈم ۋە ئۇنى يەۋەتتىم.<br>0.9 بېلىق كۆردۈم ۋە ئۇنى يەۋەتتىم.&#8236;</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>&#8235;1–2 بېلىق كۆردۈم ۋە ئۇنى يەۋەتتىم.&#8236;</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>&#8235;0–1  كىتاب&#8236;</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>&#8235;0–2 بېلىق كۆردۈم ۋە ئۇنى يەۋەتتىم.&#8236;</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Uzbek</td><td rowspan="6"><a name="uz" href="#uz">uz</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>Savatingizda 1X bor.<br>Uni sotib olasizmi?<br>Savatingizda 1,0X bor.<br>Uni sotib olasizmi?</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>Savatingizda 2X bor.<br>Ularni sotib olasizmi?<br>Savatingizda 0,9X bor.<br>Ularni sotib olasizmi?</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>15chi chorraxada o'ngga buriling.</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+other</td><td>1–2</td><td>Savatingizda 1–2X bor.<br>Ularni sotib olasizmi?</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+one</td><td>0–1</td><td>Savatingizda 0–1X bor.<br>Uni sotib olasizmi?</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+other</td><td>0–2</td><td>Savatingizda 0–2X bor.<br>Ularni sotib olasizmi?</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Venda</td><td rowspan="3"><a name="ve" href="#ve">ve</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Vietnamese</td><td rowspan="4"><a name="vi" href="#vi">vi</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>Rẽ vào lối rẽ thứ 15 bên phải.<br>Rẽ vào lối rẽ thứ 1,5 bên phải.</td><td nowrap=""></td></tr>
	<tr><td rowspan="2">ordinal</td><td>one</td><td>1</td><td>Rẽ vào lối rẽ thứ nhất bên phải.</td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …</td><td>Rẽ vào lối rẽ thứ 2 bên phải.</td><td nowrap=""></td></tr>
	<tr><td>range</td><td>other+other</td><td>0–100</td><td>Rẽ vào lối rẽ thứ 0-100 bên phải.</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Volapük</td><td rowspan="3"><a name="vo" href="#vo">vo</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Vunjo</td><td rowspan="3"><a name="vun" href="#vun">vun</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Walloon</td><td rowspan="3"><a name="wa" href="#wa">wa</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0, 1.0, 0.00, 1.00, 0.000, 1.000, 0.0000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 0..1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Walser</td><td rowspan="3"><a name="wae" href="#wae">wae</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="32">Welsh</td><td rowspan="32"><a name="cy" href="#cy">cy</a></td><td rowspan="6">cardinal</td><td>zero</td><td>0<br>0.0, 0.00, 0.000, 0.0000</td><td>0 cŵn, 0 cathod<br>0.0000 cŵn, 0.0000 cathod</td><td nowrap="">n = 0</td></tr>
	<tr><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td>1 ci, 1 gath<br>1.0 ci, 1.0 gath</td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2<br>2.0, 2.00, 2.000, 2.0000</td><td>2 gi, 2 gath<br>2.0 gi, 2.0 gath</td><td nowrap="">n = 2</td></tr>
	<tr><td>few</td><td>3<br>3.0, 3.00, 3.000, 3.0000</td><td>3 chi, 3 cath<br>3.0 chi, 3.0 cath</td><td nowrap="">n = 3</td></tr>
	<tr><td>many</td><td>6<br>6.0, 6.00, 6.000, 6.0000</td><td>6 chi, 6 chath<br>6.0 chi, 6.0 chath</td><td nowrap="">n = 6</td></tr>
	<tr><td>other</td><td>4, 5, 7~20, 100, 1000, 10000, 100000, 1000000, …<br>0.1~0.9, 1.1~1.7, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>4 ci, 4 cath<br>0.1 ci, 0.1 cath</td><td nowrap=""></td></tr>
	<tr><td rowspan="6">ordinal</td><td>zero</td><td>0, 7~9</td><td>7fed ci</td><td nowrap="">n = 0,7,8,9</td></tr>
	<tr><td>one</td><td>1</td><td>ci 1af</td><td nowrap="">n = 1</td></tr>
	<tr><td>two</td><td>2</td><td>2il gi</td><td nowrap="">n = 2</td></tr>
	<tr><td>few</td><td>3, 4</td><td>3ydd ci</td><td nowrap="">n = 3,4</td></tr>
	<tr><td>many</td><td>5, 6</td><td>5ed ci</td><td nowrap="">n = 5,6</td></tr>
	<tr><td>other</td><td>10~25, 100, 1000, 10000, 100000, 1000000, …</td><td>ci rhif 10</td><td nowrap=""></td></tr>
	<tr><td rowspan="20">range</td><td>zero+one</td><td>0–1</td><td>0–1 ci, 0–1 gath</td><td nowrap="">zero + one → one</td></tr>
	<tr><td>zero+two</td><td>0–2</td><td>0–2 gi, 0–2 gath</td><td nowrap="">zero + two → two</td></tr>
	<tr><td>zero+few</td><td>0–3</td><td>0–3 chi, 0–3 cath</td><td nowrap="">zero + few → few</td></tr>
	<tr><td>zero+many</td><td>0–6</td><td>0–6 chi, 0–6 chath</td><td nowrap="">zero + many → many</td></tr>
	<tr><td>zero+other</td><td>0–4</td><td>0–4 ci, 0–4 cath</td><td nowrap="">zero + other → other</td></tr>
	<tr><td>one+two</td><td>1–2</td><td>1–2 gi, 1–2 gath</td><td nowrap="">one + two → two</td></tr>
	<tr><td>one+few</td><td>1–3</td><td>1–3 chi, 1–3 cath</td><td nowrap="">one + few → few</td></tr>
	<tr><td>one+many</td><td>1–6</td><td>1–6 chi, 1–6 chath</td><td nowrap="">one + many → many</td></tr>
	<tr><td>one+other</td><td>1–4</td><td>1–4 ci, 1–4 cath</td><td nowrap="">one + other → other</td></tr>
	<tr><td>two+few</td><td>2–3</td><td>2–3 chi, 2–3 cath</td><td nowrap="">two + few → few</td></tr>
	<tr><td>two+many</td><td>2–6</td><td>2–6 chi, 2–6 chath</td><td nowrap="">two + many → many</td></tr>
	<tr><td>two+other</td><td>2–4</td><td>2–4 ci, 2–4 cath</td><td nowrap="">two + other → other</td></tr>
	<tr><td>few+many</td><td>3–6</td><td>3–6 chi, 3–6 chath</td><td nowrap="">few + many → many</td></tr>
	<tr><td>few+other</td><td>3–4</td><td>3–4 ci, 3–4 cath</td><td nowrap="">few + other → other</td></tr>
	<tr><td>many+other</td><td>6–7</td><td>6–7 ci, 6–7 cath</td><td nowrap="">many + other → other</td></tr>
	<tr><td>other+one</td><td>0.1–1</td><td>0.1–1 ci, 0.1–1 gath</td><td nowrap="">other + one → one</td></tr>
	<tr><td>other+two</td><td>0.1–2</td><td>0.1–2 gi, 0.1–2 gath</td><td nowrap="">other + two → two</td></tr>
	<tr><td>other+few</td><td>0.1–3</td><td>0.1–3 chi, 0.1–3 cath</td><td nowrap="">other + few → few</td></tr>
	<tr><td>other+many</td><td>0.1–6</td><td>0.1–6 chi, 0.1–6 chath</td><td nowrap="">other + many → many</td></tr>
	<tr><td>other+other</td><td>0.1–4</td><td>0.1–4 ci, 0.1–4 cath</td><td nowrap="">other + other → other</td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Western Frisian</td><td rowspan="4"><a name="fy" href="#fy">fy</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Wolof</td><td rowspan="2"><a name="wo" href="#wo">wo</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="3">Xhosa</td><td rowspan="3"><a name="xh" href="#xh">xh</a></td><td rowspan="2">cardinal</td><td>one</td><td>1<br>1.0, 1.00, 1.000, 1.0000</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">n = 1</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~0.9, 1.1~1.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="4">Yiddish</td><td><a name="ji" href="#ji">ji</a></td><td><i>=<a href="#yi">yi</a></i></td><td><i>=<a href="#yi">yi</a></i></td><td><i>=<a href="#yi">yi</a></i></td><td><i>=<a href="#yi">yi</a></i></td><td nowrap=""><i>=<a href="#yi">yi</a></i></td></tr>
	<tr><td rowspan="3"><a name="yi" href="#yi">yi</a></td><td rowspan="2">cardinal</td><td>one</td><td>1</td><td rowspan="2"><i>Not available.</i></td><td nowrap="">i = 1 and<br>&nbsp;&nbsp;v = 0</td></tr>
	<tr><td>other</td><td>0, 2~16, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>Not available.</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="2">Yoruba</td><td rowspan="2"><a name="yo" href="#yo">yo</a></td><td>cardinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …<br>0.0~1.5, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td><i>no plural differences</i></td><td nowrap=""></td></tr>
	<tr><td>range</td><td><i>n/a</i></td><td><i>n/a</i></td><td><i>no plural differences</i></td><td nowrap=""><i>n/a</i></td></tr>
	<tr><th>Name</th><th>Code</th><th>Type</th><th>Category</th><th>Examples</th><th>Minimal Pairs</th><th>Rules</th></tr>
	<tr><td rowspan="6">Zulu</td><td rowspan="6"><a name="zu" href="#zu">zu</a></td><td rowspan="2">cardinal</td><td>one</td><td>0, 1<br>0.0~1.0, 0.00~0.04</td><td>1 usuku<br>1.0 usuku</td><td nowrap="">i = 0 or<br>n = 1</td></tr>
	<tr><td>other</td><td>2~17, 100, 1000, 10000, 100000, 1000000, …<br>1.1~2.6, 10.0, 100.0, 1000.0, 10000.0, 100000.0, 1000000.0, …</td><td>2 izinsuku<br>1.1 izinsuku</td><td nowrap=""></td></tr>
	<tr><td>ordinal</td><td>other</td><td>0~15, 100, 1000, 10000, 100000, 1000000, …</td><td>Thatha indlela ejikela kwesokudla engu-15</td><td nowrap=""></td></tr>
	<tr><td rowspan="3">range</td><td>one+one</td><td>0–1</td><td>0–1 usuku</td><td nowrap="">one + one → one</td></tr>
	<tr><td>one+other</td><td>0–2</td><td>0–2 izinsuku</td><td nowrap="">one + other → other</td></tr>
	<tr><td>other+other</td><td>1.1–2</td><td>1.1–2 izinsuku</td><td nowrap="">other + other → other</td></tr>
</tbody></table>