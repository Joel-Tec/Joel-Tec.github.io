# Joel-Tec.github.io
My Web pages
<head>
<style type="text/css">
.logo {
  float: right;
}
</style>
</head>

<body>
<div class="logo">
$if(draft)$
<!-- use draft.png to show that this is a draft -->
<img src="images/draft.png" alt="Draft mode" />
$else$
<!-- insert the formal logo if this is final -->
<img src="images/logo.png" alt="Final version" />
$endif$
</div>

$body$
</body>
