# Lightbox.github.io
Tugas CSS 1 KK4A Membuat Lightbox
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Gallery</title>
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <h1>The Animals</h1>
    
    <div class="container">

        <ul class="gallery">
            <li>
                <a href="#gambar-1">
                    <img src="img/thumb/kucing.jpg" alt="Cat">
                    <span>Cat</span>
                </a>

               <div class="overlay" id="gambar-1">
                        <a href="#" class="close"> X CLOSE</a>
                        <a href="#gambar-4" class="previous">previous</a>
                        <img src="img/full/kucing.jpg" alt="Cat">
                        <a href="#gambar-2" class="next">next</a>

                </div>
            </li>

            <li>
                <a href="#gambar-2">
                    <img src="img/thumb/anjing.jpg" alt="Dog">
                    <span>Dog</span>
                </a>

                <div class="overlay" id="gambar-2">
                    <a href="#" class="close"> X CLOSE</a>
                    <a href="#gambar-1" class="previous">previous</a>
                    <img src="img/full/anjing.jpg" alt="Dog">
                    <a href="#gambar-3" class="next">next</a>
                </div>
            </li>

            <li>
                <a href="#gambar-3">
                    <img src="img/thumb/kuda.jpg" alt="Horse">
                    <span>Horse</span>
                </a>

                <div class="overlay" id="gambar-3">
                    <a href="#" class="close"> X CLOSE</a>
                    <a href="#gambar-2" class="previous">previous</a>
                    <img src="img/full/kuda.jpg" alt="Horse">
                    <a href="#gambar-4" class="next">next</a>
                </div>
            </li>

            <li>
                <a href="#gambar-4">
                    <img src="img/thumb/serigala.jpg" alt="Wolf">
                    <span>Wolf</span>
                </a>

                <div class="overlay" id="gambar-4">
                    <a href="#" class="close"> X CLOSE</a>
                    <a href="#gambar-3" class="previous">previous</a>
                    <img src="img/full/serigala.jpg" alt="Wolf">
                    <a href="#gambar-1" class="next">next</a>
                </div>
            </li>

            <div class="clear"></div>
        </ul>
    
    </div>

</body>
</html>
