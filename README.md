# Projeto-tec-blog
Curso de Desenvolvedor web 

--> Pagina html <--

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title> TecBlog - O seu Blog de tecnologia</title>
		<link rel="stylesheet" type="text/css" href="css/estilo.css">


</head>
	<body>
		<!-- cabecalho -->
		
		<div id="area-cabecalho">
			
			<div id="area-logo">
				<h1> Tec<span class="branco">Blog</span></h1>
			</div>

			<div id="area-menu">
				<a href="index.html"> Home </a>
				<a href="jogos.html"> Jogos </a>
				<a href="celulares.html"> Celulares </a>
				<a href="informatica.html"> Informática </a>
				<a href="eletronicos.html"> Eletrônicos </a>
				
			</div>

		</div>	
		<!-- fim de cabecalho -->
 
		<div id="area-principal">
			<div id="area-postagens">
				
				
				<!-- abertura postagem -->
				
				<div class="postagem">
					<h2>titulo da postagem 1</h2>
					<span class="data-postagem"> Postado em 20 de outubro de 2022 </span>		
					<img src="imagens/imagem1.jpg">
					<p>
						Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
						tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
						quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
						consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
					</p>
					<a href="">Leia mais</a>
				</div>     <!--// fechamento postagem -->


				<!-- abertura postagem -->
				<div class="postagem">
					<h2>titulo da postagem 2</h2>
					<span class="data-postagem"> Postado em 22 de Dezembro de 2022 </span>		
					<img src="imagens/imagem2.jpg">
					<p>
						Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
						tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
						quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
						consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
					</p>
					<a href="">Leia mais</a>
				</div>     <!--// fechamento postagem -->

			</div>
		<div id="area-lateral">
			
			 <div class="conteudo-lateral">
			 	<h3>Postagens recentes</h3>
			 	
			 	<div class="postagem-lateral"  >
			 		<P>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua.</P>
					<a href="">Leia Mais</a>
			 	</div>


			 	<div class="postagem-lateral" style="border: none;" >
			 		<P>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua.</P>
					<a href="">Leia Mais</a>
				</div>
			</div>

			<div class="conteudo-lateral">
			 	<h3>Categorias</h3>

			 	<a href="">Jogos</a><br>
			 	<a href="">Celulares</a><br>
			 	<a href="">Informática</a><br>
			 	<a href="">Eletrônicos</a><br>
			 

			 	
				</div>
			</div>



		</div>	

		<div id="rodape">
			Todos os direitos reservados.
		</div>

		</div>


	</body>
</html>
