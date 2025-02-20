<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Website</title>
    <!-- <link rel="stylesheet" href="style.css"> -->
    <style>
        
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}

body {
    min-height: 100vh;
}

header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 30px 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

#logo {
    font-size: 2em;
    color: #fff;
    user-select: none;
    font-weight: 600;
}

.menu a {
    font-size: 0.8em;
    color: #fff;
    font-weight: 500;
    text-decoration: none;
    margin-left: 20px;
    letter-spacing: 1px;
    padding: 6px 15px;
    border-radius: 8px;
    transition: 0.5s;
}

.menu a:hover,
a.active {
    color: #333;
    background: #fff;
}

.parallax {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: url('images/background.jpg') no-repeat;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}

#heading {
    position: absolute;
    top: 20%;
    font-size: 4em;
    color: #fff;
    text-shadow: 2px 4px 5px #232121;
}

.parallax img {
    position: absolute;
    width: 100%;
    pointer-events: none;
}

.parallax img#moon {
    width: 300px;
    top: 40%;
    right: 20%;
}

.parallax img#mountain {
    position: fixed;
    bottom: 0;
}

.parallax img#grass {
    bottom: -40%;
}

section {
    position: relative;
    background-color: #020912;
    padding: 30px 100px;
}

h2 {
    color: #fff;
    font-size: 3em;
    margin-bottom: 25px;
}

p {
    color: #fff;
    font-size: 1em;
    font-weight: 300
}

@media (max-width: 768px) {
    header {
        padding: 30px 50px;
    }

   #heading {
        font-size: 3em;
    }

   .parallax img#moon {
        width: 180px;
    }

   .parallax img#mountain {
        bottom: 20%;
    }

  .parallax img#grass {
        bottom: -10%;
    }

   section {
        margin-top: -60px;
        padding: 30px 50px;
    }

   section h2 {
        font-size: 2em;
    }
}

@media (max-width: 468px) {
    header {
        padding: 30px 50px;
    }

   #logo {
        font-size: 1.5em;
    }

  .menu {
        display: none;
    }

#heading {
        font-size: 3em;
    }

  .parallax img#moon {
        width: 180px;
        top: 65%;
        right: 10%;
    }

   .parallax img#mountain {
        width: 130%;
        bottom: 20%;
    }

  .parallax img#grass {
        bottom: -5%;
        width: 130%;
    }

  section {
        margin-top: -60px;
        padding: 30px 50px;
    }

  section h2 {
        font-size: 2em;
    }
}

.footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}
.footer a {
    color: #ffcc00;
    text-decoration: none;
    margin: 0 10px;
}
.footer a:hover {
    text-decoration: underline;
}

  </style>
</head>

<body>
    <header>
        <div id="logo">
            KNECT

   </div>

   <div class="menu">
            <a href="" class="active">Home</a>
            <a href="">Blog</a>
            <a href="">About</a>
            <a href="">Contact</a>
        </div>
    </header>

  <div class="parallax">
        <h2 id="heading">Website</h2>
        <img src="images/moon.png" alt="" id="moon">
        <img src="images/layer.png" alt="" id="mountain">
        <img src="images/grass.png" alt="" id="grass">
    </div>

    
   <section>
        <h2> Website</h2>
        
