<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ananya Stationery</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f4f8ff;
}

header{
    background:linear-gradient(135deg,#6a11cb,#2575fc);
    color:white;
    padding:70px 20px;
    text-align:center;
}

header h1{
    font-size:48px;
    margin-bottom:10px;
}

header p{
    font-size:20px;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
    margin:50px 0;
}

.card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card h3{
    color:#2575fc;
    text-align:center;
    margin-top:15px;
}

.card p{
    padding:15px;
    text-align:center;
    color:#555;
}

.contact{
    background:white;
    padding:50px;
    border-radius:15px;
    margin-bottom:40px;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
}

.contact h2{
    color:#2575fc;
    margin-bottom:20px;
    text-align:center;
}

.contact p{
    font-size:18px;
    margin:12px 0;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
</style>

</head>
<body>

<header>
    <h1>🖊️ Ananya Stationery</h1>
    <p>Innovative • Creative • Stylish</p>
</header>

<div class="container">

<section class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1517842645767-c639042777db?auto=format&fit=crop&w=600&q=80" alt="Pens">
<h3>Premium Pens</h3>
<p>Elegant pens for school, office and professionals.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1516979187457-637abb4f9353?auto=format&fit=crop&w=600&q=80" alt="Notebooks">
<h3>Designer Notebooks</h3>
<p>Stylish notebooks for students and creative minds.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1455390582262-044cdead277a?auto=format&fit=crop&w=600&q=80" alt="Art Supplies">
<h3>Art & Craft</h3>
<p>Everything for artists, hobbyists and school projects.</p>
</div>

</section>

<section class="contact">

<h2>Contact Us</h2>

<p><strong>📞 Mobile:</strong> 9284485735</p>

<p><strong>📍 Address:</strong><br>
Sai Mandir Samor,<br>
Main Road, Unchgaon
</p>

<p><strong>🛍️ Products Available:</strong><br>
Pens, Pencils, Notebooks, School Bags, Files, Office Supplies,
Art & Craft Materials, Gift Items, Printing Accessories and More.</p>

</section>

</div>

<footer>
© 2026 Ananya Stationery | Innovative • Creative • Stylish
</footer>

</body>
</html>
