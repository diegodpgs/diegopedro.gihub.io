<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN"
       "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
  <title>Guillaume Melquiond's page</title>
  <link rel="stylesheet" type="text/css" href="style.css" />
  <script type="text/javascript" src="jquery-1.9.1.min.js"></script>
  <script type="text/javascript" src="dynlist.js"></script>
  <script type="text/javascript">dynlist('see more', 'see less');</script>
</head>

<body>

<div class="photo"><img src="imagens/diego.jpg" alt="Diego Pedro" /></div>

<p class="language"><a href="index.html.fr">Version française</a></p>

<h1>Guillaume Melquiond</h1>

<p>I am an <a href="https://www.inria.fr/fr/centre-inria-saclay-ile-de-france">Inria</a> researcher
in the <a href="http://toccata.lri.fr/">Toccata</a> team
from the <a href="https://lmf.cnrs.fr/">LMF</a> laboratory
(<a href="https://www.universite-paris-saclay.fr/">Université Paris Saclay</a>).</p>

<h2>Research interests</h2>

<p>My work lies at the intersection between the domains of computer
arithmetic and formal proof.</p>

<ul class="topics">
  <li><b>Automated proof of numerical properties.</b> I am interested in
    methods for automating the verification of numerical programs. In
    particular, I am developing the
    <a href="https://gappa.gitlabpages.inria.fr/">Gappa</a> tool and the
    <a href="https://coqinterval.gitlabpages.inria.fr/">CoqInterval</a> library.
    Gappa is dedicated to the formal proof of small yet complicated functions
    relying on floating-point arithmetic; such functions can be found in
    mathematical libraries such as
    <a href="http://lipforge.ens-lyon.fr/www/crlibm/">CRlibm</a>. CoqInterval
    provides some Coq tactics for formally proving inequalities on
    real-valued expressions by performing computations. I am also investigating
    SMT solvers such as  <a href="http://alt-ergo.lri.fr">Alt-Ergo</a> in
    order to improve their support for real and floating-point arithmetics.</li>
  <li><b>Formal verification of programs.</b> With respect to program proof,
    I am also participating to bigger projects. For instance, the goal of the
    <a href="http://fost.saclay.inria.fr/">FOST</a> project was to achieve
    a comprehensive formal proof of a scientific computing program that solves
    the wave equation. The <a href="http://verasco.imag.fr/">Verasco</a>
    project aimed at developing and formally verifying a C compiler and some
    static analysis tools. I am also contributing to the development of the
    <a href="http://why3.lri.fr/">Why3</a> framework for deductive verification
    of programs and to its interactions with Coq and Gappa.</li>
  <li><b>Formalization of arithmetic.</b> The above topics require from proof
    assistants a good support for real numbers and analysis, and for
    floating-point arithmetic. As a consequence, I am also part of the
    <a href="http://coquelicot.saclay.inria.fr/">Coquelicot</a> and
    <a href="https://flocq.gitlabpages.inria.fr/">Flocq</a> projects. Coquelicot is
    a conservative extension of Coq's standard library on real numbers,
    while Flocq is a generic formalization of floating-point arithmetic in
    Coq.</li>
  <li><b>Interval arithmetic.</b> I am also looking at reliable computations
    outside formal systems, and more precisely at interval arithmetic. For
    instance, I am one of the developers of a generic interval module for
    the <a href="https://www.boost.org/">Boost</a> C++ library. I am also a
    member of the
    <a href="http://grouper.ieee.org/groups/1788/">IEEE 1788</a> committee
    for standardizing interval arithmetic and I follow the evolution of the
    C++ language with respect to support for scientific computations.</li>
</ul>

<h2>Publications (<a href="biblio.html"><code>bibtex</code></a>)</h2>

<div class="book">
  <a href="https://dx.doi.org/10.1007/978-3-319-76526-6">
    <img src="divers/book1.png" alt="Handbook of Floating-Point Arithmetic" />
  </a>
  <br/>
  <a href="http://iste.co.uk/book.php?id=1238">
    <img src="divers/book2.jpg" alt="Computer Arithmetic and Formal Proofs" />
  </a>
</div>

<h3>Books, book chapters, and theses:</h3>

