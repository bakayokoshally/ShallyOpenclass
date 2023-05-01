<!DOCTYPE html>
<html lang="fr">
	<head>
		<meta charset="UTF-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<script src="https://kit.fontawesome.com/4a2f2722a9.js" crossorigin="anonymous"></script>
		<link href='https://fonts.googleapis.com/css?family=Shrikhand' rel='stylesheet'>
		<link href='https://fonts.googleapis.com/css?family=Roboto' rel='stylesheet'>
		<link rel="stylesheet" href="styles.css">
		<title>OhMyFood</title>
	</head>
	<body>
		<!--Haut Principal-->
		<header class="header">
			<img class="headerlogo" src="img/ohmyfood.png" alt="logo OhMyfood">
		</header>
		<main>
			<section class="lieu">
				<i class="fa-map-marker-alt fas lieu__icon"></i>
				<input class="lieu__text" placeholder="Paris, Belleville">
			</section>
			<section class="hero">
				<h1 class="hero__title">Réservez le menu qui vous convient <br></h1>
				<p class="hero__subtitle">
					 Découvrez des restaurants d'exception, séléctionnés par nos soins.
				</p>
				<a class="hero__button"> Explorer nos restaurants </a>
			</section>
			<!--Navigation Fonctionnement-->
			<section class="functioning container">
				<h1 class="ftitle">Fontionnement</h1>
				<div class="choix-list">
					<div class="choix-list_cards">
						<p class="number">
							1
						</p>
						<i class="fas fa-mobile-alt" aria-hidden="true"></i>
						<p class="choix">
							Choisissez un restaurant
						</p>
					</div>
					<div class="choix-list_cards">
						<p class="number">
							2
						</p>
						<i class="fas fa-list-ul" aria-hidden="true"></i>
						<p class="choix">
							Composez votre menu
						</p>
					</div>
					<div class="choix-list_cards">
						<p class="number">
							3
						</p>
						<i class="fas fa-store" aria-hidden="true"></i>
						<p class="choix">
							Dégustez au restaurant
						</p>
					</div>
				</div>
			</section>
		</main>
	</body>
</html>
