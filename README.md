<!DOCTYPE html>
<html>

<head>
    <title>Membuat Biodata </title>
</head>

<body>
    <form action="#" style="width: 700px" class="posisi" ;>
        <fieldset class="h">
            <table style="width: 600px;">

                <body style="background-color:hsla(106, 39%, 66%, 0.831)">
                </body>
                <tr>
                    <td rowspan="10" width="100px">
                        <img src="nedison wanimbo.jpg" width="150px" height="200px" border="5">
                    </td>
                </tr>
                <center>
                    <font size="25px">
                        <b>BIODATA</b>
                    </font>
                </center>
                <tr>
                    <td><b>NAMA</b></td>
                    <td>: NEDISON WANIMBO</td>
                </tr>
                <tr>
                    <td><b>NIM</b></td>
                    <td>: 2302438</td>
                </tr>
                <tr>
                    <td><b>TTL</b></td>
                    <td>: JUNUGA 10, APRIL 2005</td>
                </tr>
                <tr>
                    <td><b>ALAMAT</b></td>
                    <td>: NOLOPUR</td>
                </tr>
                <tr>
                    <td><b>JENIS KELAMIN</b></td>
                    <td>: Laki - Laki</td>
                </tr>
                <tr>
                    <td><b>AGAMA</b></td>
                    <td>: KRISTEN</td>
                </tr>
</body>
</html>


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HOME</title>
    <link rel="stylesheet" href="css/tampilan.css">
</head>

