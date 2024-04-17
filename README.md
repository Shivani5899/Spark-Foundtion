<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Gatway Integration</title>
    <link rel="stylesheet" href="header.css">
    <link rel="stylesheet" href="section.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="header">
            <div class="left">
                <div class="logo">
                    <img class="icon" src="img/logo_small.png" alt="Error">
                </div>
                <div class="title">
                    <div class="name">
                        The Sparks Foundation
                    </div>
                    <div class="quto">
                        ...i n s p i r i n g ,  &#160; i n n o v a t i n g , &#160; i n t e g r a t i n g 
                    </div>
                </div>
            </div>
            <div class="right">
                <a href="http://127.0.0.1:5500/Payment%20Gatway%20Project/payment.html">
                    <button class="button">
                        <div class="home">Home</div>
                    </button>
                </a>
                <a href="https://www.thesparksfoundationsingapore.org/">
                    <button class="button">
                        <div class="about">About</div>
                    </button>
                </a>
                <a href="https://www.thesparksfoundationsingapore.org/contact-us/">
                    <button class="button">
                        <div class="contact">Contact</div>
                    </button>
                </a>
               
            </div>
        </div>
    </header>
    <section>
        <div class="section">
            <img class="background" src="img/background.jpeg" alt="
            Error">
            <div class="mission">
                <div class="heading">Mission and Vision Statement</div>
                <div class="content">
                    The sparks foundation is working to bring parity in education, making sure children have equal opportunity at success, irrespective of the financial background.
                </div>
                <a href="https://www.thesparksfoundationsingapore.org/about/vision-mission-and-values/">
                    <button class="know-more-container">
                        <div class="know-more">KNOW MORE</div>
                    </button>
                </a>
            </div>
            <div class="payment">
                <div class="heading">
                    Payment Gateway Integration
                </div>
                <div class="content">
                    <span class="qutos">"Giving is not just about making a donation,It is about making a difference"</span>
                    <div class="donate">
                        Make a big impact with your small amounts.
                    </div>
                </div>
                <div class="donatenow">
                   <form><script src="https://checkout.razorpay.com/v1/payment-button.js" data-payment_button_id="pl_M2AeRJlDtWr8rj" async> </script> </form>
                       </div>
               <div>
            </div>
        </div>

    </section>
</body>
</html>



*{
    box-sizing: border-box;
    font-family: 'Roboto', Arial, sans-serif;
}

.header{
    height: 84px;
    border: 1px solid rgb(128, 128, 128);
    background-color: #545252;
    position: fixed;
    top: 0px;
    right: 0px;
    left: 0px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    z-index: 1;
    border-bottom: 2px solid white;

}
.left{
    height: 63px;
    width: 550px;
    /* background-color: lightpink; */
    display: flex;
    flex-direction: row;
    align-items: center;
}
.right{
    height: 63px;
    width: 310px;
    display: flex;
    margin-right: 10px;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}
.logo{
    margin-left: 20px;
}
.icon{
    height: 63px;
    width: 53px;
}
.title{
    margin-left: 10px;
    
}
.name{
    font-size: 30px;
    color: rgb(179, 28, 255);
    font-weight: 500;
}
.quto{
    font-size: 12px;
    color: white;
    margin-left: 22px;
    /* font-weight: 500; */
}
.button{
    font-size: 16px;
    font-weight: 500;
    height: 40px;
    width: 100px;
    margin-left: 5px;
    border: none;
    border-radius: 40px;
    transition: opacity 0.15s;
}
.button:hover{
    background-color:rgb(255, 28, 221); 
    color: white;
}
.button:active{
    opacity: 0.8;
}


.section{
    position: relative;
    top: 78px;
    right: -8px;
    left: -8px;
    /* bottom: -8px; */
}
.background{
    width: 1349px;
}
.project{
    font-size: 20px;
    position: absolute;
    top: 100px;
    bottom: 46px;
    left: 100px;
    border-radius: 20px;
}
.mission , .payment{
    width: 450px;
    background-color: rgb(54, 54, 54);
    color: black;
    border-radius: 20px;
    opacity: 0.8;
    position: absolute;
    top: 150px;
    bottom: 150px;
    padding-left: 10px;
}

.mission{
    left: 155px;
}
.payment{
    right: 155px;
}
.heading{
    font-size: 30px;
    margin-top: 20px;
    padding: 25px 5px 10px 18px;
    color: rgb(187, 255, 0);
    /* color: rgb(255, 238, 0); */
    font-weight: 700;
    opacity: 1;
}
.content{
    color: white;
    font-size: 20px;
    /* font-weight: 500; */
    line-height: 26px;
    padding: 10px 20px 20px 15px;
    opacity: 1;
}
.donate{
    padding: 15px 0px 0px 40px;
}
.donatenow{
    margin: 0px 0px 0px 120px;
}
.qutos{
    font-weight: 600;
}
.know-more-container{
    font-size: 16px;
    font-weight: 500;
    height: 40px;
    width: 150px;
    border: 1px solid white;
    background-color: white;
    border-radius: 40px;
    align-items: center;
    margin:0px 0px 0px 120px;
    transition: opacity 0.15s;
}
.know-more-container:hover{
    color: blue;
    background-color:rgb(255, 238, 0);
}
.know-more-container:active{
    opacity: 0.8;
}
