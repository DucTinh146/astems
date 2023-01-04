<script>
	import 'bootstrap/dist/css/bootstrap.min.css';
	import logo from '$lib/images/123.jpg';
</script>
<svelte:head>
	<title>Login</title>
	<meta name="description" content="About this app" />
</svelte:head>
<div class="wrapper">
	<div class="logo">
		<img src="https://scontent.fhan4-1.fna.fbcdn.net/v/t1.6435-1/141750606_123140022995026_4710703695795988991_n.jpg?stp=dst-jpg_p320x320&_nc_cat=105&ccb=1-7&_nc_sid=7206a8&_nc_ohc=6YC4A6edOf0AX9D5_lr&_nc_ht=scontent.fhan4-1.fna&oh=00_AfCEZms0HxW-hluZxT7Ow0_FbMFihiwicJpyL63l6Ae4Cw&oe=63D2297A" alt="">
	</div>
	<div class="text-center mt-4 name">
		LOGIN
	</div>
	<form class="p-3 mt-3">
		<div class="form-field d-flex align-items-center">
			<span class="far fa-user"></span>
			<input type="text" name="userName" id="userName" placeholder="Username">
		</div>
		<div class="form-field d-flex align-items-center">
			<span class="fas fa-key"></span>
			<input type="password" name="password" id="pwd" placeholder="Password">
		</div>
		<button class="btn mt-3">Login</button>
	</form>
	<div class="text-center fs-6">
		<a href="/">Forget password?</a> or <a href="/">Sign up</a>
	</div>
</div>	

<style>
	/* Importing fonts from Google */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap');

/* Reseting */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: #ecf0f3;
}

.wrapper {
    max-width: 350px;
    min-height: 500px;
    margin: 80px auto;
    padding: 40px 30px 30px 30px;
    background-color: #ecf0f3;
    border-radius: 15px;
    box-shadow: 13px 13px 20px #cbced1, -13px -13px 20px #fff;
}

.logo {
    width: 80px;
    margin: auto;
}

.logo img {
    width: 100%;
    height: 80px;
    object-fit: cover;
    border-radius: 50%;
    box-shadow: 0px 0px 3px #5f5f5f,
        0px 0px 0px 5px #ecf0f3,
        8px 8px 15px #a7aaa7,
        -8px -8px 15px #fff;
}

.wrapper .name {
    font-weight: 600;
    font-size: 1.4rem;
    letter-spacing: 1.3px;
    padding-left: 10px;
    color: #555;
}

.wrapper .form-field input {
    width: 100%;
    display: block;
    border: none;
    outline: none;
    background: none;
    font-size: 1.2rem;
    color: #666;
    padding: 10px 15px 10px 10px;
    /* border: 1px solid red; */
}

.wrapper .form-field {
    padding-left: 10px;
    margin-bottom: 20px;
    border-radius: 20px;
    box-shadow: inset 8px 8px 8px #cbced1, inset -8px -8px 8px #fff;
}

.wrapper .form-field .fas {
    color: #555;
}

.wrapper .btn {
    box-shadow: none;
    width: 100%;
    height: 40px;
    background-color: #03A9F4;
    color: #fff;
    border-radius: 25px;
    box-shadow: 3px 3px 3px #b1b1b1,
        -3px -3px 3px #fff;
    letter-spacing: 1.3px;
}

.wrapper .btn:hover {
    background-color: #039BE5;
}

.wrapper a {
    text-decoration: none;
    font-size: 0.8rem;
    color: #03A9F4;
}

.wrapper a:hover {
    color: #039BE5;
}

@media(max-width: 380px) {
    .wrapper {
        margin: 30px 20px;
        padding: 40px 15px 15px 15px;
    }
}
</style>