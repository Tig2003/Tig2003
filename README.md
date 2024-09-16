<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tecnologia Mesada</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRTzL5l3FCGSlCuWDzg5dOFOYF7x6t6bbjB0hR0XEFcdywfcikRLLTI0qbR&s=10');
            background-size: cover;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        .container {
            padding-top: 50px;
        }

        h1 {
            color: white;
            font-size: 48px;
            margin-bottom: 20px;
        }

        .main-image {
            width: 300px;
            height: auto;
            margin-bottom: 20px;
        }

        .contact-info {
            color: white;
            font-size: 20px;
            margin-bottom: 30px;
        }

        .links {
            display: flex;
            justify-content: center;
            margin-bottom: 30px;
        }

        .link-box {
            border: 3px solid green; /* Bordas V */
            padding: 20px;
            margin: 0 15px;
            font-size: 18px;
            color: white;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .link-box:hover {
            border-color: lightgreen; /* Bordas BV */
            transform: scale(1.1);
        }

        .link-box a {
            color: white;
            text-decoration: none;
        }

        .moving-images {
            display: flex;
            justify-content: center;
        }

        .moving-images img {
            width: 100px;
            height: auto;
            margin: 0 10px;
            animation: move 2s infinite alternate;
            cursor: pointer;
        }

        @keyframes move {
            0% { transform: translateY(0); }
            100% { transform: translateY(-10px); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Tecnologia Mesada</h1>

        <img src="https://cdn.dribbble.com/userupload/10951018/file/original-d53f68cdc20daa2a2f31037fed7375e2.gif" alt="Foto maior" class="main-image">

        <div class="contact-info">
            <p>Thiago Migliano Santos</p>
            <p>Email: tiagomedrado12@gmail.com</p>
            <p>Contato: +55 (73) 98101-9503</p>
        </div>

        <div class="links">
            <div class="link-box"><a href="https://www.mercadolivre.com.br" target="_blank">Mercado Livre</a></div>
            <div class="link-box"><a href="https://www.casasbahia.com.br" target="_blank">Casa Bahia</a></div>
            <div class="link-box"><a href="https://www.shopee.com.br" target="_blank">Shopping</a></div>
        </div>

        <div class="moving-images">
            <a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTPcMr_HuaHwkRGaHYZwZztRGFubtr8nOc4Eg&usqp=CAU">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTPcMr_HuaHwkRGaHYZwZztRGFubtr8nOc4Eg&usqp=CAU" alt="Foto 1">
            </a>
            <a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS58QW1udJlQP2xrBk6NSQvW84VebkNdgJgg0wMlKOHpA&s">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS58QW1udJlQP2xrBk6NSQvW84VebkNdgJgg0wMlKOHpA&s" alt="Foto 2">
            </a>
            <a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRTzL5l3FCGSlCuWDzg5dOFOYF7x6t6bbjB0hR0XEFcdywfcikRLLTI0qbR&s=10">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRkmWhEEBTqcSuzTorxlIDpKvJLQCKsnhSLaw&usqp=CAU">
            </a>
        </div>
    </div>
</body>
</html>