<ul class="dynlist">
  <li><b>Formal verification for numerical computations, and the other way around</b>.<br/>
    <a href="doc/19-hdr.pdf">HDR</a> and <a href="doc/19-soutenance.pdf">defense</a>.
    <a href="https://hal.archives-ouvertes.fr/tel-02194683">HAL</a>.</li>
  <li><b>Handbook of Floating-Point Arithmetic</b> (2nd edition), coordinated by
    <a href="http://perso.ens-lyon.fr/jean-michel.muller/">Jean-Michel Muller</a>,<br/>
    published by Birkhäuser (2018).
    <a href="http://perso.ens-lyon.fr/jean-michel.muller/Handbook.html">Summary</a>.
    <a href="https://dx.doi.org/10.1007/978-3-319-76526-6">DOI</a>.</li>
  <li><b>Computer Arithmetic and Formal Proofs: Verifying Floating-point Algorithms with the Coq System</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,<br/>
    published by ISTE Press - Elsevier (2017).
    <a href="http://iste.co.uk/book.php?id=1238">URL</a>.</li>
  <li><b>Arithmétique des ordinateurs et preuves formelles</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,<br/>
    in Informatique Mathématique&nbsp;: une photographie en 2013.</li>
  <li><b>Handbook of Floating-Point Arithmetic</b>, coordinated by
    <a href="http://perso.ens-lyon.fr/jean-michel.muller/">Jean-Michel Muller</a>,<br/>
    published by Birkhäuser (2010).
    <a href="http://perso.ens-lyon.fr/jean-michel.muller/Handbook.html">Summary</a>.
    <a href="https://dx.doi.org/10.1007/978-0-8176-4705-6">DOI</a>.</li>
  <li><b>Arithmétique d'intervalles et certification de programmes</b>.<br/>
    <a href="doc/06-these.pdf">PhD thesis</a> (in French) and
    <a href="doc/06-soutenance.pdf">defense</a>.
    <a href="https://hal.archives-ouvertes.fr/tel-01094485">HAL</a>.</li>
</ul>

<h3>Journals:</h3>

