# Site-Responsivo

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Cidade inteligentes</title>
</head>
<body>
    <div class="container">
        <div class="navbar">
            <a href="index.html"> <img src="https://user-images.githubusercontent.com/100946873/190887662-a9cacfbc-236e-458b-8483-5fbbd5795917.png" class="logo"></a>
            <nav>
                <ul>
                    <li> <a href="#">PAGINA INICIAL</a></li>
                    <li> <a href="#">REGIÃO</a></li>
                    <li> <a href="#">SOBRE</a></li>
                    <img src="https://user-images.githubusercontent.com/100946873/190887669-e554e8a3-2faa-45eb-9202-63b9aebfcb15.png" class="menu-icon"/>
                </ul>
            </nav>
        </div>
        <div class="row">
            <div class="col">
                <h1>Cidades Inteligentes
                </i></h1>
                <p>
                    Cidades inteligentes no Mundo e como elas podem promover o desenvolvimento sustentável.
                    Smart Cities devem incluir tecnologia em visão multisetorial em seu planejamento urbano.
                </p>
                <button>Explorar</button>
            </div>
            <div class="col">
                <div class="card card1">
                </ul>
                    <h5>New York</h5>
                <img src="https://user-images.githubusercontent.com/100946873/190887584-aed688ae-7247-474e-b795-a74bee781b88.jpg" class="card1"/>
                    <p>
                        A cidade de Nova York compreende 5 distritos situados no encontro do rio Hudson com o Oceano Atlântico
                    </p>
                </div>

                <div class="col">
                    <div class="card card2">
                        <h5>Dubai</h5>
                        <img src="https://user-images.githubusercontent.com/100946873/190887589-437c713d-7256-4231-b55b-a9c9b61df98e.jpg" class="card2"/>
                        <p>
                            Dubai é uma cidade e um emirado dos Emirados Árabes Unidos conhecida pelos shoppings de luxo
                        </p>
            </div>
            <div class="col">
                <div class="card card3">
                    <h5>Roma</h5>
                    <img src="https://user-images.githubusercontent.com/100946873/190887592-afd5d54a-1036-46c0-bfa4-837706474ffa.jpg" class="card3"/>
                    
                    <p>
                        Roma, a capital da Itália, é uma cidade cosmopolita, enorme, com quase 3.000 anos de arte
                    </p>
        </div>
        <div class="col">
            <div class="card card4">
                <h5>Los Angeles</h5>
                 <img src="https://user-images.githubusercontent.com/100946873/190887601-a108c137-8aec-4b1c-9d17-f186fd2f9915.jpg" class="card4"/>
                <p>
                    Los Angeles é uma grande cidade do sul da Califórnia e também o centro da indústria de cinema e televisão do país. 
                </p>
    </div>
</body>
</html>
                  
 @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,900&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
}
.container{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.7),
                                          rgba(0,0,0,0.7)),url(https://user-images.githubusercontent.com/100946873/190887582-cbcda282-963e-4691-8a1b-6146c5a70c6b.jpg);
    background-position:center;
    background-size: cover;
    padding: 0 8%;
}
.navbar{
    height: 12% ;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.logo{
    width: 50px;
    cursor: pointer;
}
.menu-icon{
    width: 30px;
    cursor: pointer;
    margin-left: 40px;
}
nav ul{
    display: flex;
    align-items: center;

}
nav ul li{
    list-style: none;
    margin-left: 30px;
}
nav ul li a{
    text-decoration: none;
    color:white;
    font-size: 13px;
}
.row{
    display: flex;
    height:  88%;
    align-items: center;
}
.col{
    width: 50%;

}
h1{
    color: white;
    font-size: 100px;
}
p{
    color: white;
    font-size: 12px;
   
}
button{
    width: 180px;
    color: black;
    font-size: 12px;
    padding: 12px 0;
    background-color: white;
    border: 0;
    border-radius: 20px;
    margin-top: 30px;
    cursor: pointer;
}
.card{
    width: 200px;
    height: 115px;
    display: run-in;
    border-radius: 10px;
    padding: 10px 15px;
    cursor: pointer;
    margin: 10px 15px;
    background-position: center;
    background-size: cover;
    
    transition: 0.5s;
}
.card:hover{
    transform: translateY(-10px);
}
.card1{
    background-image: url(https://user-images.githubusercontent.com/100946873/190887584-aed688ae-7247-474e-b795-a74bee781b88.jpg);
}
.card2{
    background-image: url(https://user-images.githubusercontent.com/100946873/190887589-437c713d-7256-4231-b55b-a9c9b61df98e.jpg);
}
.card3{
    background-image: url(https://user-images.githubusercontent.com/100946873/190887592-afd5d54a-1036-46c0-bfa4-837706474ffa.jpg);
}
.card4{
    background-image: url(https://user-images.githubusercontent.com/100946873/190887601-a108c137-8aec-4b1c-9d17-f186fd2f9915.jpg);
}
h5{
    color:white;
    font-size: 20px;
}
