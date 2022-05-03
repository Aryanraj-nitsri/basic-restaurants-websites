# basic-restaurants-websites
I have created this website using HTML and CSS .I have used media query to make website responsive.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My resturant</title>
    <!-- lets start styling -->
    <style>
        
        *{
            box-sizing: border-box;
        }
        #box3>p {
            font-size: 2rem;
            font-weight: bold;
        }
        
        #box3 {
            margin-top: 5rem;
            text-align: center;
            color: #393b37;
            
        }
        
        #box1 {
            /* position: static; */
            margin-bottom: 0px;
        }
        
        #box1 ul {
            /* created ul box flex box */
            display: flex;
            flex-direction: row;
        }
        
        /* remove text decoration and list styling */
        ul>li {
            list-style-type: none;
            padding: 0rem 7rem;
        }
        
        ul>li>a {
            text-decoration: none;
            font-size: 1rem;
            color: #393b37;
            
        }
        #navbar>ul>li>a:hover{
            color:red;            
        }
        
        
        #box2::before {
            background: url(bc1.jpg) no-repeat center center/cover;
            content: '';
            position: absolute;
            width: 100vw;
            height:21rem;
            z-index: -1;
            opacity: 0.4;
            left: 0px;
            top: 3rem;
            
            
        }
        
        
        #box2 {
            margin-top: 8rem;
            text-align: center;
            font-size: 1rem;
            color: #252b2b;
            height: 11rem;
        }
        
        #box2>h1 {
            color: #090552;
        }
        
        #box4 {
            margin-top: 3rem;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            
            
        }
        
        #img1 {
            width: 8rem;
        }
        
        #img3 {
            width: 8rem;
            height: 8rem;
        }
        
        #para2 {
            margin-top: 3rem;
            font-weight: bold;
            font-size: 2rem;
            text-align: center;
            color: #393b37;
        }
        
        .photo {
            padding: 1rem 4rem;
        }
        
        #box7 {
            display:flex;
            /* flex-wrap: wrap; */
            
        }
        
        .cl {
            border: 2px solid red;
            height: 24rem;
            border-radius: 2rem;
            text-align: center;
            margin: 0px 13px;
        }
        
        .fr {
            display: block;
            width: 12rem;
            height: 9rem;
            border-radius: 74px;
            margin: 18px auto;
            
        }
        
        .cl>p {
            margin: 2rem auto;
            
        }
        
        
        
        #box6{
            height:3rem;
            width: 100%;
            background-color: black;
            color: white;
            text-align: center;
            padding-top:1rem;
        }
        
        </style>
<link rel="stylesheet" href="media.css">
</head>

<body>

    <!-- fromm here  heading begins -->
    <header>

        <div id="box1" class="item">
            <nav id="navbar">
                <ul>
                    <li class="li" id="ele2"><a href="http://google.com">Home</a></li>
                    <li class="li" id="ele1"><a href="http://google.com">Services</a></li>
                    <li class="li" id="ele3"><a href="http://google.com">gallery</a></li>
                    <li class="li" id="ele4"><a href="http://google.com">Aboutus</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <!-- from here secion begins -->
    <section>

        <div id="box2" class="item">
            <h1>Welcome to our Restuarent</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui cum officiis quidem doloremque
                inventoreplaceat facere commodi facilis temporibus, dignissimos est non asperiores, molestiae voluptas
                possimusenim eius repellat impedit repellendus iusto. Dolorum, necessitatibus.Lorem ipsum dolor sit
                ametconsectetur adipisicing elit. Aliquam, dolore voluptas dolorem praesentium cumvoluptatibus molestias
                ipsam tempora .</p>
        </div>
        <div id="box3" class="item">
            <p>OUR BEST DISHES</p>
        </div>
        <div id="box7" class="item">
            <div id="f1" class="cl"><img src="pizza.jpg" alt="404 error" class="fr">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab, quia? Nobis commodi corrupti, eaque
                    error ad est quisquam soluta nisi tenetur aut magnam fuga vel, ipsa quae eligendi dignissimos,
                    beatae officiis nam? Nostrum neque sequi natus doloremque dolores praesentium, ex eos minima.
                    Nostrum animi, repellat illo blanditiis commodi voluptatibus! Magnam natus nesciunt perspiciatis
                    officia saepe! Animi ad esse debitis voluptates hic totam, dolores nulla eligendi adipisci natus
                    alias?</p>
            </div>
            <div id="f2" class="cl"><img src="pasta.jpg" alt="404 error" class="fr">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab, quia? Nobis commodi corrupti, eaque
                    error ad est quisquam soluta nisi tenetur aut magnam fuga vel, ipsa quae eligendi dignissimos,
                    beatae officiis nam? Nostrum neque sequi natus doloremque dolores praesentium, ex eos minima.
                    Nostrum animi, repellat illo blanditiis commodi voluptatibus! Magnam natus nesciunt perspiciatis
                    officia saepe! Animi ad esse debitis voluptates hic totam, dolores nulla eligendi adipisci natus
                    alias?</p>
            </div>
            <div id="f3" class="cl"><img src="chaumin.jpg" alt="404 error" class="fr">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab, quia? Nobis commodi corrupti, eaque
                    error ad est quisquam soluta nisi tenetur aut magnam fuga vel, ipsa quae eligendi dignissimos,
                    beatae officiis nam? Nostrum neque sequi natus doloremque dolores praesentium, ex eos minima.
                    Nostrum animi, repellat illo blanditiis commodi voluptatibus! Magnam natus nesciunt perspiciatis
                    officia saepe! Animi ad esse debitis voluptates hic totam, dolores nulla eligendi adipisci natus
                    alias?</p>
            </div>
        </div>
        <div id="partner">
            <P id="para2">OUR PARTNERS</P>
        </div>
        <div id="box4" class="item">
            <div id="p1" class="photo"><img src="p1.png" alt="404 error" id="img1"></div>
            <div id="p1" class="photo"><img src="z1.png" alt="404 error"></div>
            <div id="p1" class="photo"><img src="s2.png" alt="404 error" id="img3"></div>
        </div>
    </section>
    <!-- from here footer begins -->
    <footer>
        <div id="box6" class="item">
            <span>

                Copyright &copy;2022Aryan raj 
            </span>
            
        </div>
    </footer>

</body>

</html>