<ul class="dynlist">
  <li><b>WhyMP, a formally verified arbitrary-precision integer library</b>,
    avec Raphaël Rieu-Helft.<br/>
    <a href="doc/21-jsc.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-03233220">HAL</a>.</li>
  <li><b>Formally verified approximations of definite integrals</b>,
    with <a href="http://people.rennes.inria.fr/Assia.Mahboubi/">Assia Mahboubi</a>
    and Thomas Sibut-Pinote,<br/>
    in Journal of Automated Reasoning (2019, volume 62.2).
    <a href="doc/18-jar.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-01630143">HAL</a>,
    <a href="https://dx.doi.org/10.1007/s10817-018-9463-7">DOI</a>.</li>
  <li><b>Proving tight bounds on univariate expressions with elementary functions in Coq</b>,
    with <a href="http://erik.martin-dorel.org/">Érik Martin-Dorel</a>,<br/>
    in Journal of Automated Reasoning (2016, volume 57.3).
    <a href="doc/15-jar.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-01086460">HAL</a>,
    <a href="https://dx.doi.org/10.1007/s10817-015-9350-4">DOI</a>.</li>
  <li><b>Formalization of real analysis: A survey of proof assistants and libraries</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>
    and Catherine Lelay,<br/>
    in Mathematical Structures in Computer Science (2016, volume 26.7).
    <a href="doc/14-mscs.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00806920">HAL</a>,
    <a href="https://dx.doi.org/10.1017/S0960129514000437">DOI</a>.</li>
  <li><b>Coquelicot: a user-friendly library of real analysis for Coq</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>
    and Catherine Lelay,<br/>
    in Mathematics in Computer Science (2015, volume 9.1).
    <a href="doc/14-mcs.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00860648">HAL</a>,
    <a href="https://dx.doi.org/10.1007/s11786-014-0181-1">DOI</a>.</li>
  <li><b>Verified compilation of floating-point computations</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,
    <a href="https://jhjourdan.mketjh.fr/">Jacques-Henri Jourdan</a>,
    and <a href="https://xavierleroy.org/">Xavier Leroy</a>,<br/>
    in Journal of Automated Reasoning (2015, volume 54.2).
    <a href="doc/14-jar.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00862689">HAL</a>,
    <a href="https://dx.doi.org/10.1007/s10817-014-9317-x">DOI</a>.</li>
  <li><b>Trusting computations: a mechanized proof from partial differential equations to actual program</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,
    <a href="https://who.rocq.inria.fr/Francois.Clement/">François Clément</a>,
    <a href="https://www.lri.fr/~filliatr/">Jean-Christophe Filliâtre</a>,
    <a href="https://lipn.univ-paris13.fr/~mayero/">Micaela Mayero</a>,
    and <a href="http://pauillac.inria.fr/~weis/">Pierre Weis</a>,<br/>
    in Computers &amp; Mathematics with Applications (2014, volume 68.3).
    <a href="doc/14-camwa.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00769201">HAL</a>,
    <a href="https://dx.doi.org/10.1016/j.camwa.2014.06.004">DOI</a>.</li>
  <li><b>Some issues related to double rounding</b>,
    with <a href="http://erik.martin-dorel.org/">Érik Martin-Dorel</a>
    and <a href="http://perso.ens-lyon.fr/jean-michel.muller/">Jean-Michel Muller</a>,<br/>
    in BIT Numerical Mathematics (2013, volume 53.4).
    <a href="doc/13-bitn.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/ensl-00644408">HAL</a>,
    <a href="https://dx.doi.org/10.1007/s10543-013-0436-2">DOI</a>.</li>
  <li><b>Wave equation numerical resolution: a comprehensive mechanized proof of a C program</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,
    <a href="https://who.rocq.inria.fr/Francois.Clement/">François Clément</a>,
    <a href="https://www.lri.fr/~filliatr/">Jean-Christophe Filliâtre</a>,
    <a href="https://lipn.univ-paris13.fr/~mayero/">Micaela Mayero</a>,
    and <a href="http://pauillac.inria.fr/~weis/">Pierre Weis</a>,<br/>
    in Journal of Automated Reasoning (2013, volume 50.4).
    <a href="doc/12-jar.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00649240">HAL</a>,
    <a href="https://dx.doi.org/10.1007/s10817-012-9255-4">DOI</a>.</li>
  <li><b>Numerical approximation of the Masser-Gramain constant to four decimal digits: &delta; = 1.819...</b>,
    with W. Georg Nowak
    and <a href="https://members.loria.fr/PZimmermann/">Paul Zimmermann</a>,<br/>
    in Mathematics of Computation (2013, volume 82).
    <a href="doc/12-mc.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00644166">HAL</a>,
    <a href="https://dx.doi.org/10.1090/S0025-5718-2012-02635-4">DOI</a>.</li>
  <li><b>Floating-point arithmetic in the Coq system</b>,<br/>
    in Information and Computation (2012, volume 216).
    <a href="doc/12-ic.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00797913">HAL</a>,
    <a href="https://dx.doi.org/10.1016/j.ic.2011.09.005">DOI</a>.</li>
  <li><b>Certifying the floating-point implementation of an elementary function using Gappa</b>,
    with <a href="http://perso.citi-lab.fr/fdedinec/">Florent de Dinechin</a>
    and <a href="https://www.christoph-lauter.org/">Christoph Lauter</a>,<br/>
    in Transactions on Computers (2011, volume 60.2).
    <a href="doc/10-tc.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/ensl-00200830">HAL</a>,
    <a href="https://dx.doi.org/10.1109/TC.2010.128">DOI</a>.</li>
  <li><b>Certification of bounds on expressions involving rounded operators</b>,
    with <a href="http://md.srvr.fr/">Marc Daumas</a>,<br/>
    in Transactions on Mathematical Software (2010, volume 37.1).
    <a href="doc/09-toms.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00127769">HAL</a>,
    <a href="https://dx.doi.org/10.1145/1644001.1644003">DOI</a>.</li>
  <li><b>Computing predecessor and successor in rounding to nearest</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,
    <a href="https://www.tuhh.de/ti3/rump/">Siegfried Rump</a>,
    and <a href="https://members.loria.fr/PZimmermann/">Paul Zimmermann</a>,<br/>
    in BIT Numerical Mathematics (2009, volume 49.2).
    <a href="doc/09-bitn.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00337537">HAL</a>,
    <a href="https://dx.doi.org/10.1007/s10543-009-0218-z">DOI</a>.</li>
  <li><b>Emulation of FMA and correctly-rounded sums: proved algorithm using rounding to odd</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,<br/>
    in Transactions on Computers (2008, volume 57.4).
    <a href="doc/08-tc.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00080427">HAL</a>,
    <a href="https://dx.doi.org/10.1109/TC.2007.70819">DOI</a>.</li>
  <li><b>Formally certified floating-point filters for homogeneous geometric predicate</b>,
    with <a href="https://people.bordeaux.inria.fr/sylvain.pion/">Sylvain Pion</a>,<br/>
    in Theoretical Informatics and Applications (2007, volume 41.1).
    <a href="doc/07-tia.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00071232">HAL</a>,
    <a href="https://dx.doi.org/10.1051/ita:2007005">DOI</a>.</li>
  <li><b>The design of the Boost interval arithmetic library</b>,
    with Hervé Brönnimann
    and <a href="https://people.bordeaux.inria.fr/sylvain.pion/">Sylvain Pion</a>,<br/>
    in Theoretical Computer Science (2006, volume 351).
    <a href="doc/06-tcs-rnc5.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00344412">HAL</a>,
    <a href="https://dx.doi.org/10.1016/j.tcs.2005.09.062">DOI</a>.</li>
