<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>task</title>
    <style>
        *{
            box-sizing: border-box;
        }
        h1{
            margin-bottom: 30px;
            text-align: center;
        }
        .row{
            width: 100%;
        }
        .par{
            border: 1px solid black;
            background-color: grey;
            width: 90%;
            height: 10%;
            margin-top: 30px;
            margin-right: auto;
            margin-left: auto;
            color: black;
        }
        
        .p1{
            border: 1px solid black;
            background-color:darksalmon;
            width: 60px;
            height: 20px;
            color: black;
            text-align: center;
            margin-top: 0px;
            float: right;
        }
        .p2{
            margin-top: 40px;
            margin-left: 20px;
            margin-right: auto;
        }
        .par2{
            border: 1px solid black;
            background-color: grey;
            width: 90%;
            height: 10%;
            margin-top: 30px;
            margin-right: auto;
            margin-left: auto;
            color: black;
        }
        
        .p12{
            border: 1px solid black;
            background-color:maroon;
            width: 60px;
            height: 20px;
            color:white;
            text-align: center;
            margin-top: 0px;
            float: right;
        }
        .p22{
            margin-top: 40px;
            margin-left: 20px;
            margin-right: auto;
        }
        .par3{
            border: 1px solid black;
            background-color: grey;
            width: 90%;
            height: 10%;
            margin-top: 30px;
            margin-right: auto;
            margin-left: auto;
            color: black;
        }
        
        .p13{
            border: 1px solid black;
            background-color:darkkhaki;
            width: 60px;
            height: 20px;
            color: black;
            text-align: center;
            margin-top: 0px;
            float: right;
        }
        .p23{
            margin-top: 40px;
            margin-left: 20px;
            margin-right: auto;
        }
        @media (min-width:1200px){
            .col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-lg-10,
            .col-lg-11,.col-lg-12{
                float: left;}
            .col-lg-1{width: 8.33%;}
            .col-lg-2{width: 16.66;}
            .col-lg-3{width: 25%;}
            .col-lg-4{width: 33%;}
            .col-lg-5{width: 41.66%;}
            .col-lg-6{width: 50%;}
            .col-lg-7{width: 58.33%;}
            .col-lg-8{width: 66.66%;}
            .col-lg-9{width: 74.99%;}
            .col-lg-10{width: 83.33%;}
            .col-lg-11{width: 91.66%;}
            .col-lg-12{width: 100%;}}


            @media (min-width:950px) and (max-width:1199px){
            .col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-md-10,
            .col-md-11,.col-md-12{
                float: left;}
            .col-md-1{width: 8.33%;}
            .col-md-2{width: 16.66;}
            .col-md-3{width: 25%;}
            .col-md-4{width: 33%;}
            .col-md-5{width: 41.66%;}
            .col-md-6{width: 50%;}
            .col-md-7{width: 58.33%;}
            .col-md-8{width: 66.66%;}
            .col-md-9{width: 74.99%;}
            .col-md-10{width: 83.33%;}
            .col-md-11{width: 91.66%;}
            .col-md-12{width: 100%;}
        }
    </style>
</head>
<body>
    <h1>Our Menu</h1>

        <div class="row">
            <div class="col-lg-3 col-md-6">
                <div class="par">
               
                   <p class="p1">chicken</p>
                   <p class="p2">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias asperiores animi eaque ea optio minima quisquam quas doloribus natus ratione, vitae libero consectetur quod harum,
                      consequuntur temporibus tempore consequatur corporis?
                   </p>
                </div>
            </div>
            <div class="col-lg-3 col-md-6">
                <div class="par2">
                
                     <p class="p12">Beef</p>
                     <p class="p22">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias asperiores animi eaque ea optio minima quisquam quas doloribus natus ratione, vitae libero consectetur quod harum,
                        consequuntur temporibus tempore consequatur corporis?
                     </p>
                </div>
            </div>
            <div class="col-lg-3 col-md-6">
                <div class="par3">
                
                    <p class="p13">Sushi</p>
                    <p class="p23">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias asperiores animi eaque ea optio minima quisquam quas doloribus natus ratione, vitae libero consectetur quod harum,
                        consequuntur temporibus tempore consequatur corporis?
                    </p>
                </div>
            </div>
        </div>
    
</body>
</html>
