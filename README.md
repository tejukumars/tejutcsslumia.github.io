* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

html,
body {
    width: 100%;
    overflow-x: hidden;
    background-color: aliceblue;
}

/* Navbar Starts */

nav {
    background-color: rgb(246, 247, 255);
    padding: 25px 45px;
    position: fixed;
    top: 0px;
    width: 100%;
}

/*z-index:-2; */

nav ul li {
    display: inline;
}

nav ul {
    display: inline;
    margin-left: 228px;
}

nav ul li a {
    text-decoration: none;
    color: black;
    font-size: 14px;
    font-weight: 500;
    margin-left: 51px;
}

nav ul li a:hover {
    color: blue;
}

.brand-logo {
    text-decoration: none;
    font-size: 25px;
    color: black;
}

.nav-btn {
    background-color: #e2e5fe;
    font-size: 16px;
    padding: 8px 24px;
    border-radius: 4px;
    transition: background-color 1s, color 0.6s;
}

.nav-btn:hover {
    background-color: rgb(1, 1, 14);
    color: white;
}

/* Navbar Ends */

/* Banner Starts */

.banner {
    height: 500px;
    background: linear-gradient(to right, rgba(51, 47, 47, 0.555), transparent), url("https://previews.envatousercontent.com/files/229742203/paradise/images/fw_al_004_01.jpg");
    background-repeat: no-repeat;
    background-size: 100% 100%;
}

.banner-content {
    width: 800px;
    color: rgb(151 187 192);
    padding: 20px;
    text-align: center;
    margin: 50px auto;
    font-family: "Krub", sans-serif!important;
}

.banner-content h1 {
    font-size: 60px;
}

.banner-content p {
    font-size: 25px;
    margin-top: 20px;
    margin-bottom: 30px;
}

.banner-content button {
    background-color: rgb(57, 57, 65);
    border-radius: 6px;
    padding: 13px 50px;
    font-size: 16px;
    color: white;
    border: none;
}

.banner-content button:hover {
    background-color: blue;
}

/* Banner Ends */

/* bg-img starts */

.banner-image {
    margin-top: -180px;
    margin-left: 305px;
}

/* bg-img ends */

/* provident starts */

.provident {
    background-color: #466393;
    padding: 50px;
    color: white;
}

.provident-content,
.provident-icons {
    /* border:2px solid red; */
    display: inline-block
}

.provident-icons-content {
    /* border:2px solid green; */
    padding: 20px;
}

.provident-content {
    width: 500px;
    padding: 20px;
}

.provident-icons {
    width: 350px;
}

.provident-icons i {
    font-size: 40px;
    color: #b6bdfc;
}

.provident-content button {
    border-radius: 30px;
    font-weight: bold;
    padding: 10px 37px;
    background-color: rgba(173, 216, 230, 0.2);
    border: none;
    color: white;
}

.provident-content button:hover {
    background-color: rgba(173, 216, 230, 0.274);
}

.provident h1 {
    font-size: 40px;
}

.provident .provident-content p {
    margin-top: 40px;
    margin-bottom: 40px;
    font-size: 17px;
}

.provident-icons-content h3 {
    margin-top: 10px;
    margin-bottom: 10px;
}

/* provident Ends */

/* logos starts */

.logos {
    background-color: #f6f7ff;
    padding: 10px 130px;
}

.logo-image {
    /* border: 2px solid red; */
    width: 178px;
    height: 86px;
    display: inline-block;
}

.logo-image img {
    height: 31px;
    width: 60px;
    margin: 16px 51px;
    transition: transform 1s;
}

.logo-image img:hover {
    transform: scale(1.2);
}

/* logos ends */

/* features starts */

.features {
    margin: 70px;
}

.features .para,
.heading {
    text-align: center;
}

.features-data {
    border: 2px solid red;
}

.features-image,
.features-content {
    /* border:2px solid green; */
    height: 450px;
    display: inline-block;
    padding: 20px;
}

.features-image {
    width: 480px;
}

.features-content {
    width: 650px;
    margin-left: 35px;
}

