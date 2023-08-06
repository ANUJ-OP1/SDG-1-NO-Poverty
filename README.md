
    <title>SDG 1 - No Poverty</title>
    <style>
        body {
            background: linear-gradient(45deg, #ff0080, #4eff00); /* Vibrant gradient background */
            color: #ffffff; /* White font color */
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
            margin: 0;
        }

        h1 {
            font-size: 50px;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3); /* Shadow for the heading */
        }

        p {
            font-size: 26px;
            margin-bottom: 20px;
        }

        .donate-button {
            display: inline-block;
            padding: 15px 30px;
            font-size: 18px;
            border: 2px solid #ffffff;
            background-color: transparent;
            color: #ffffff;
            text-decoration: none;
            border-radius: 8px;
            transition: background-color 0.3s ease, transform 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Shadow for the button */
            cursor: pointer;
        }

        .donate-button:hover {
            background-color: #ffffff;
            color: #ff0080;
            transform: scale(1.1); /* Slightly scale up on hover */
        }

        .donate-button:active {
            transform: scale(0.9); /* Slightly scale down on click */
        }

        @keyframes glowing {
            0% { box-shadow: 0 0 5px rgba(255, 0, 128, 0.8); }
            50% { box-shadow: 0 0 20px rgba(255, 0, 128, 0.8); }
            100% { box-shadow: 0 0 5px rgba(255, 0, 128, 0.8); }
        }

        .donate-button:focus {
            outline: none;
            animation: glowing 1s infinite; /* Glowing effect on focus */
        }

        .donate-info {
            font-size: 14px;
            color: #ffffff;
            opacity: 0.8;
        }

        .donate-info a {
            color: #ffffff;
            text-decoration: none;
            border-bottom: 1px dotted #ffffff;
        }

        /* Advanced CSS for background animation */
        .background-shapes {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }

        .background-shapes div {
            position: absolute;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            opacity: 0.7;
            animation: move 5s linear infinite;
        }

        @keyframes move {
            0% {
                transform: translateY(0);
                opacity: 0.7;
            }
            50% {
                transform: translateY(-100vh);
                opacity: 0.3;
            }
            100% {
                transform: translateY(-200vh);
                opacity: 0.7;
            }
        }

        /* Advanced CSS for responsive design */
        @media screen and (max-width: 600px) {
            h1 {
                font-size: 40px;
            }

            p {
                font-size: 22px;
            }

            .donate-button {
                font-size: 16px;
                padding: 12px 24px;
            }

            .background-shapes div {
                width: 30px;
                height: 30px;
            }
        }

        /* Advanced CSS for 3D donate button */
        .donate-button-3d {
            display: inline-block;
            padding: 15px 30px;
            font-size: 18px;
            border: none;
            background-color: #ffffff;
            color: #ff0080;
            text-decoration: none;
            border-radius: 8px;
            transition: transform 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Shadow for the button */
            cursor: pointer;
            transform-style: preserve-3d;
            perspective: 1000px;
        }

        .donate-button-3d:hover {
            transform: translateY(-5px) translateZ(20px) rotateX(-10deg); /* 3D transformation on hover */
        }

        .donate-button-3d:active {
            transform: scale(0.9); /* Slightly scale down on click */
        }
    </style>
</head>
<body>
    <!-- Background animation -->
    <div class="background-shapes">
        <div style="background-color: #ff0080; top: 10%; left: 10%;"></div>
        <div style="background-color: #4eff00; top: 40%; left: 70%;"></div>
        <div style="background-color: #ff0080; top: 70%; left: 30%;"></div>
        <div style="background-color: #4eff00; top: 90%; left: 80%;"></div>
    </div>

    <h1>Join Us in SDG 1 - No Poverty</h1>
    <p>Help eradicate poverty by donating only 1 Rupee!</p>
    <a href="#" class="donate-button">Donate 1 Rupee</a>
    <p class="donate-info">Learn more about SDG 1 - No Poverty</p>
    Sustainable Development Goal 1 (SDG 1) aims to end poverty in all its forms
    everywhere. The goal is to ensure that all people have equal access to resources,
    basic services, and opportunities for economic growth and development.
</p>
<p>
    By supporting SDG 1, we can create a world where no one is left behind, and all
    individuals and communities have the chance to live a dignified life, free from
    extreme poverty and deprivation.
</p>

<h2>About the United Nations (UN)</h2>
<p>
    The United Nations is an international organization founded in 1945 after World War II
    with the mission to maintain peace and security, promote human rights, foster
    social and economic development, protect the environment, and provide humanitarian aid.
</p>
<p>
    The UN plays a crucial role in advancing the 17 Sustainable Development Goals (SDGs),
    including SDG 1. It brings together countries, organizations, and individuals from around
    the world to address global challenges and work towards a better and more sustainable future.
</p>
 
</body>
</html>
