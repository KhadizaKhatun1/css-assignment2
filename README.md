Assignment:02
Name:Khadiza Khatun
Email:khadijasheikh266@gmail.
Live url link:https://meek-longma-ab667c.netlify.app/
 *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            /* max-width: 1450px; */
            font-family: 'Inter', sans-serif;
        }
        .header-container {
            background-color: #F0FDF4;
            height: 650px;
            padding: 40px 0;
            max-width: 1450px;
            border: 1px solid black;
        }
        .nav-container{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 80px;
            /* background-color: #f9fff9; */
            
        }
        .nav-title{
            font-weight: 500s;
            font-size: 32px;
            color:  #06C167;
            
        }
        .menus{
            
            display: flex;
            list-style: none;
            gap: 30px;
        }
        .menus li a{
            color: black;
            text-decoration: none;
        }
        .menus li a:hover{
            color: #06C167;
        }
        /* hero */
        .hero{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 80px;
        }
        .hero-title{
            font-size: 75px;
            font-weight: 600;
            line-height: 100%;
            margin-bottom: 20px;
        }
        .hero-button{
            display: flex;
            top: 30px;
            padding:20px;
            background-color: #06C167;
            width: 200px;
            position: relative;
            color: #FFFFFF;
        }
        .button-icon{
            position: absolute;
            left: 130px;
        }
        .polcadot{
            position: absolute;
            top: 481px;
            left: 300px;
        }
        .logoipsum{
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: relative;
            gap: 100px;
            top: 100px;
        }
        .hero-images{
            position: relative;
        }
        .ratings{
            display: flex;
            gap: 15px;
            padding: 10px;
            background-color: #FFFFFF;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1); 
            width: 230px;
            border-radius: 20px;
            position: absolute;
            top: 300px;
            left: -80px;
        }
        .quality-box{
            display: flex;
            align-items: center;
            gap: 10px;
            background-color: #FFFFFF;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            width: 230px;
            border-radius: 20px;
            position: absolute;
            top: 200px;
            left: 300px;
        }
        
        /* cart section */
        .section-container{
          margin: 0 auto; 
          padding: 70px;
          box-sizing: border-box;
          border: 1px solid red;
        }
        .cart-container{
           display: flex;
           justify-content: space-between;
           position: relative;
           padding: 40px 0;
           top: 170px;
           /* border: 1px solid black; */
           /* transition: all 0.3s ease; */
           box-shadow: 0 2px 8px rgba(0,0,0,0.1);  
        }
        .cart{
            display: flex;
            align-items: center;
            padding: 15px 10px;
            gap: 5px;
        }
        .cart:hover {
            background-color: #f0f4ff;
            transform: translateY(-3px);
        }