.features-image img {
    height: 100%;
    width: 100%;
}

.features-content h1 {
    font-size: 35px;
    font-family: calibri;
}

.features-content p {
    font-size: 22px;
    margin-top: 20px;
    margin-bottom: 40px;
}

.features-content li {
    font-size: 23px;
    margin-bottom: 20px;
    list-style-type: none;
    /* list-style-image: url("data:image/jpeg;base64,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");*/
}

.features hr {
    margin-top: 20px;
    margin-bottom: 40px;
}

.features-content .fa-check {
    font-size: 14px;
    font-weight: bold;
    color: green;
}

/* features ends */

/* boxes starts */

.boxes {
    margin: 70px;
}

.box-content {
    border: 1px solid gray;
    width: 400px;
    height: 300px;
    display: inline-block;
    padding: 30px;
    margin-left: -5px;
}

.boxes .box-content:nth-child(1) {
    border-top: none;
    border-left: none;
}

.boxes .box-content:nth-child(2) {
    border-top: none;
}

.boxes .box-content:nth-child(3) {
    border-top: none;
    border-right: none;
}

.boxes .box-content:nth-child(4) {
    border-left: none;
    border-bottom: none;
    border-top: none;
}

.boxes .box-content:nth-child(5) {
    border-bottom: none;
    border-top: none;
}

.boxes .box-content:nth-child(6) {
    border-right: none;
    border-bottom: none;
    border-top: none;
}

/* boxes Ends */

/* Services Starts */

.services {
    background-color: #466393;
    padding: 60px 100px;
}

.services h1,
.para {
    text-align: center;
    color: rgb(10, 8, 8);
}

.services h1 {
    font-size: 50px;
}

.services .para {
    font-size: 20px;
}

.services-cards .cards {
    /* border:2px solid red; */
    width: 250px;
    height: 300px;
    padding: 30px;
    display: inline-block;
    margin-left: 30px;
    background-color: white;
    border-radius: 10px;
    transition: transform .5s;
}

.services-cards .cards:hover {
    transform: scale(1.1);
}

.services-cards {
    margin-top: 30px;
}

.services hr {
    margin-top: 30px;
    margin-bottom: 30px;
}

.services-cards .cards .cards-content {
    margin: 20px;
    text-align: center;
}

.services-cards .cards .cards-content h2 {
    margin-top: 30px;
    margin-bottom: 20px;
}

.services-cards .cards .cards-content p {
    line-height: 24px;
}

.services-cards .cards .cards-content i {
    color: #466393;
    font-size: 25px;
    background-color: rgba(173, 216, 230, 0.377);
    height: 56px;
    width: 56px;
    border-radius: 100%;
    padding: 13px;
}

/* Services ends */

/* team starts */

.team {
    margin: 60px;
}

.team h1,
.para1 {
    text-align: center;
}

.team-cards .card {
    /* border:2px solid red; */
    width: 270px;
    height: 300px;
    display: inline-block;
    position: relative;
    margin-left: 30px;
    overflow: hidden;
}

.team-cards .card img {
    width: 100%;
    height: 100%;
    transition: transform 1sx;
}

.team-cards .card:hover img {
    transform: scale(1.1);
}

.team-cards .card .card-content {
    background-image: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.9));
    position: absolute;
    bottom: 0px;
    width: 100%;
    height: 0px;
    color: white;
    text-align: center;
    visibility: hidden;
    transition: height .5s;
}

.team-cards .card:hover .card-content {
    visibility: visible;
    height: 100%;
}

.team-cards .card .card-content div {
    margin-top: 200px;
}

.team-cards .card .card-content div i {
    margin-left: 10px;
}

/* team ends */

hr {
    height: 7px;
    background-color: gray;
    width: 80px;
    margin: 20px auto;
    border: none;
}

.input {
    margin: 100px;
}

.input input {
    padding: 10px 40px;
    border-radius: 6px;
    border: 1px solid gray;
    outline: none;
}

.input input:focus {
    border: 1px solid blue
}
