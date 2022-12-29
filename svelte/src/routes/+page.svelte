<script>
	// import Counter from './Counter.svelte';
	// import welcome from '$lib/images/svelte-welcome.webp';
	// import welcome_fallback from '$lib/images/svelte-welcome.png';
	import 'bootstrap/dist/css/bootstrap.min.css';
	import {Carousel} from 'bootstrap';
	import "bootstrap-icons/font/bootstrap-icons.css";

	import hinh1 from '$lib/images/banner.jpg';
	import hinh2 from '$lib/images/banner2.jpg';

	import hinh3 from '$lib/images/banner.jpg';
	import proc0 from '$lib/images/proc0.jpg';
	import proc_1 from '$lib/images/proc1.jpg';
	import proc2 from '$lib/images/proc2.jpg';
	import proc3 from '$lib/images/proc3.jpg';
	import banner4 from '$lib/images/banner4.jpg';
	import l1 from '$lib/images/l1.jpg';
	import l2 from '$lib/images/l2.jpg';
	import l3 from '$lib/images/l3.jpg';
	import l4 from '$lib/images/l4.jpg';
	import proc5 from '$lib/images/proc5.jpg';
	import proc6 from '$lib/images/proc6.jpg';
	import proc7 from '$lib/images/proc7.jpg';

	import proc4 from '$lib/images/proc4.jpg';
	import proc8 from '$lib/images/proc8.jpg';









</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<!-- <section>
	<h1>
		<span class="welcome">
			<picture>
				<source srcset={welcome} type="image/webp" />
				<img src={welcome_fallback} alt="Welcome" />
			</picture>
		</span>

		to your new<br />SvelteKit app
	</h1>

	<h2>
		try editing <strong>src/routes/+page.svelte</strong>
	</h2>

	<Counter />
</section> -->

