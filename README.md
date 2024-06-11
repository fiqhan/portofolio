<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fiqhan.com</title>
    <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>
    <style>
        body {
            margin: 0%;
            padding: 0%;
        }

        .header {
            height: 100px;
            width: 100%;

        }

        .dropbtn {
            height: 30px;
            width: 30px;
            padding-top: 20px;
            padding-right: 30px;
            cursor: pointer;
        }

        .dropdown {
            position: relative;
            float: right;
            
        }

        .dropdown-content {
            display: none;
            float: left;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
            z-index: 1;
        }

        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown-content a:hover {
            background-color: #f1f1f1
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }


        .article {
            padding-left: 50px;
            width: 360px;
            height: 260px;
            text-align: justify;
            float: left;
        }

        .gallery-article {

            padding-top: 75px;
            padding-left: 550px;
            position: absolute;
            z-index: -1;
        }

        .container-footer {
            padding-top: 510px;
        }

        .content-footer {
            height: 100px;
            width: auto;
        }

        .logo-footer {
            margin: 30px;
            float: left;
        }

        .text-footer1 {
            float: right;
            padding-right: 120px;
        }

        .text-footer2 {
            float: right;
            padding-right: 30px;
        }

        .text-footer3 {
            float: right;
            padding-right: 30px;
        }

        .text-footer {
            list-style-type: none;
            float: none;
        }

        .text-footer a {
            text-decoration: none;
            color: black;
        }

    </style>
</head>

<body>
    <div class="header">
        <a href="portofolio.html"
            style="font-size: 3em; text-decoration: none; color: black; float: left; padding-top: 15px; padding-left: 30px;">Fiqhan.com</a>
        <div class="content-container">
            <div class="dropdown">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                    class="dropbtn"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
                    <path
                        d="M0 96C0 78.3 14.3 64 32 64H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z" />
                </svg>
                <div class="dropdown-content">
                    <a href="portofolio.html">Home</a>
                    <a href="experience.html">Experience and Education</a>
                    <a href="#Portofolio">Portofolio</a>
                    <a href="#Writing">Writing</a>
                    <a href="#Speaking">Speaking</a>
                </div>
            </div>
        </div>
    </div>
    <div class="article">
        <p style="font-size: 4em;"><b>About Me</b></p>
        <p style="font-size: 2em;">Fiqhan Chusnan Arriziq</p>
        <p style="text-indent: 50px;">Lahir pada 02 September 2004 di desa Kalitapen, Kecamatan Purwojati, Kabupaten
            Banyumas. Ia merupakan anak
            dari sepasang suami istri bernama bapak Misomudin dan Ibu Umiyati. </p>
        <p style="text-indent: 50px;">Jenjang pendidikan yang tengah ditempuh adalah berkuliah di Universitas Sains dan
            Al-Qur’an Wonosobo</p>
    </div>
    <div class="gallery-article">
        <img src="fiqhan 2.JPG" alt="gambar-fiqhan" style="width: 300px; height: 420px; float: left;">
        <img src="fiqhan 1.JPG" alt="gambar-fiqhan"
            style="width: 300px; height: 420px; float: right; margin-left: 50px;">
    </div>
    <div class="container-footer">
        <div class="content-footer">
            <p style="font-size: 2em; padding-left: 40px;"><b>Fiqhan.com</b></p>
        </div>
        <div class="logo-footer">
            <a href="https://www.instagram.com/fiqhan_na/" style="text-decoration: none;">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                    style="height: 30px; width: 30px; padding-left: 40px;"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
                    <path
                        d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z" />
                </svg>
            </a>
            <a href="https://www.facebook.com/alimaminalfaqoha.chusninan?mibextid=ZbWKwL" style="text-decoration: none;">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                    style="height: 30px; width: 30px;"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
                    <path
                        d="M512 256C512 114.6 397.4 0 256 0S0 114.6 0 256C0 376 82.7 476.8 194.2 504.5V334.2H141.4V256h52.8V222.3c0-87.1 39.4-127.5 125-127.5c16.2 0 44.2 3.2 55.7 6.4V172c-6-.6-16.5-1-29.6-1c-42 0-58.2 15.9-58.2 57.2V256h83.6l-14.4 78.2H287V510.1C413.8 494.8 512 386.9 512 256h0z" />
                </svg>
            </a>
            <a href="" style="text-decoration: none;">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                    style="height: 30px; width: 30px;"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
                    <path
                        d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z" />
                </svg>
            </a>
            <a href="https://youtube.com/@cuncshok6821?feature=shared" style="text-decoration: none;">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512"
                    style="height: 30px; width: 30px;"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
                    <path
                        d="M549.7 124.1c-6.3-23.7-24.8-42.3-48.3-48.6C458.8 64 288 64 288 64S117.2 64 74.6 75.5c-23.5 6.3-42 24.9-48.3 48.6-11.4 42.9-11.4 132.3-11.4 132.3s0 89.4 11.4 132.3c6.3 23.7 24.8 41.5 48.3 47.8C117.2 448 288 448 288 448s170.8 0 213.4-11.5c23.5-6.3 42-24.2 48.3-47.8 11.4-42.9 11.4-132.3 11.4-132.3s0-89.4-11.4-132.3zm-317.5 213.5V175.2l142.7 81.2-142.7 81.2z" />
                </svg>
            </a>
        </div>
        <div class="content-text-footer">
            <div class="text-footer1">
                <ul>
                    <li class="text-footer">Update New Content</li>
                    <li class="text-footer">-</li>
                    <li class="text-footer">-</li>
                    <li class="text-footer">-</li>
            </div>
            </ul>
            <div class="text-footer2">
                <ul>
                    <li class="text-footer">Menerima Order</li>
                    <li class="text-footer"><a href="">Website</a></li>
                    <li class="text-footer"><a href="">Portofolio</a></li>
                    <li class="text-footer"><a href="">Undangan</a></li>
                    <li class="text-footer">Dll</li>
                </ul>
            </div>
            <div class="text-footer3">
                <ul>
                    <li class="text-footer">Link Social Media</li>
                    <li class="text-footer"><a href="https://wa.me/qr/ZK66Q62M4NLEN1">WhatsApp</a></li>
                    <li class="text-footer"><a href="https://www.instagram.com/fiqhan_na/">Instagram</a></li>
                    <li class="text-footer"><a href="https://www.facebook.com/alimaminalfaqoha.chusninan?mibextid=ZbWKwL">Facebook</a></li>
                </ul>
            </div>
        </div>
    </div>
</body>

</html>

![fiqhan 4](https://github.com/fiqhan/portofolio/assets/51523087/772e4cd9-b167-4d61-9c52-133a0847c5de)
![fiqhan 3](https://github.com/fiqhan/portofolio/assets/51523087/3099803a-0a2e-4358-8026-080ebf2125ab)
![fiqhan 2](https://github.com/fiqhan/portofolio/assets/51523087/3de86fc8-7084-40f3-bc16-079fdc1f5b04)
![fiqhan 1](https://github.com/fiqhan/portofolio/assets/51523087/d9be2a6a-5bf6-4250-a38d-771941df9c81)
