<script>
	import 'bootstrap/dist/css/bootstrap.min.css';
	import about1 from '$lib/images/about1.jpg';
	import about22 from '$lib/images/about22.jpg';
	import ao1 from '$lib/images/ao1.jpg';
	import ao2 from '$lib/images/ao2.jpg';
	import ao3 from '$lib/images/ao3.jpg';
	import ao4 from '$lib/images/ao4.jpg';




</script>
<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>
	  <div class="container-fluid">
		<nav aria-label="breadcrumb">
			<ol class="breadcrumb">
			  <li class="breadcrumb-item"><a href="/">Home</a></li>
			  <li class="breadcrumb-item"><a href="/">Library</a></li>
			  <li class="breadcrumb-item active" aria-current="page">Data</li>
			</ol>
		  </nav>
		<div class="row">
			<div class="col-4">
				<p class="About">
					<span class="About_title">
						About Metagent
					</span>
				</p>
			</div>
		</div>
		<div class="col-12 text-center">
			<h3 style="font-size:30px;color:red;">About Us</h3>
		</div>
		<div class="col-12 text-center">
			<h3 class="title_h3">
				Câu chuyện giá trị thật “Tự hào Made in Vietnam”
			</h3>
		</div>
		
	  </div>
	<div class="container-fluid">
		<div class="row">
			<div class="col-12">
					<img class="img-banner1" src={about1} alt="">
			</div>

		</div>
	</div>
	<div class="container-fluid">
		<div class="row">
			<div class="col-6 about22">
				<p class="text_font">
					Metagent sẵn sàng vượt qua giới hạn của một thương hiệu thời trang nam đơn thuần để chứng tỏ vị thế dẫn đầu phong cách trong thị trường thời trang dành cho Nam giới - Metagent cũng chính là câu chuyện của một thương hiệu Việt nỗ lực khẳng định mình bằng “giá trị thật Made In Vietnam”. Sự minh bạch về sản xuất, áp dụng chuẩn mực quốc tế cho các sản phẩm để phù hợp với người Việt, Metagent với kinh nghiệm lâu năm trong lĩnh vực sản xuất thời trang, tự hào gắn mác “Made In Vietnam” và cạnh tranh công bằng với các thương hiệu nước ngoài về cả chất lượng và giá cả.
				</p>
			</div>
			<div class="col-6">
				<img class="about23" src={about22} alt="">
			</div>
			<div class="col-6">
				<img class="about23" src={about22} alt="">
			</div>
			<div class="col-6 about22">
				<p class="text_font">
					Metagent sẵn sàng vượt qua giới hạn của một thương hiệu thời trang nam đơn thuần để chứng tỏ vị thế dẫn đầu phong cách trong thị trường thời trang dành cho Nam giới - Metagent cũng chính là câu chuyện của một thương hiệu Việt nỗ lực khẳng định mình bằng “giá trị thật Made In Vietnam”. Sự minh bạch về sản xuất, áp dụng chuẩn mực quốc tế cho các sản phẩm để phù hợp với người Việt, Metagent với kinh nghiệm lâu năm trong lĩnh vực sản xuất thời trang, tự hào gắn mác “Made In Vietnam” và cạnh tranh công bằng với các thương hiệu nước ngoài về cả chất lượng và giá cả.
				</p>
			</div>
		</div>
	</div>
	<div class="container-fluid sss">
		<div class="row">
			<div class="col-3">
				<div class="card" style="width: 18rem;">
					<img class="proc_1"  src={ao1} alt="">
					<div  class="card-body">
					  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					  <div>
						<p class="abc">
						   1.200.000đ
					   </p>
					 <p class="dcmm">
					   995.000đ
				   </p>
					</div>
					</div>
				  </div>
			</div>
			<div class="col-3">
				<div class="card" style="width: 18rem;">
					<img class="proc_1"  src={ao2} alt="">
					<div class="card-body">
					  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					  <div>
						<p class="abc">
						   1.200.000đ
					   </p>
					 <p class="dcmm">
					   995.000đ
				   </p>
					</div>
					</div>
				  </div>
			</div>
			<div class="col-3">
				<div class="card" style="width: 18rem;">
					<img class="proc_1" src={ao3} alt="">
					<div class="card-body">
					  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					  <div>
						<p class="abc">
						   1.200.000đ
					   </p>
					 <p class="dcmm">
					   995.000đ
				   </p>
					</div>
					</div>
				  </div>
			</div>
			<div class="col-3">
				<div class="card" style="width: 18rem;">
					<img class="proc_1"  src={ao4} alt="">
					<div class="card-body">
					  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					 <div>
						 <p class="abc">
							1.200.000đ
						</p>
					  <p class="dcmm">
						995.000đ
					</p>
					 </div>
					</div>
				  </div>
			</div>
			
		</div>

	</div>
<style>
	.sss{
		padding-top: 10px;
	}
	.About{
		font-weight: 800;
		font-size: 30px;
		line-height: 40px;
		margin-bottom: 32px;
		color: #221F20;
		
	}
	.About_title{
		background: linear-gradient(90deg, #0cccfc 0%, #28316E 100%);
		-webkit-background-clip: text;
		-webkit-text-fill-color:transparent;
	}
	.title_h3{
		font-family: 'Mulish';
		font-style: normal;
		font-weight: 800;
		font-size: 38px;
		line-height: 52px;
		text-align: center;
		text-transform: uppercase;
		color: #221F20;
		margin-top: 8px;	
	}
	.img-banner1{
		max-width: 100%;
		margin: 0 auto;
		padding-bottom: 20px;
	}
	.text_font{
		/* justify-content: center; */
		padding-top: 100px;
		text-align: justify;
	}
	.about22{
		/* width: 400px;
		height: 400px; */
		background-color: antiquewhite;
	}
	.about23{
		width: 930px;
		height: 450px;
		object-fit: cover;
	}
	.dcmm{
		font-size: 30px;
		font-weight: bold;
	}
	.abc{
		float: right;
		text-decoration: line-through;
	}
	.proc_1 {
		transition: transform .2s;
		width: 18rem;
		height: 495px;
		margin-bottom: 16px;
		padding-left: 10px;
		padding-bottom: 10px;
		padding-top: 10px;
		/* border-radius: 30px; */
		
	}
	.proc_1:hover{
	
		-ms-transform: scale(1.1); /* IE 9 */
		-webkit-transform: scale(1.1); /* Safari 3-8 */
		transform: scale(1.1);
	}
</style>