<body>
    <div class="badan-utama">

        <style>
            body {
                margin: 0;
                padding: 0;
                box-sizing: border-box;
                font-family: Arial, Helvetica, sans-serif;
            }
            
            body {
                background-color: rgb(225, 83, 83);
            }
            
            .badan-utama {
                max-width: 1080px;
                margin: 20px auto;
                background-color: rgb(102, 113, 106);
                padding: 15px;
                overflow: hidden;
            }
            
            header {
                background-color: crimson;
                color: white;
                padding: 20px;
            }
            
            header h2 {
                margin-bottom: 7px;
                font-size: 35px;
            }
            
            .navigasi ul {
                list-style-type: none;
                margin: 0;
                padding: 0;
                overflow: hidden;
                background-color: darkorange;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 20px;
                font-weight: bold;
            }
            
            * {
                margin: 0;
                padding: 0;
            }
            
            .navbar {
                display: flex;
                align-items: center;
                justify-content: center;
                position: sticky;
                top: 0;
                cursor: pointer;
            }
            
            .background {
                background: rgb(5, 158, 178);
                background-blend-mode: darken;
                background-size: cover;
            }
            
            .nav-list {
                width: 70%;
                display: flex;
                align-items: center;
            }
            
            .logo {
                display: flex;
                justify-content: center;
                align-items: center;
            }
            
            .logo img {
                width: 100px;
                border-radius: 50px;
            }
            
            .nav-list li {
                list-style: none;
                padding: 26px 30px;
            }
            
            .nav-list li a {
                text-decoration: none;
                color: white;
            }
            
            .nav-list li a:hover {
                color: grey;
            }
            
            .rightnav {
                width: 30%;
                text-align: right;
            }
            
            #search {
                padding: 5px;
                font-size: 17px;
                border: 2px solid grey;
                border-radius: 9px;
            }
            
            .firstsection {
                background-color: green;
                height: 400px;
            }
            
            .secondsection {
                background-color: blue;
                height: 400px;
            }
            
            .section {
                background-color: antiquewhite;
                height: 4200px;
            }
            
            .box-main {
                display: flex;
                justify-content: center;
                align-items: center;
                color: black;
                max-width: 80%;
                margin: auto;
                height: 80%;
            }
            
            .firsthalf {
                width: 100%;
                display: flex;
                flex-direction: column;
                justify-content: center;
            }
            
            .secondhalf {
                width: 30%;
            }
            
            .secondhalf img {
                width: 70%;
                border: 4px solid white;
                border-radius: 150px;
                display: block;
                margin: auto;
            }
            
            .text-big {
                font-family: 'Piazzolla', serif;
                font-weight: bold;
                font-size: 35px;
            }
            
            .text-small {
                font-size: 18px;
            }
            
            .btn {
                padding: 8px 20px;
                margin: 7px 0;
                border: 2px solid white;
                border-radius: 8px;
                background: none;
                color: white;
                cursor: pointer;
            }
            
            .btn-sm {
                padding: 6px 10px;
                vertical-align: middle;
            }
            
            .section {
                height: 400px;
                display: flex;
                align-items: center;
                justify-content: center;
                max-width: 90%;
                margin: auto;
            }
            
            .section-Left {
                flex-direction: row-reverse;
            }
            
            .paras {
                padding: 0px 65px;
            }
            
            .thumbnail img {
                width: 250px;
                border: 2px solid black;
                border-radius: 26px;
                margin-top: 19px;
            }
            
            .center {
                text-align: center;
            }
            
            .text-footer {
                text-align: center;
                padding: 30px 0;
                font-family: 'Ubuntu', sans-serif;
                display: flex;
                justify-content: center;
                color: white;
            }
        </style>

        <body>

            <nav class="navbar background">

                <ul class="nav-list">

                    <div class="logo">
                        <img src="nedison wanimbo.jpg" width="10">
                    </div>
                    <h1>
                        <li><button class="btn btn-sm"><a href="#HOME">HOME</a></button></li>
                    </h1>
                    <h1>
                        <li><button class="btn btn-sm"><a href="#ABOUT">ABOUT</a></button></li>
                    </h1>
                    <h1>
                        <li><button class="btn btn-sm"><h3><a href="biodata nedison wanimbo1.html">tentang saya</a></h3></button></li>
                    </h1>
                    <h1>
                        <li><button class="btn btn-sm">  <h3><a href="kontak html.html">kontak</a></h3></button></li>
                    </h1>
                    <h1>
                        <li><button class="btn btn-sm"><h3><a href="syle.css">syle.css</a></h3></button></li>
                    </h1>

                </ul>
                <div class="rightNav">
                    <input type="text" name="search" id="search">
                    <button class="btn btn-sm">Search</button>
                </div>
            </nav>
            <style>
                body {
                    font-family: Arial, sans-serif;
                    background-color: #f5f5f5;
                    margin: 0;
                    padding: 0;
                }
                
                h1 {
                    color: #333;
                    text-align: center;
                    padding-top: 30px;
                }
                
                h2 {
                    color: #666;
                    margin-top: 30px;
                }
                
                p {
                    color: #777;
                    line-height: 1.5;
                }
                
                ul {
                    list-style-type: disc;
                    margin-left: 20px;
                    color: #777;
                }
                
                li {
                    margin-bottom: 10px;
                }
                
                .container {
                    max-width: 800px;
                    margin: 0 auto;
                    padding: 20px;
                    background-color: #fff;
                    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
                }
                /* Warna-warna tambahan */
                
                .bg-blue {
                    background-color: #3498db;
                    color: #fff;
                    padding: 10px;
                    margin-bottom: 20px;
                }
                
                .bg-green {
                    background-color: #2ecc71;
                    color: #fff;
                    padding: 10px;
                    margin-bottom: 20px;
                }
                
                .bg-orange {
                    background-color: #e67e22;
                    color: #fff;
                    padding: 10px;
                    margin-bottom: 20px;
                }
                
                .bg-purple {
                    background-color: #9b59b6;
                    color: #fff;
                    padding: 10px;
                    margin-bottom: 20px;
                }
            </style>
            </head>

            <body>
                <div class="container">
                    <h1 class="bg-blue">Biodata Diri</h1>

                    <h2 class="bg-gr een"></h2>
                    <p>Nama : nedison wanimbo</p>
                    <p>Alamat : perum kaiper lorong salon aceh</p>
                    <p>Tangal lahir : 10 April 2005</p>
                    <p>Nomor Telp : 082196653324</p>

                    <h2 class="bg-orange">Pendidikan</h2>
                    <ul>
                        <li>SD</li>
                        <li>SMP</li>
                        <li>SMK</li>
                        <li>Universitas politeknik negeri manado</li>
                    </ul>
                    <h2 class="bg-purple">Pengalaman kerja</h2>
                    <ul>
                        <li>mahasiswa</li>
                        <li>mahasiswa</li>
                    </ul>

                    <h2 class="bg-orange">minat dan hoby</h2>
                    <ul>
                        <li>Bulutangkis</li>
                        <li>mendengar musik</li>
                        <li>BOla volly</li>
                    </ul>
                </div>
                <footer class="background">

                    <p class="text-footer">
                        ©-by nedisonwanimbo_23_2005
                    </p>
                </footer>
                <h3><a href="biodata nedison wanimbo1.html">Back</a></h3>
                <h3><a href="1234.html">halaman sebelumnya</a></h3>
            </body>

</html>
