<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<link rel="icon" href="./favicon.png" />
		<meta name="viewport" content="width=device-width" />
		<style>
			body {
			  background-position: left top;
			  font-family: "Inter", sans-serif;
			  margin: 0;
			  background-repeat: no-repeat;
			}
	  
			* {
			  box-sizing: border-box;
			}
	  
			a {
			  text-decoration: none;
			  color: black;
			}
	  
			nav {
			  position: sticky;
			  top: 0;
			  left: 0;
			  right: 0;
			  margin: 0 80px 0 80px;
			  padding-top: 2rem;
			  padding-bottom: 2rem;
			}
	  
			nav .nav-container {
			  display: flex;
			  justify-content: space-between;
			  align-items: center;
			}
	  
			.nav-links {
			  display: flex;
			  justify-content: flex-end;
			  align-items: center;
			  margin: -1em 0;
			  flex: 1 0 auto;
			}
	  
			.nav-links .link {
			  position: relative;
			  margin: 1em;
			  font-size: 0.85rem;
			  letter-spacing: 1px;
			  color: black;
			}
	  
			.nav-logo {
			  position: relative;
			  line-height: 1;
			  font-size: 1.1rem;
			  color: black;
			}
		  </style>
		
		<link href="./_app/immutable/assets/_layout.65099de4.css" rel="stylesheet">
		<link href="./_app/immutable/assets/_page.abab7d99.css" rel="stylesheet"><title>Имя Фамилия</title><!-- HEAD_svelte-vshy5s_START --><!-- HEAD_svelte-vshy5s_END -->
	</head>
	<body data-sveltekit-preload-data="hover">
		<div style="display: contents">


<nav><div class="nav-container"><a href="/" class="nav-logo" title="Back to Homepage">Матвей Шевцов</a>
        <div class="nav-links"><a href="/about" class="link">Обо мне</a><a href="/blog" class="link">Блог</a><a href="/project" class="link">Портфолио</a><a href="/contact" class="link">Контакты</a></div></div></nav>

<div class="container svelte-1m8mvlz">
    

<div class="container svelte-etkpxf"><div class="info svelte-etkpxf"><div class="animate-background"><div class="container info-container svelte-etkpxf"><div class="info-text svelte-etkpxf"><h1 class="svelte-etkpxf"><p class="animate-text-1 svelte-etkpxf">Персональный сайт,</p>
                    <p class="text-2 svelte-etkpxf">Матвей Шевцов</p></h1></div>
                <h2 class="subtitle svelte-etkpxf">
                </h2>
                <div style="color:black" class="scroll-button animate-scroll svelte-etkpxf" tabindex="0"><a href="/about">Узнать обо мне</a><div class="arrow svelte-etkpxf">→</div></div></div></div></div></div>

<div class="background-div svelte-etkpxf"></div>
</div>


			
			<script>
				{
					__sveltekit_to3qk8 = {
						base: new URL(".", location).pathname.slice(0, -1),
						env: {}
					};

					const element = document.currentScript.parentElement;

					const data = [null,null];

					Promise.all([
						import("./_app/immutable/entry/start.1ee0651f.js"),
						import("./_app/immutable/entry/app.73eb89e8.js")
					]).then(([kit, app]) => {
						kit.start(app, element, {
							node_ids: [0, 7],
							data,
							form: null,
							error: null
						});
					});
				}
			</script>
		</div>
	</body>
</html>