<!--  -->
	<main>
		<!--  -->
		<div class="container-fluid text-center bbb">
			<div class="row">
			  <div class="col-4 ">
				<a class="sss" href="/" >FREE SHIP ĐƠN HÀNG TỪ 2 TRIỆU</a>
			  </div>
			  <div class="col-4 ">
				<a class="aaa" href="/">BẢO HÀNH TRỌN ĐỜI</a>
			  </div>
			  <div class="col-4">
				<a class="ccc" href="/">CHÍNH SÁCH THẺ THÀNH VIÊN</a>
			  </div>
			</div>
		  </div>
		<!-- banner -->
		<div>
			<div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="true">
				<div class="carousel-indicators">
				  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
				  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
				  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
				</div>
				<div class="carousel-inner">
				  <div class="carousel-item active">
					<img src={hinh1} class="d-block w-100" alt="...">
				  </div>
				  <div class="carousel-item">
					<img src={hinh2}  class="d-block w-100" alt="...">
				  </div>
				  <div class="carousel-item">
					<img src={hinh3}  class="d-block w-100" alt="...">
				  </div>
				</div>
				<button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
				  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
				  <span class="visually-hidden">Previous</span>
				</button>
				<button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
				  <span class="carousel-control-next-icon" aria-hidden="true"></span>
				  <span class="visually-hidden">Next</span>
				</button>
			  </div>
		</div>
		<div class="container-fluid text-center">
			<p class="best_seller">
				BEST SELLER
			</p>
		</div>
		<div  class="container-fluid text-center">
			<div class="row">
				<div class="col-3">
					<a href="/"><img class="proc_1" src={proc0} alt=""></a>
					<p class="title_pro">
						Đầm trơn xòe tay lỡ

					</p>
					<p class="dcmm">
						995.000đ

					</p>
				</div>
				<div class="col-3">
					<a href="/"><img class="proc_1" src={proc_1} alt=""></a>
					<p class="title_pro">
						Đầm trơn xòe tay lỡ

					</p>
					<p class="dcmm">
						995.000đ

					</p>
				</div>
				<div class="col-3">
					<a href="/"><img class="proc_1" src={proc2} alt=""></a>
					<p class="title_pro">
						Đầm trơn xòe tay lỡ

					</p>
					<p class="dcmm">
						995.000đ

					</p>
				</div>
				<div class="col-3">
					<a href="/"><img class="proc_1" src={proc3} alt=""></a>
					<p class="title_pro">
						Đầm trơn xòe tay lỡ

					</p>
					<p class="dcmm">
						995.000đ

					</p>
				</div>
		
				<div class="col-3">
					<a href="/"><img class="proc_1" src={proc8} alt=""></a>
					<p class="title_pro">
						Đầm trơn xòe tay lỡ

					</p>
					<p class="dcmm">
						995.000đ

					</p>
				</div>
				<div class="col-3">
					<a href="/"><img class="proc_1" src={proc4} alt=""></a>
					<p class="title_pro">
						Đầm trơn xòe tay lỡ

					</p>
					<p class="dcmm">
						995.000đ

					</p>
				</div>
				<div class="col-3">
					<a href="/"><img class="proc_1" src={proc6} alt=""></a>
					<p  class="title_pro">
						Gina Dress - Đầm xòe cut out
					</p>
					<p class="dcmm">
						995.000đ

					</p>
				</div>
				<div class="col-3">
					<a href="/"><img class="proc_1" src={proc7} alt=""></a>
					<p  class="title_pro">
						Chân váy dạ dáng đuôi cá
					</p>
					<p class="dcmm">
						995.000đ

					</p>
					
			</div>
			<div class="btn123">
				<button class="button"><span>Xem thêm! </span></button>
			</div>
			
		</div>
		<!-- banner4 -->
		<section class="banner4">
			<img class="banner2" src={banner4} alt="">
			<div class="banner4_1">
				<h3 class="img_title">
					Touching Winter
				</h3>
				<p class="img_tile_cap1">
					Wool Collection
				</p>
				<a href="https://metagent.vn/danh-muc/touching-winter" class="btn btn-buy-now">Khám phá ngay</a>
			</div>
		</section>
		<!-- List product  --> 
		<section class="section-list-products product-page">
			<div class="container">
				<div>
					<h1 class="title-page">
						<span class="title-gradient">Wool Collection - Touching Winter</span>
					</h1>
				</div>
			</div>
		</section>
		<div>
			<div class="container-fluid text-center">
				<div class="row">
				  <div class="col-3 dumam">
					<div class="info-ticket">NEW</div>
					<div class="infor-hear">
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-heart" viewBox="0 0 16 16">
							<path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"/>
						  </svg>
					</div>
					<a href="/"><img class="list1" src={l1} alt=""></a>
					<p class="title_proc">
						Eser Set - Set áo lụa và chân váy kèm đai
					</p>
					<p class="dcmm">
						995.000đ

					</p>
				  </div>
				  <div class="col-3 dumam">
					<div class="info-ticket">NEW</div>
					<div class="infor-hear">
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-heart" viewBox="0 0 16 16">
							<path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"/>
						  </svg>
					</div>
					<a href="/"><img class="list1" src={l2} alt=""></a>
					<p class="title_proc">
						Eser Set - Set áo lụa và chân váy kèm đai
					</p>
					<p class="dcmm">
						995.000đ

					</p>
				  </div>
				  <div class="col-3 dumam">
					<div class="info-ticket">NEW</div>
					<div class="infor-hear">
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-heart" viewBox="0 0 16 16">
							<path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"/>
						  </svg>
					</div>
					<a href="/"><img class="list1" src={l3} alt=""></a>
					<p class="title_proc">
						Eser Set - Set áo lụa và chân váy kèm đai
					</p>
					<p class="dcmm">
						995.000đ

					</p>
				  </div>
				  <div class="col-3 dumam">
					<div class="info-ticket">NEW</div>
					<div class="infor-hear">
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-heart" viewBox="0 0 16 16">
							<path d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"/>
						  </svg>
					</div>
					<a href="/"><img class="list1" src={l4} alt=""></a>
					<p class="title_proc">
						Eser Set - Set áo lụa và chân váy kèm đai
					</p>
					<p class="dcmm">
						995.000đ

					</p>

				  </div>
				</div>
				<div class="btn123">
					<button class="button"><span>Xem thêm! </span></button>
				</div>
			  </div>
		</div>
		<!-- pagination -->
		<div>
			<nav aria-label="Page navigation example">
				<ul class="pagination justify-content-center">
				  <li class="page-item">
					<a class="page-link" href="/" aria-label="Previous">
					  <span aria-hidden="true">&laquo;</span>
					  <span class="sr-only">Previous</span>
					</a>
				  </li>
				  <li class="page-item"><a class="page-link" href="/">1</a></li>
				  <li class="page-item"><a class="page-link" href="/">2</a></li>
				  <li class="page-item"><a class="page-link" href="/">3</a></li>
				  <li class="page-item"><a class="page-link" href="/">4</a></li>
				  <li class="page-item"><a class="page-link" href="/">5</a></li>
				  <li class="page-item"><a class="page-link" href="/">6</a></li>
				  <li class="page-item"><a class="page-link" href="/">7</a></li>
				  <li class="page-item"><a class="page-link" href="/">8</a></li>
				  <li class="page-item"><a class="page-link" href="/">9</a></li>
				  <li class="page-item"><a class="page-link" href="/">10</a></li>
				  <li class="page-item">
					<a class="page-link" href="/" aria-label="Next">
					  <span aria-hidden="true">&raquo;</span>
					  <span class="sr-only">Next</span>
					</a>
				  </li>
				</ul>
			  </nav>
		</div>
	</main>


