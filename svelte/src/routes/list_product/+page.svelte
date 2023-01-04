<script>
	import 'bootstrap/dist/css/bootstrap.min.css';
	import hinh1 from '$lib/images/nhin1.jpg';
	import proc5 from '$lib/images/proc5.jpg';
	import {Carousel} from 'bootstrap';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<!-- <div class="container-fluid text-center">
	<div class="row">
		<div class="col-3">
			<img src={hinh1} alt="">
		</div>
		<div class="col-3">
			<img src={hinh1} alt="">
		</div>
		<div class="col-3">
			<img src={hinh1} alt="">
		</div>
		<div class="col-3">
			<img src={hinh1} alt="">
		</div>
	</div>
</div> -->
<div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
	<div class="carousel-inner">
	  <div class="carousel-item active">
		<img src={hinh1} class="d-block image" alt="...">
		<img src={hinh1} class="d-block image" alt="...">
		<img src={hinh1} class="d-block image" alt="...">
		<img src={hinh1} class="d-block image" alt="...">
		<img src={hinh1} class="d-block image" alt="...">
	  </div>
	   <div class="carousel-item">
		<img src={proc5} class="d-block image" alt="...">
		<img src={proc5} class="d-block image" alt="...">
		<img src={proc5} class="d-block image" alt="...">
		<img src={proc5} class="d-block image" alt="...">
		<img src={proc5} class="d-block image" alt="...">

	  </div>
	 <!-- <div class="carousel-item">
		<img src={hinh1} class="d-block w-100 image" alt="...">
	  </div> -->
	</div>
	<button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
	  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
	  <span class="visually-hidden">Previous</span>
	</button>
	<button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
	  <span class="carousel-control-next-icon" aria-hidden="true"></span>
	  <span class="visually-hidden">Next</span>
	</button>
  </div>


<style>
.image{
	width:300px;
	height: 500px;
	float: left;
	margin-left: 3px;
}
</style>