</ul>

<h3>Conferences:</h3>

<ul class="dynlist">
  <li><b>A strong call-by-need calculus</b>,
    with <a href="https://www.lri.fr/~blsk/">Thibaut Balabonski</a>
    and <a href="https://www.lri.fr/~lanco/">Antoine Lanco</a>,<br/>
    for the 6th FSCD conference (2021).
    <a href="doc/21-fscd-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-03149692">HAL</a>,
    <a href="https://dx.doi.org/10.4230/LIPIcs.FSCD.2021.9">DOI</a>.</li>
  <li><b>Some formal tools for computer arithmetic: Flocq and Gappa</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,<br/>
    for the 28th ARITH symposium (2021).
    <a href="doc/21-arith-article.pdf">Paper</a> and
    <a href="doc/21-arith-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-03233227">HAL</a>.</li>
  <li><b>Plotting in a formally verified way</b>,<br/>
    for the 6th F-IDE workshop (2021).
    <a href="doc/21-fide-article.pdf">Paper</a> and
    <a href="doc/21-fide-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-03168208">HAL</a>,
    <a href="https://dx.doi.org/10.4204/EPTCS.338.6">DOI</a>.</li>
  <li><b>WhyMP, a formally verified arbitrary-precision integer library</b>,
    with Raphaël Rieu-Helft,<br/>
    for the 45th ISSAC symposium (2020, Kalamata, Greece).
    <a href="doc/20-issac-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-02566654">HAL</a>,
    <a href="https://dx.doi.org/10.1145/3373207.3404029">DOI</a>.</li>
  <li><b>Formal verification of a state-of-the-art integer square root</b>,
    with Raphaël Rieu-Helft,<br/>
    for the 26th ARITH symposium (2019, Kyoto, Japan).
    <a href="doc/19-arith-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-02092970">HAL</a>,
    <a href="https://dx.doi.org/10.1109/ARITH.2019.00041">DOI</a>.</li>
  <li><b>A Why3 framework for reflection proofs and its application to GMP's algorithms</b>,
    with Raphaël Rieu-Helft,<br/>
    for the 9th IJCAR conference (2018, Oxford, United Kingdom).
    <a href="doc/18-ijcar-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-01699754">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-319-94205-6_13">DOI</a>.</li>
  <li><b>A three-tier strategy for reasoning about floating-point numbers in SMT</b>,
    with <a href="https://www.lri.fr/~conchon/">Sylvain Conchon</a>,
    <a href="http://www.iguer.xyz/">Mohamed Iguernelala</a>,
    Kailiang Ji,
    and Clément Fumex,<br/>
    for the 29th CAV conference (2017, Heidelberg, Germany).
    <a href="doc/17-cav-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-01522770">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-319-63390-9_22">DOI</a>.</li>
  <li><b>How to get an efficient yet verified arbitrary-precision integer library</b>,
    with Raphaël Rieu-Helft
    and <a href="https://www.lri.fr/~marche/">Claude Marché</a>,<br/>
    for the 9th VSTTE conference (2017, Heidelberg, Germany).
    <a href="doc/17-vstte-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-01519732">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-319-72308-2_6">DOI</a>.</li>
  <li><b>Formally verified approximations of definite integrals</b>,
    with <a href="http://people.rennes.inria.fr/Assia.Mahboubi/">Assia Mahboubi</a>
    and Thomas Sibut-Pinote,<br/>
    for the 7th ITP symposium (2016, Nancy, France).
    <a href="doc/16-itp-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-01289616">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-319-43144-4_17">DOI</a>.</li>
  <li><b>Inductive verification of hybrid automata with strongest postcondition calculus</b>,
    with <a href="https://www.dsksh.com/">Daisuke Ishii</a>
    and Shin Nakajima,<br/>
    for the 10th iFM symposium (2013, Turku, Finland).
    <a href="doc/13-ifm-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00806701">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-642-38613-8_10">DOI</a>.</li>
  <li><b>Preserving user proofs across specification changes</b>,
    with François Bobot,
    <a href="https://www.lri.fr/~filliatr/">Jean-Christophe Filliâtre</a>,
    <a href="https://www.lri.fr/~marche/">Claude Marché</a>,
    and <a href="https://www.lri.fr/~andrei/">Andrei Paskevich</a>,<br/>
    for the 5th VSTTE conference (2013, Menlo Park, CA, USA).
    <a href="doc/13-vstte-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00875395">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-642-54108-7_10">DOI</a>.</li>
  <li><b>A formally-verified C compiler supporting floating-point arithmetic</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,
    <a href="https://jhjourdan.mketjh.fr/">Jacques-Henri Jourdan</a>,
    and <a href="https://xavierleroy.org/">Xavier Leroy</a>,<br/>
    for the 21st ARITH symposium (2013, Austin, TX, USA).
    <a href="doc/13-arith-article.pdf">Paper</a> and
    <a href="doc/13-arith-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00743090">HAL</a>,
    <a href="https://dx.doi.org/10.1109/ARITH.2013.30">DOI</a>.</li>
  <li><b>Improving real analysis in Coq: a user-friendly approach to integrals and derivatives</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>
    and Catherine Lelay,<br/>
    for the 2nd CPP symposium (2012, Kyoto, Japan).
    <a href="doc/12-cpp-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00712938">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-642-35308-6_22">DOI</a>.</li>
  <li><b>Built-in treatment of an axiomatic floating-point theory for SMT solvers</b>,
    with <a href="https://www.lri.fr/~conchon/">Sylvain Conchon</a>,
    Cody Roux,
    and <a href="http://www.iguer.xyz/">Mohamed Iguernelala</a>,<br/>
    for the 10th SMT workshop (2012, Manchester, UK).
    <a href="doc/12-smt-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-01785166">HAL</a>.</li>
  <li><b>A Simplex-based extension of Fourier-Motzkin for solving linear integer arithmetic</b>,
    with François Bobot,
    <a href="https://www.lri.fr/~conchon/">Sylvain Conchon</a>,
    <a href="https://www.lri.fr/~contejea/">Évelyne Contejean</a>,
    <a href="http://www.iguer.xyz/">Mohamed Iguernelala</a>,
    <a href="http://people.rennes.inria.fr/Assia.Mahboubi/">Assia Mahboubi</a>,
    and <a href="https://www.lri.fr/~mebsout/">Alain Mebsout</a>,<br/>
    for the 6th IJCAR symposium (2012, Manchester, UK).
    <a href="doc/12-ijcar-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00687640">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-642-31365-3_8">DOI</a>.</li>
  <li><b>Différentiabilité et intégrabilité en Coq. Application à la formule de d'Alembert</b>,
    with Catherine Lelay,<br/>
    for the 23th JFLA meeting (2012, Carnac, France).
    <a href="doc/12-jfla23-article.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00642206">HAL</a>.</li>
  <li><b>Flocq: a unified library for proving floating-point algorithms in Coq</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,<br/>
    for the 20th ARITH symposium (2011, Tübingen, Germany).
    <a href="doc/11-arith20-article.pdf">Paper</a> and
    <a href="doc/11-arith20-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00534854">HAL</a>,
    <a href="https://dx.doi.org/10.1109/ARITH.2011.40">DOI</a>.</li>
  <li><b>Formal proof of a wave equation resolution scheme: the method error</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,
    <a href="https://who.rocq.inria.fr/Francois.Clement/">François Clément</a>,
    <a href="https://www.lri.fr/~filliatr/">Jean-Christophe Filliâtre</a>,
    <a href="https://lipn.univ-paris13.fr/~mayero/">Micaela Mayero</a>,
    and <a href="http://pauillac.inria.fr/~weis/">Pierre Weis</a>,<br/>
    for the 1st ITP symposium (2010, Edinburgh, Scotland).
    <a href="doc/10-itp.pdf">Paper</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00450789">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-642-14052-5_12">DOI</a>.</li>
  <li><b>Combining Coq and Gappa for certifying floating-point programs</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>
    and <a href="https://www.lri.fr/~filliatr/">Jean-Christophe Filliâtre</a>,<br/>
    for the 16th Calculemus symposium (2009, Grand Bend, ON, Canada).
    <a href="doc/09-calculemus-article.pdf">Paper</a> and
    <a href="doc/09-calculemus-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00432726">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-642-02614-0_10">DOI</a>.</li>
  <li><b>Proving bounds on real-valued functions with computations</b>,<br/>
    for the 4th IJCAR symposium (2008, Sidney, Australia).
    <a href="doc/08-ijcar-article.pdf">Paper</a> and
    <a href="doc/08-ijcar-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00180138">HAL</a>,
    <a href="https://dx.doi.org/10.1007/978-3-540-71070-7_2">DOI</a>.</li>
  <li><b>Floating-point arithmetic in the Coq system</b>,<br/>
    for the 8th RNC symposium (2008, Santiago de Compostela, Spain).
    <a href="doc/08-rnc8-article.pdf">Paper</a> and
    <a href="doc/08-rnc8-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-01780385">HAL</a>.</li>
  <li><b>Proposing Interval Arithmetic for the C++ Standard</b>,
    with Hervé Brönnimann
    and <a href="https://people.bordeaux.inria.fr/sylvain.pion/">Sylvain Pion</a>,<br/>
    for the 12th SCAN symposium (2006, Duisburg, Germany).
    <a href="doc/06-scan06_1-expose.pdf">Talk</a>.</li>
  <li><b>Proof and certification for an accurate discriminant</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,
    <a href="http://md.srvr.fr/">Marc Daumas</a>,
    and <a href="https://people.eecs.berkeley.edu/~wkahan/">William Kahan</a>,<br/>
    for the 12th SCAN symposium (2006, Duisburg, Germany).
    <a href="doc/06-scan06_2-expose.pdf">Talk</a>.</li>
  <li><b>Assisted verification of elementary functions using Gappa</b>,
    with <a href="http://perso.citi-lab.fr/fdedinec/">Florent de Dinechin</a>
    and <a href="https://www.christoph-lauter.org/">Christoph Lauter</a>,<br/>
    for the SAC'06 symposium (2006, Dijon, France).
    <a href="doc/06-mcms-article.pdf">Paper</a> and
    <a href="doc/05-rr-5683.pdf">extended paper</a>.</li>
  <li><b>When double rounding is odd</b>,
    with <a href="https://www.lri.fr/~sboldo/">Sylvie Boldo</a>,<br/>
    for the 17th IMACS symposium (2005, Paris, France).
    <a href="doc/05-imacs17_1-article.pdf">Paper</a> and
    <a href="doc/05-imacs17_1-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00070603">HAL</a>.</li>
  <li><b>Formal certification of arithmetic filters for geometric predicates</b>,
    with <a href="https://people.bordeaux.inria.fr/sylvain.pion/">Sylvain Pion</a>,<br/>
    for the 17th IMACS symposium (2005, Paris, France).
    <a href="doc/05-imacs17_2-article.pdf">Paper</a> and
    <a href="doc/05-imacs17_2-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00344518">HAL</a>.</li>
  <li><b>Guaranteed proofs using interval arithmetic</b>,
    with <a href="http://md.srvr.fr/">Marc Daumas</a>
    and <a href="https://shemesh.larc.nasa.gov/people/cam/">César Muñoz</a>,<br/>
    for the 17th ARITH symposium (2005, Cape Cod, MA, USA).
    <a href="doc/05-arith17-article.pdf">Paper</a> and
    <a href="doc/05-arith17-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/hal-00164621">HAL</a>,
    <a href="https://dx.doi.org/10.1109/ARITH.2005.25">DOI</a>.</li>
  <li><b>Generating formally certified bounds on values and round-off errors</b>,
    with <a href="http://md.srvr.fr/">Marc Daumas</a>,<br/>
    for the 6th RNC symposium (2004, Schloß Dagstuhl, Germany).
    <a href="doc/04-rnc6-article.ps.gz">Paper</a> and
    <a href="doc/04-rnc6-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00070739">HAL</a>.</li>
  <li><b>The Boost interval library</b>,
    with Hervé Brönnimann
    and <a href="https://people.bordeaux.inria.fr/sylvain.pion/">Sylvain Pion</a>,<br/>
    for the 5th RNC symposium (2003, Lyon, France).
    <a href="doc/03-rnc5-article.ps.gz">Paper</a> and
    <a href="doc/03-rnc5-expose.pdf">talk</a>.
    <a href="https://hal.archives-ouvertes.fr/inria-00348711">HAL</a>.</li>
