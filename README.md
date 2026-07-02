<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FlixPin</title>

<style>
body{
    margin:0;
    background:#111;
    color:white;
    font-family:Arial,sans-serif;
}

header{
    background:#000;
    padding:15px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:red;
    font-size:30px;
    font-weight:bold;
}

input{
    padding:8px;
    border-radius:20px;
    border:none;
    width:180px;
}

.movies{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
    gap:15px;
    padding:20px;
}

.card{
    background:#222;
    border-radius:10px;
    overflow:hidden;
    transition:0.3s;
}

.card:hover{
    transform:scale(1.05);
}

.card img{
    width:100%;
}

.card h3{
    text-align:center;
}
</style>
</head>

<body>

<header>
<div class="logo">FLIXPIN</div>
<input type="text" placeholder="Search...">
</header>

<div class="movies">

<div class="card">
<img src="https://picsum.photos/300/450?1">
<h3>Movie 1</h3>
</div>

<div class="card">
<img src="https://picsum.photos/300/450?2">
<h3>Movie 2</h3>
</div>

<div class="card">
<img src="https://picsum.photos/300/450?3">
<h3>Movie 3</h3>
</div>

<div class="card">
<img src="https://picsum.photos/300/450?4">
<h3>Movie 4</h3>
</div>

</div>

</body>
</html>
section class="hero">
    <h1>Welcome to FlixPin</h1>
    <p>Watch movies, series and discover amazing content.</p>
    <button>▶ Watch Now</button>
</section>.hero{
    height:350px;
    background:linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.9)),
    url("https://picsum.photos/1200/600");
    background-size:cover;
    display:flex;
    flex-direction:column;
    justify-content:center;
    padding:40px;
}

.hero h1{
    font-size:45px;
    margin:0;
}

.hero p{
    font-size:18px;
    width:300px;
}

.hero button{
    width:150px;
    padding:12px;
    border:none;
    border-radius:5px;
    background:red;
    color:white;
    font-size:16px;
    cursor:pointer;
}
