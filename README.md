<!DOCTYPE html>
<html>
<head>
    <title>Parallax</title>
    <style type="text/css">
        *{
            margin-top: 0px;
            padding: 0px;
         } 
         
        .parallaxone{
            width: 100%;
            height: 600px;
            background-image: url("https://cdn.pixabay.com/photo/2020/12/21/09/58/bmw-5849403_960_720.jpg");
            background-size: 100% 100%;
            background-attachment:fixed;
        }

        .parallaxone h2{
            position: relative;
            left: 500px;
            right: 500px;
            top: 300px;
            bottom: 300px;
            width: 300px;
            height: 40px;
            padding: 10px;
            background-color: black;
            color: white;
            text-align: center;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

        .parallaxtwo{
            width: 100% ;
            height: 600px;
            background-image: url(https://cdn.pixabay.com/photo/2021/01/01/21/09/challenger-5880009_960_720.jpg);
            background-size: 100% 100%;
            background-attachment:fixed;
        }

        .parallaxtwo h3{
            position: relative;
            left: 500px;
            top: 300px;
            width: 300px;
            height: 40px;
            padding: 10px;
            background-color: black;
            color: white;
            text-align: center;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

        .parallaxthree{
            width: 100%;
            height: 600px;
            background-image:url(https://cdn.pixabay.com/photo/2016/11/22/23/44/porsche-1851246_960_720.jpg) ;
            background-size: 100% 100%;
            background-attachment:fixed;
        }

        .parallaxthree h4{
            position: relative;
            left: 500px;
            right: 500px;
            top: 300px;
            bottom: 300px;
            width: 300px;
            height: 35px;
            padding: 5px;
            background-color: black;
            color: white;
            text-align: center;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }


        .para{
        
            padding: 50px;
            text-allign: center;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            height: 100px;
            background-color: black;
            color: white;
            font-size: 20px;
        }
        
    </style>         
</head>
<body>
    <div class="parallaxone">
        <h2>BMW M4 Competition
        </h2>
    </div>
    
    <div class="para">
        <p>
            In February 2016, BMW announced the M4 Competition Package. The M4 Competition Package boasts 331 kW (450 PS; 444 hp) and a revised suspension for better handling. New springs, dampers and anti-roll bars complement the included Adaptive M Suspension. BMW also re-tuned the electronic differential and the Dynamic Stability Control to match the upgraded hardware. The interior remains largely unchanged, but Competition Package cars get new lightweight sport seats along with the M-striped woven seat belts. The exterior includes the M Sport exhaust with black chrome tailpipes and high gloss Shadow Line exterior trim. Gloss black trim is added to the kidney grille, side gills, and model badge on the trunk.
        </p>
    </div>

    <div class="parallaxtwo">
        <h3>
            Dodge Challenger SXT
        </h3>
    </div>
    
    <div class="para">
        <p>
            The 2022 Dodge Challenger SXT comes standard with a 303-horsepower V6 engine, an eight-speed automatic transmission, and rear-wheel drive; all-wheel drive is optional. Standard features include cloth upholstery, a six-way power-adjustable driver's seat, a leather-wrapped steering wheel and shift knob, a rearview camera, dual-zone automatic climate control, proximity keyless entry, and a 7-inch touch-screen infotainment system with Bluetooth, Android Auto, Apple CarPlay, two USB ports, and a six-speaker stereo.
        </p>
    </div>

    <div class="parallaxthree">
        <h4>
            The 911 Carrera T
        </h4>
    </div>
    
    <div class="para">
        <p>
            Fewer kilograms equals more agility and contact with the road is more important than ever. The 911 Carrera T is a commitment to purism. A conscious release for increased driving pleasure.
        </p>
    </div>
    