</ul>


<h3>Invited talks:</h3>

<ul class="dynlist">
  <li><b>Computer arithmetic and formal proofs</b>,<br/>
    for the 30th JFLA workshop (2019, Les Rousses, France).
    <a href="doc/19-jfla30-article.pdf">Paper</a> (in French) and
    <a href="doc/19-jfla30-expose.pdf">talk</a>.</li>
  <li><b>Formal verification of a floating-point elementary function</b>,<br/>
    for the tutorials of the 22nd ARITH conference (2015, Lyon, France).
    <a href="doc/15-arith22-expose.pdf">Talk</a>.</li>
  <li><b>Automating the verification of floating-point algorithms</b>,<br/>
    for the 12th SMT workshop (2014, Vienna, Austria).
    <a href="doc/14-smt12-expose.pdf">Talk</a>.</li>
  <li><b>Automated methods for verifying floating-point algorithms</b>,<br/>
    for MSC (2014, Lyon, France).
    <a href="doc/14-msc-expose.pdf">Talk</a>.</li>
  <li><b>Automations for verifying floating-point algorithms</b>,<br/>
    for the 5th Coq workshop (2013, Rennes, France).
    <a href="doc/13-coq5-expose.pdf">Talk</a>.</li>
  <li><b>Wave equation numerical resolution: a comprehensive mechanized proof of a C program</b>,<br/>
    for the CaCoS workshop (2012, Grenoble, France).
    <a href="doc/12-cacos-expose.pdf">Talk</a>.</li>
  <li><b>Numerical computations and formal methods</b>,<br/>
    for the 3rd RAIM (2009, Lyon, France).
    <a href="doc/09-raim3-expose.pdf">Talk</a>.</li>
  <li><b>IEEE interval standard working group - P1788: current status</b>,
    with William Edmonson,<br/>
    for the 19th ARITH symposium (2009, Portland, OR, USA).
    <a href="doc/09-arith19-article.pdf">Paper</a> and
    <a href="doc/09-arith19-expose.pdf">talk</a> (first part).
    <a href="https://dx.doi.org/10.1109/ARITH.2009.36">DOI</a>.</li>
