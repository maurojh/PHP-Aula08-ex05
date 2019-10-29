<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<!-- 2019-10-29 ter 17:44 -->
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>&lrm;</title>
<meta name="generator" content="Org mode" />
<style type="text/css">
 <!--/*--><![CDATA[/*><!--*/
  .title  { text-align: center;
             margin-bottom: .2em; }
  .subtitle { text-align: center;
              font-size: medium;
              font-weight: bold;
              margin-top:0; }
  .todo   { font-family: monospace; color: red; }
  .done   { font-family: monospace; color: green; }
  .priority { font-family: monospace; color: orange; }
  .tag    { background-color: #eee; font-family: monospace;
            padding: 2px; font-size: 80%; font-weight: normal; }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  .org-right  { margin-left: auto; margin-right: 0px;  text-align: right; }
  .org-left   { margin-left: 0px;  margin-right: auto; text-align: left; }
  .org-center { margin-left: auto; margin-right: auto; text-align: center; }
  .underline { text-decoration: underline; }
  #postamble p, #preamble p { font-size: 90%; margin: .2em; }
  p.verse { margin-left: 3%; }
  pre {
    border: 1px solid #ccc;
    box-shadow: 3px 3px 3px #eee;
    padding: 8pt;
    font-family: monospace;
    overflow: auto;
    margin: 1.2em;
  }
  pre.src {
    position: relative;
    overflow: visible;
    padding-top: 1.2em;
  }
  pre.src:before {
    display: none;
    position: absolute;
    background-color: white;
    top: -10px;
    right: 10px;
    padding: 3px;
    border: 1px solid black;
  }
  pre.src:hover:before { display: inline;}
  /* Languages per Org manual */
  pre.src-asymptote:before { content: 'Asymptote'; }
  pre.src-awk:before { content: 'Awk'; }
  pre.src-C:before { content: 'C'; }
  /* pre.src-C++ doesn't work in CSS */
  pre.src-clojure:before { content: 'Clojure'; }
  pre.src-css:before { content: 'CSS'; }
  pre.src-D:before { content: 'D'; }
  pre.src-ditaa:before { content: 'ditaa'; }
  pre.src-dot:before { content: 'Graphviz'; }
  pre.src-calc:before { content: 'Emacs Calc'; }
  pre.src-emacs-lisp:before { content: 'Emacs Lisp'; }
  pre.src-fortran:before { content: 'Fortran'; }
  pre.src-gnuplot:before { content: 'gnuplot'; }
  pre.src-haskell:before { content: 'Haskell'; }
  pre.src-hledger:before { content: 'hledger'; }
  pre.src-java:before { content: 'Java'; }
  pre.src-js:before { content: 'Javascript'; }
  pre.src-latex:before { content: 'LaTeX'; }
  pre.src-ledger:before { content: 'Ledger'; }
  pre.src-lisp:before { content: 'Lisp'; }
  pre.src-lilypond:before { content: 'Lilypond'; }
  pre.src-lua:before { content: 'Lua'; }
  pre.src-matlab:before { content: 'MATLAB'; }
  pre.src-mscgen:before { content: 'Mscgen'; }
  pre.src-ocaml:before { content: 'Objective Caml'; }
  pre.src-octave:before { content: 'Octave'; }
  pre.src-org:before { content: 'Org mode'; }
  pre.src-oz:before { content: 'OZ'; }
  pre.src-plantuml:before { content: 'Plantuml'; }
  pre.src-processing:before { content: 'Processing.js'; }
  pre.src-python:before { content: 'Python'; }
  pre.src-R:before { content: 'R'; }
  pre.src-ruby:before { content: 'Ruby'; }
  pre.src-sass:before { content: 'Sass'; }
  pre.src-scheme:before { content: 'Scheme'; }
  pre.src-screen:before { content: 'Gnu Screen'; }
  pre.src-sed:before { content: 'Sed'; }
  pre.src-sh:before { content: 'shell'; }
  pre.src-sql:before { content: 'SQL'; }
  pre.src-sqlite:before { content: 'SQLite'; }
  /* additional languages in org.el's org-babel-load-languages alist */
  pre.src-forth:before { content: 'Forth'; }
  pre.src-io:before { content: 'IO'; }
  pre.src-J:before { content: 'J'; }
  pre.src-makefile:before { content: 'Makefile'; }
  pre.src-maxima:before { content: 'Maxima'; }
  pre.src-perl:before { content: 'Perl'; }
  pre.src-picolisp:before { content: 'Pico Lisp'; }
  pre.src-scala:before { content: 'Scala'; }
  pre.src-shell:before { content: 'Shell Script'; }
  pre.src-ebnf2ps:before { content: 'ebfn2ps'; }
  /* additional language identifiers per "defun org-babel-execute"
       in ob-*.el */
  pre.src-cpp:before  { content: 'C++'; }
  pre.src-abc:before  { content: 'ABC'; }
  pre.src-coq:before  { content: 'Coq'; }
  pre.src-groovy:before  { content: 'Groovy'; }
  /* additional language identifiers from org-babel-shell-names in
     ob-shell.el: ob-shell is the only babel language using a lambda to put
     the execution function name together. */
  pre.src-bash:before  { content: 'bash'; }
  pre.src-csh:before  { content: 'csh'; }
  pre.src-ash:before  { content: 'ash'; }
  pre.src-dash:before  { content: 'dash'; }
  pre.src-ksh:before  { content: 'ksh'; }
  pre.src-mksh:before  { content: 'mksh'; }
  pre.src-posh:before  { content: 'posh'; }
  /* Additional Emacs modes also supported by the LaTeX listings package */
  pre.src-ada:before { content: 'Ada'; }
  pre.src-asm:before { content: 'Assembler'; }
  pre.src-caml:before { content: 'Caml'; }
  pre.src-delphi:before { content: 'Delphi'; }
  pre.src-html:before { content: 'HTML'; }
  pre.src-idl:before { content: 'IDL'; }
  pre.src-mercury:before { content: 'Mercury'; }
  pre.src-metapost:before { content: 'MetaPost'; }
  pre.src-modula-2:before { content: 'Modula-2'; }
  pre.src-pascal:before { content: 'Pascal'; }
  pre.src-ps:before { content: 'PostScript'; }
  pre.src-prolog:before { content: 'Prolog'; }
  pre.src-simula:before { content: 'Simula'; }
  pre.src-tcl:before { content: 'tcl'; }
  pre.src-tex:before { content: 'TeX'; }
  pre.src-plain-tex:before { content: 'Plain TeX'; }
  pre.src-verilog:before { content: 'Verilog'; }
  pre.src-vhdl:before { content: 'VHDL'; }
  pre.src-xml:before { content: 'XML'; }
  pre.src-nxml:before { content: 'XML'; }
  /* add a generic configuration mode; LaTeX export needs an additional
     (add-to-list 'org-latex-listings-langs '(conf " ")) in .emacs */
  pre.src-conf:before { content: 'Configuration File'; }

  table { border-collapse:collapse; }
  caption.t-above { caption-side: top; }
  caption.t-bottom { caption-side: bottom; }
  td, th { vertical-align:top;  }
  th.org-right  { text-align: center;  }
  th.org-left   { text-align: center;   }
  th.org-center { text-align: center; }
  td.org-right  { text-align: right;  }
  td.org-left   { text-align: left;   }
  td.org-center { text-align: center; }
  dt { font-weight: bold; }
  .footpara { display: inline; }
  .footdef  { margin-bottom: 1em; }
  .figure { padding: 1em; }
  .figure p { text-align: center; }
  .inlinetask {
    padding: 10px;
    border: 2px solid gray;
    margin: 10px;
    background: #ffffcc;
  }
  #org-div-home-and-up
   { text-align: right; font-size: 70%; white-space: nowrap; }
  textarea { overflow-x: auto; }
  .linenr { font-size: smaller }
  .code-highlighted { background-color: #ffff00; }
  .org-info-js_info-navigation { border-style: none; }
  #org-info-js_console-label
    { font-size: 10px; font-weight: bold; white-space: nowrap; }
  .org-info-js_search-highlight
    { background-color: #ffff00; color: #000000; font-weight: bold; }
  .org-svg { width: 90%; }
  /*]]>*/-->
</style>
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2019 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
</head>
<body>
<div id="content">
<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#org3382743">1. Upload de imagem</a>
<ul>
<li><a href="#org345236a">1.1. Exercício 1</a></li>
<li><a href="#orgafd62ed">1.2. Verificar o tipo de arquivo</a></li>
<li><a href="#orgb17a02d">1.3. Exercício 2</a></li>
<li><a href="#org9ac5067">1.4. Exercício 3</a></li>
<li><a href="#org4982666">1.5. Exercício 4</a></li>
<li><a href="#orgb6fa07d">1.6. Exercício 5</a></li>
</ul>
</li>
</ul>
</div>
</div>

<div id="outline-container-org3382743" class="outline-2">
<h2 id="org3382743"><span class="section-number-2">1</span> Upload de imagem</h2>
<div class="outline-text-2" id="text-1">
<p>
Para enviar um arquivo de imagem o formulário deve ser como o seguinte:
</p>

<pre class="example">
&lt;form action="recebe.php" method="post" enctype="multipart/form-data"&gt;
    Selecione a imagem:
    &lt;input type="file" name="arquivo" id="arquivo"&gt;
    &lt;input type="submit" value="Enviar imagem" name="submit"&gt;
&lt;/form&gt;
</pre>

<p>
O método de envio deve ser <b>post</b>.
Deve conter o atributo <b>enctype="multipart/form-data"</b> que especifica o tipo do conteúdo submetido.
</p>

<p>
A página que recebe os dados deve fazer o seguinte:
</p>

<ol class="org-ol">
<li>Ajustar o destino do arquivo.</li>
<li>Usar a função move_uploaded_file() para copiar o arquivo da pasta temporária para a pasta desejada.</li>
</ol>

<p>
Exemplo:
</p>

<pre class="example">
&lt;?php
$diretorio = "img/";
$destino = $diretorio . basename($_FILES["arquivo"]["name"]);

if (move_uploaded_file($_FILES["arquivo"]["tmp_name"], $destino)) {
    echo "O arquivo ". basename( $_FILES["arquivo"]["name"]). " foi enviado.";
} else {
    echo "Erro no envio.";
}
?&gt;
</pre>
</div>

<div id="outline-container-org345236a" class="outline-3">
<h3 id="org345236a"><span class="section-number-3">1.1</span> Exercício 1</h3>
<div class="outline-text-3" id="text-1-1">
<p>
Altere o código da página recebe.php para enviar para outro diretório com nome diferente de <b>img</b>.
</p>
</div>
</div>



<div id="outline-container-orgafd62ed" class="outline-3">
<h3 id="orgafd62ed"><span class="section-number-3">1.2</span> Verificar o tipo de arquivo</h3>
<div class="outline-text-3" id="text-1-2">
<p>
Para verificar o tipo do arquivo usamos a função <b>pathinfo()</b> para retirar apenas a extensão:
</p>

<pre class="example">
$tipo = strtolower(pathinfo($destino,PATHINFO_EXTENSION));

if($tipo != "jpg" ) {
    echo "Aceitamos apenas JPG, desculpe";
    die("Erro, a página morreu aqui mesmo!");
}
</pre>
</div>
</div>

<div id="outline-container-orgb17a02d" class="outline-3">
<h3 id="orgb17a02d"><span class="section-number-3">1.3</span> Exercício 2</h3>
<div class="outline-text-3" id="text-1-3">
<p>
Acrescente no código acima outras extensões de arquivo de imagem. PNG por exemplo.
</p>
</div>
</div>

<div id="outline-container-org9ac5067" class="outline-3">
<h3 id="org9ac5067"><span class="section-number-3">1.4</span> Exercício 3</h3>
<div class="outline-text-3" id="text-1-4">
<p>
Crie uma página que recebe um arquivo de imagem e salva na pasta img incluindo a data no formato ANOMESDIAHORAMINUTO no comeco do nome do arquivo.
</p>

<p>
<b>Exemplo</b>: Usuário envia foto.jpg às 18:45 de 17/10/2019, a imagem fica na pasta img com nome 201910171845foto.jpg.
</p>
</div>
</div>

<div id="outline-container-org4982666" class="outline-3">
<h3 id="org4982666"><span class="section-number-3">1.5</span> Exercício 4</h3>
<div class="outline-text-3" id="text-1-5">
<p>
Mostre a imagem enviada pelo usuário usando a tag <b>&lt;img&gt;</b>.
</p>

<p>
Exemplo o usuário enviou a imagem foto.jpg às 18:45 de 17/10/2019, a tag &lt;img&gt; fica assim:
</p>

<pre class="example">
&lt;img src="img/201910171845foto.jpg"&gt;
</pre>
</div>
</div>

<div id="outline-container-orgb6fa07d" class="outline-3">
<h3 id="orgb6fa07d"><span class="section-number-3">1.6</span> Exercício 5</h3>
<div class="outline-text-3" id="text-1-6">
<p>
Crie um sistema de chat utilizando as tabelas disponíveis no link abaixo:
</p>

<p>
<a href="https://dbdesigner.page.link/7vT7">https://dbdesigner.page.link/7vT7</a>
</p>

<p>
O usuário deve preencher o cadastro.
</p>

<p>
Após efetuar o login, o usuário pode criar uma sala, ou entrar em uma sala existente.
</p>

<p>
Dentro da sala o usuário deve ver todas as mensagem e pode enviar uma mensagem ou <b>imagem</b> para a sala.
</p>

<p>
SQL das tabelas:
</p>

<pre class="example">
CREATE TABLE `Usuarios` (
	`id` INT NOT NULL AUTO_INCREMENT,
	`nome` varchar(255) NOT NULL,
	`email` varchar(255) NOT NULL,
	`senha` varchar(64) NOT NULL,
	PRIMARY KEY (`id`)
);

CREATE TABLE `Sala` (
	`id` INT NOT NULL AUTO_INCREMENT,
	`nome` varchar(255) NOT NULL,
	`dono` INT(255) NOT NULL,
	PRIMARY KEY (`id`)
);

CREATE TABLE `Mensagens` (
	`id` INT NOT NULL AUTO_INCREMENT,
	`remetente` INT NOT NULL,
	`mensagem` varchar(255) NOT NULL,
	`sala` INT(255) NOT NULL,
	PRIMARY KEY (`id`)
);

ALTER TABLE `Sala` ADD CONSTRAINT `Sala_fk0` FOREIGN KEY (`dono`) REFERENCES `Usuarios`(`id`);

ALTER TABLE `Mensagens` ADD CONSTRAINT `Mensagens_fk0` FOREIGN KEY (`remetente`) REFERENCES `Usuarios`(`id`);

ALTER TABLE `Mensagens` ADD CONSTRAINT `Mensagens_fk1` FOREIGN KEY (`sala`) REFERENCES `Sala`(`id`);
</pre>



<pre class="example">

</pre>
</div>
</div>
</div>
</div>
<div id="postamble" class="status">
<p class="date">Created: 2019-10-29 ter 17:44</p>
<p class="validation"><a href="http://validator.w3.org/check?uri=referer">Validate</a></p>
</div>
</body>
</html>

