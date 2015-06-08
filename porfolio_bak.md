---
layout: porfolio
title:  "n"
subtitle: "by Jorge Drexler"
banner: p_n.jpg
featured:
 - thumb: ecdls.jpg
   name: The Circle of Health
   text: I designed the user experience and developed this iPad and iPhone app for the treatment and prevention of cardiovascular diseases.
   link: p_ecdls.html
 - thumb: n.jpg
   name: n by Jorge Drexler
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_n.html
 - thumb: ecdls.jpg
   name: Contigo
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_contigo.html
 - thumb: ecdls.jpg
   name: Sincrolab
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_sincrolab.html
 - thumb: ecdls.jpg
   name: Tres
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_tres.html
 - thumb: ecdls.jpg
   name: Openbank
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_openbank.html
 - thumb: ecdls.jpg
   name: Funginote
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_funginote.html

old:
 - thumb: ecdls.jpg
   name: The Knot
   text: I designed the user experience and developed this iPad and iPhone app for the treatment and prevention of cardiovascular diseases.
   link: p_theknot.html
 - thumb: n.jpg
   name: ¡Seleccionízate!
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_seleccionizate.html
 - thumb: ecdls.jpg
   name: Contigo
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_contigo.html
 - thumb: ecdls.jpg
   name: Cadiz 2012
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_cadiz2012.html      
 - thumb: ecdls.jpg
   name: Navidad Raphael
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_navidadraphael.html    
 - thumb: ecdls.jpg
   name: Volkswagen Polo
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_volkswagenpolo.html  
 - thumb: ecdls.jpg
   name: Denim Dating
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_denimdating.html       
 - thumb: ecdls.jpg
   name: Trucco
   text: Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros.
   link: p_trucco.html                     
---

<div class="row">
	
	{% for project in page.featured %}

		<div class="4u 12u(narrower)">
			<a href="{{ project.link }}">
			<section class="box special project">
				<span class="image featured"><img src="projects/{{ project.thumb }}" alt="" /></span>
				<h3>{{ project.name }}</h3>
				<p>{{ project.text }}</p>
			</section>
			</a>
		</div>
  
  {% endfor %}      

</div>

<div class="box">						
	<h3>Old stuff</h3>
	<p>Cep risus aliquam gravida cep ut lacus amet. Adipiscing faucibus nunc placerat. Tempus adipiscing turpis non blandit accumsan eget lacinia nunc integer interdum amet aliquam ut orci non col ut ut praesent. Semper amet interdum mi. Phasellus enim laoreet ac ac commodo faucibus faucibus. Curae ante vestibulum ante. Blandit. Ante accumsan nisi eu placerat gravida placerat adipiscing in risus fusce vitae ac mi accumsan nunc in accumsan tempor blandit aliquet aliquet lobortis. Ultricies blandit lobortis praesent turpis. Adipiscing accumsan adipiscing adipiscing ac lacinia cep. Orci blandit a iaculis adipiscing ac. Vivamus ornare laoreet odio vis praesent nunc lorem mi. Erat. Tempus sem faucibus ac id. Vis in blandit. Nascetur ultricies blandit ac. Arcu aliquam. Accumsan mi eget adipiscing nulla. Non vestibulum ac interdum condimentum semper commodo massa arcu.</p>
</div>

<div class="row">
				
	{% for project in page.old %}

		<div class="4u 12u(narrower)">
			<a href="{{ project.link }}">
			<section class="box special project">
				<span class="image featured"><img src="projects/{{ project.thumb }}" alt="" /></span>
				<h3>{{ project.name }}</h3>
				<p>{{ project.text }}</p>
			</section>
			</a>
		</div>
  
  {% endfor %}  
</div>					