</ul>

<h3>Some reports:</h3>

<ul class="dynlist">
  <li><b>Directed rounding arithmetic operations</b>,
    with <a href="https://people.bordeaux.inria.fr/sylvain.pion/">Sylvain Pion</a>,<br/>
    for the C++ standardization committee (2009).
    <a href="http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2009/n2899.pdf">Technical report</a>.</li>
  <li><b>A Proposal to add Interval Arithmetic to the C++ Standard Library</b>,
    with Hervé Brönnimann
    and <a href="https://people.bordeaux.inria.fr/sylvain.pion/">Sylvain Pion</a>,<br/>
    for the C++ standardization committee (2006).
    <a href="http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2006/n2137.pdf">Technical report</a>.</li>
  <li><b>Bool_set: multi-valued logic</b>,
    with Hervé Brönnimann
    and <a href="https://people.bordeaux.inria.fr/sylvain.pion/">Sylvain Pion</a>,<br/>
    for the C++ standardization committee (2006).
    <a href="http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2006/n2136.pdf">Technical report</a>.</li>
</ul>

<h2>Software development</h2>

<ul>
  <li><a href="https://www.boost.org/">Boost.Interval</a>: a generic
    interval library for C++.</li>
  <li><a href="http://coq.inria.fr/">Coq</a>&nbsp;: a proof assistant.</li>
  <li><a href="https://coqinterval.gitlabpages.inria.fr/">CoqInterval</a>:
    tactics for proving inequalities on real-valued expressions in Coq.</li>
  <li><a href="http://coquelicot.saclay.inria.fr/">Coquelicot</a>:
    a user-friendly library for real analysis in Coq.</li>
  <li><a href="https://flocq.gitlabpages.inria.fr/">Flocq</a>: a multi-radix
    multi-format multi-precision formalization of floating-point arithmetic
    in Coq.</li>
  <li><a href="https://gappa.gitlabpages.inria.fr/">Gappa</a>: a tool for
    formally verifying numerical applications.</li>
  <li><a href="https://github.com/silene/remake">Remake</a>: a tiny clone
    of make with support for dynamic dependencies.</li>
  <li><a href="http://why3.lri.fr/">Why3</a>: a software verification
    platform.</li>
  <li><a href="https://gitlab.inria.fr/why3/whymp">WhyMP</a>:
    an efficient C library for computing with large integers, verified using Why3.</li>
  <li>Some minor contributions to <a href="http://why.lri.fr/">Why</a> and
    <a href="http://frama-c.cea.fr/">Frama-C</a>.</li>
