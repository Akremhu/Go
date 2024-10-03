# Fivestar 
/* تصميم أساسي للصفحة */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    direction: rtl;
    background-color: #f5f5f5;
}

/* رأس الصفحة */
header {
    background-color: #333;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo h1 {
    margin: 0;
}

header .social-links a {
    color: white;
    text-decoration: none;
    margin-left: 15px;
    font-size: 14px;
}

/* القسم الرئيسي */
main .hero {
    text-align: center;
    padding: 50px;
    background-color: #fff;
    margin-bottom: 20px;
}

main .hero img {
    max-width: 100%;
    height: auto;
}

main .services {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: #f0f0f0;
}

main .services .service {
    text-align: center;
    width: 30%;
}

main .services .service img {
    width: 80px;
    height: auto;
}

/* تذييل الصفحة */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

footer .social-links a {
    color: white;
    text-decoration: none;
    margin-left: 10px;
    font-size: 14px;
}
