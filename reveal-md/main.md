---
title: First presentation test
separator: <!--s-->
verticalSeparator: <!--v-->
theme: white
css: custom.css
revealOptions:
    transition: 'fade'
---


# Slide 1 

Content of slide 1.


<!--s-->


# Slide 2 

content of slide 2


<!--s-->

# Some mathematics


$E = mc^2$

Note that you need four slashes to do [matrices](https://github.com/MacDownApp/macdown/issues/535)

$$
\begin{equation}
\begin{bmatrix}
a & b \\\\
c & d
\end{bmatrix}
\end{equation}
$$

$$
\int_0^3\left(\frac{x^3}4-2x^2-e^x\right)dx
$$


<!--s-->

# Including a video 


<iframe frameborder="0" width="100%" height="500pt" src="https://www.youtube.com/embed/Do-wDPoC6GM"></iframe>

<!--s-->

# Lists 

<div id="left">


## Left column

- Bullet 1
- Bullet 2
- Bullet 3 
- Even [links](https://www.google.com)

</div>

<div id="right">



## Right colum

1. List
2. List
3. list 

</div>

<!--s-->

# Second attempt at two columns 

<section>
  <div style="text-align: left; float: left;">
    <p data-markdown>- This is my first left element</p>
    <p data-markdown>- This is my second left element</p>
    <!-- more Elements -->
  </div>

  <div style="text-align: right; float: right;">
    <p data-markdown>- This is my first right element</p>
    <p data-markdown>- This is my second rightelement</p>
    <!-- more Elements -->
  </div>
</section>

<!--s-->

# Third attempt at two columns 

<section data-markdown>
    <h3>Doing two-column (this headline still full-width)</h3>

    <div class='multiCol'>
        <div class='col'>
            Gallia est omnis divisa in partes tres, quarum unam incolunt Belgae, aliam Aquitani, tertiam qui ipsorum lingua Celtae, nostra Galli appellantur.
        </div>
        <div class='col'>
            Qua de causa Helvetii quoque reliquos Gallos virtute praecedunt, quod fere cotidianis proeliis cum Germanis contendunt, cum aut suis finibus eos prohibent aut ipsi in eorum finibus bellum gerunt.
        </div>
    </div>
    And simply more regular full-width text in the following. But hey, there is also:
    <div class='multiCol'>
        <div class='col'>Also works for 3 columns...</div>
        <div class='col'>...as we can show in...</div>
        <div class='col'>...this example here.</div>
    </div>
</section>

<!--s-->

# Embedding raw html 

<iframe frameborder="0" width="100%" height="500pt">
<section>
    <script type="text/template">
        ## Page title
        <div>
            A div with some text and a [link](http://hakim.se).
        </div>
    </script>
</section>
</iframe>


<style>
#left {
	margin: 10px 0 15px 20px;
	text-align: left;
	float: left;
	z-index:-10;
	width:48%;
	font-size: 0.85em;
	line-height: 1.5; 
}

#right {
	margin: 10px 0 15px 0;
	float: right;
	text-align: left;
	z-index:-10;
	width:48%;
	font-size: 0.85em;
	line-height: 1.5; 
}
</style>

<!--s-->

# Good references

- [reveal-md  with custom css at the end](https://medium.com/@mandieq/beautiful-presentations-from-markdown-who-knew-it-could-be-so-easy-d279aa7f787a)