</ul>

<h2>Projects and grants</h2>

<ul>
  <li><a href="https://cordis.europa.eu/project/id/101001995">Fresco</a> (ERC 101001995).</li>
  <li><a href="https://nuscap.gitlabpages.inria.fr/">NuSCAP</a> (ANR-20-CE48-0014).</li>
  <li><a href="http://fastrelax.gforge.inria.fr/">FastRelax</a> (ANR-14-CE25-0018).</li>
  <li><a href="http://soprano-project.fr/">Soprano</a> (ANR-14-CE28-0020).</li>
  <li><a href="http://verasco.imag.fr/">Verasco</a> (ANR-11-INSE-03).</li>
  <li><a href="http://coquelicot.saclay.inria.fr/">Coquelicot</a> (Digiteo
    cluster and Île-de-France regional council).</li>
  <li><a href="http://fost.saclay.inria.fr/">FOST</a> (ANR-08-BLAN-0246).</li>
</ul>

<h2>Contact information</h2>

<table class="address">
  <tbody>
    <tr>
      <td>E-mail:</td>
      <td><code>guillaume.melquiond@inria.fr</code></td>
    </tr>
    <tr>
      <td>Address:</td>
      <td>LMF - Bâtiment 650<br/>
        Université Paris-Sud<br/>
        91405 ORSAY cedex<br/>
        FRANCE</td>
    </tr>
    <tr>
      <td>Phone:</td>
      <td>+33 1 69 15 70 98</td>
    </tr>
    <!--<tr>
      <td style="text-align: right">Fax:</td>
      <td>+33 1 74 85 42 29</td>
    </tr>-->
  </tbody>
</table>

<h2>Other resources</h2>

<ul>
  <li><a href="http://scholar.google.com/citations?user=SuXuWQwAAAAJ">Google Scholar</a></li>
  <li><a href="https://www.ohloh.net/accounts/silene">Ohloh</a></li>
</ul>

<hr />

<div class="update">Last update: June 16th, 2021.</div>
</body>
</html>