<p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste sunt numquam tempora eligendi ipsa commodi, ex
            magni fugit in consequuntur velit, cupiditate illum? Animi, cupiditate eligendi iure sit facilis repudiandae
            unde dicta numquam magni illo reiciendis ea quasi rerum corporis explicabo consectetur nisi maiores
            temporibus. Officiis quod iusto voluptas fugit illo cupiditate necessitatibus quos tempore saepe corrupti
            sed, odit vel quis rerum itaque consequuntur ea harum veniam ab laboriosam accusamus quibusdam nihil!
            Doloremque perferendis placeat minima at ut vero cum atque, nesciunt unde iste aspernatur consequuntur
            voluptatem, deserunt officiis delectus similique quis neque dolor officia, nisi laudantium ipsa cupiditate!
            Architecto nesciunt exercitationem in neque temporibus, ut quisquam minima repellendus, hic totam est
            dolorem numquam accusantium incidunt eum aliquam? Cumque, commodi?
       </p><br>
        
   <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consequatur doloribus labore dignissimos? Ad,
            quas? Maxime, dolorem. Velit iure possimus non quidem similique provident modi eius soluta dolorum,
            quibusdam doloremque impedit dolorem, repellendus cupiditate! Facere necessitatibus distinctio iste
            voluptates aperiam quisquam laboriosam ab nulla sunt recusandae, nemo laudantium sapiente? Consequuntur
            temporibus assumenda ipsum deleniti eligendi quam libero minus tempora aliquid neque?
        </p><br>
        
  <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore minima earum assumenda soluta temporibus
            ipsum, modi aperiam, sint iusto rerum ad quis natus voluptatibus inventore corporis! Libero ad non
            exercitationem.
        </p><br>
        
   <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Officia minima sit vero laborum quidem, mollitia
            reiciendis praesentium perferendis aperiam dolor placeat odit minus, distinctio aut obcaecati molestiae?
            Doloribus, voluptatum provident.
        </p><br>
        
   <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo natus suscipit sed laboriosam officia beatae
            quisquam, magnam, vel ab, veritatis eum consequatur ducimus numquam non quod repellat! Quia doloremque
            animi, voluptates laudantium iusto eaque corporis fugiat aspernatur excepturi? Porro architecto iusto
            perferendis labore possimus consectetur rerum obcaecati saepe, molestiae totam ea dolorem qui ad quisquam
            provident ducimus aut maiores quas, nemo dolor! Doloribus natus dolores illo architecto, saepe perspiciatis
            ab placeat cumque labore repellendus accusantium atque deserunt numquam eveniet, mollitia beatae, tenetur
            amet nulla. Numquam aliquid enim eaque neque accusantium amet architecto nesciunt nam at hic, maiores
            perferendis porro ipsam assumenda veniam. Quia itaque earum quis corporis consequuntur voluptate
            voluptatibus! Porro nesciunt unde saepe sunt excepturi non praesentium quia ullam est earum dolore, officiis
            necessitatibus natus consequuntur eos laudantium suscipit harum. Illum aspernatur tenetur incidunt animi
            laboriosam possimus sapiente eaque eligendi totam iure cupiditate provident reiciendis illo, qui quod cumque
            ad sed, delectus rem ipsa minima pariatur fuga? Ipsa ut suscipit odio illo natus repellendus beatae, atque
            velit adipisci aspernatur soluta modi sapiente nulla, placeat accusamus possimus. Neque deleniti autem
            expedita quasi consequuntur possimus voluptatibus, eligendi rerum commodi veniam vel eius ab! Doloremque
            totam amet possimus error asperiores, fuga voluptatibus.
        </p><br>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur ex eveniet suscipit quaerat quasi
            laudantium, eum beatae, voluptate laboriosam tempora aliquid non nihil soluta, accusamus nobis? Adipisci
            eveniet quam ab. Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro ea accusantium, dolorem
            consequatur delectus non libero odio voluptatibus magnam est ipsum atque, dignissimos voluptate corrupti cum
            fugit ullam nam reiciendis! Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem
            voluptates, laudantium, officia excepturi sapiente dolorum ipsam, repudiandae voluptatibus quibusdam
            corrupti blanditiis similique fuga? Consequuntur nulla quas aut quasi et labore! Lorem ipsum dolor sit amet
            consectetur adipisicing elit. Dignissimos itaque quis minus magni tempore odio doloremque numquam. Eius
            perferendis natus molestiae ab! Facere inventore sed in iste? Ipsum, itaque est.
        </p>
        
   <footer class="footer">
            <p>&copy; 2025 YourWebsite. All rights reserved.</p>
            <p>
                <a href="#">Privacy Policy</a> |
                <a href="#">Terms of Service</a> |
                <a href="#">Contact Us</a>
            </p>
        </footer>
    </section>
    
</body>

</html>