<style>
	.aaa{
		width: 100%;
		text-decoration: none;
		
		
	}
	.bbb{
		height: 25px;
		/* background-color: aqua; */

	}
	.ccc{
		width: 100%;
		text-decoration: none;
	}
	.sss{
		width: 100%;
		text-decoration: none;
	}
	.best_seller{
	text-align: center;
	margin-top: 10px;
    letter-spacing: 5px;
    text-transform: uppercase;
    font-weight: 600;
    font-size: 30px;
    /* line-height: 32px; */
    font-family: 'Montserrat';
    color: #221F20;
}
	
	.proc_1 {
		transition: transform .2s;
		width: 330px;
		height: 495px;
		margin-bottom: 16px;
		padding-left: 10px;
		padding-bottom: 10px;
		padding-top: 10px;
		border-radius: 30px;
		
	}
	.proc_1:hover{
	
		-ms-transform: scale(1.1); /* IE 9 */
		-webkit-transform: scale(1.1); /* Safari 3-8 */
		transform: scale(1.1);
	}
	/* .proc_1:hover{
		opacity: 1;
		transform: scale(1,1);
		width: 370px;
		height: 535px;
		margin-bottom: 16px;
		padding-left: 10px;
		border-radius: 30px;
	} */
	
	
	.banner2{
		max-width: 100%;
		height: auto;
	

	}
	.dcmm{
		text-align: center;
		font-weight: 700;
		text-decoration: line-through;
	}
	 .banner4 {
    position: relative;
	width: 100%;

}
	.banner4_1{
	position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
	}
	.img_title{
		font-family: 'Highway Gothic Expanded';
		font-style: normal;
		font-weight: 400;
		font-size: 80px;
		line-height: 89px;
		text-align: center;
		color: #FFFFFF;
		text-transform: uppercase;
	}
	.img_tile_cap1{
		font-weight: 400;
		font-size: 20px;
		line-height: 30px;
		text-align: center;
		color: #FFFFFF;
		margin-top: 8px;
		margin-bottom: 0;
	}
	.btn {
     /* border: 0; */
	 display: inline-flex;
    justify-content: center;
    align-items: center;
    font-family: "Mulish", sans-serif;
    cursor: pointer;
	background-image: linear-gradient(to right, #4CAD67, #28316E, #28316E, #28316E);
    background-size: 300% 100%;
    border: none;
    border-radius: unset;
    transition: all 0.3s;
}
	 .btn-buy-now{
		height: 56px;
		line-height: 56px;
		min-width: 160px;
		font-weight: 800;
		font-size: 24px;
		text-align: center;
		text-transform: uppercase;
		color: #F7F8F9;
		padding: 0 10px;
		text-decoration: none;
	} 
	
	.section-list-products {
    margin-top: 10px;
}
.container {
    padding-right: 26px;
    padding-left: 26px;
    margin-right: auto;
    margin-left: auto;
    max-width: 100%;
}
.product-page .title-page {
    margin-bottom: 30px;
}
.title-page {
    font-weight: 800;
    font-size: 30px;
    line-height: 40px;
    /* margin-bottom: 32px; */
    color: #221F20;
}
.title-gradient {
    background: linear-gradient(90deg, #4CAD67 0%, #28316E 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    /* background-clip: text;
    text-fill-color: transparent; */
}
/* list producct */
.dumam{
	position: relative;
}
.info-ticket {
    color: #fff;
    font-weight: 700;
    font-size: 12px;
    padding : 4px 12px;
    background: #221F20;
    width: max-content;
	position: absolute;
	top:25px; 
	left:100px;
	/* top: 52px;
    left: 90px; */
}
.list1{
	width: 330px;
	height: 495px;
	margin-left: 10px;
	border-radius: 30px;
	/* position: relative; */
	
}
/* .list1:hover {
	width: 350px;
	height: 515px;
	opacity: 1;
	transform: scale(1,1);
} */
.infor-hear {
	position: relative;
	top: 30px;
	left:151px
}

.title_proc {
		padding-top: 20px;
		font-weight: 700;
		text-align: center;
		color: #070707;
}
/* css button animation */
.button {
  border-radius: 4px;
  background-color: #D22632;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  /* padding: 20px; */
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 0 auto;
  padding-bottom: 10px;
  padding-top: 10px;
  
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
   /* display: flex;
  justify-content: center;
  align-items: center; */
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
.btn123{
	padding-bottom: 100px;
}

</style>
