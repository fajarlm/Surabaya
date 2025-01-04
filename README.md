
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas akhir</title>
    <link rel="stylesheet" href="Surabaya.css">
    <link rel="icon" href="/picture/logo.png">

    <script>
    document.addEventListener('DOMContentLoaded', function() {
        // Toggle menu burger
        const burger = document.getElementById('burger');
        const navMenu = document.getElementById('navMenu');
        
        if (burger && navMenu) {
            burger.addEventListener('click', function() {
                this.classList.toggle('active');
                navMenu.classList.toggle('active');
            });
        }

        // Slider functionality
        let currentIndex = 0;
        function showSlides() {
            const slides = document.querySelectorAll('.slider-image');
            slides.forEach(slide => slide.style.display = 'none'); // Hide all slides
            currentIndex++;
            if (currentIndex > slides.length) {
                currentIndex = 1;
            }
            slides[currentIndex - 1].style.display = 'block'; // Show the current slide
            setTimeout(showSlides, 3000); // Change image every 3 seconds
        }

        showSlides(); // Start the slider
    });
</script>

    </head>
    
<body>  
    <header class="header">
        <h1 class="judul"><acroniym title="Kota Di Pulau Jawa Timur" >SURABAYA</acroniym></h1>
        
        <div class="burger-menu" id="burger">
            <span></span>
            <span></span>
            <span></span>
        </div>
        <nav class="nav-menu" id="navMenu">
            <ul>
                <li><a href="#1">Tentang</a></li>
                <li><a href="#2">Sejarah</a></li>
                <li><a href="#3">Budaya</a></li>
                <li><a href="#4">Geografis</a></li>
            </ul>
        </nav>
    </header>
    <main>
        
        <div id="content" >
            <article id="1" class="card">
                <h2>Tentang</h2>
                <hr>
                <p>Apa yang ada dipikiran kalian tentang Jawa Timur ?
                    Tentang Surabaya, sesuai dengan etimologinya, berasal dari kata Sura ata Suro dan Baya atau Boyo, dalam bahasa Jawa. Suro adalah jenis ikan hiu, sedang boyo adalah istilah bahasa jawa untuk buaya. Nama Surabaya juga diambil dari istilah Sura Ing Baya, yang berarti “berani menghadapi bahaya”. Surabaya dikenal sebagai Kota Pahlawan, hal ini terjadi sejak adanya pertempuran rakyat Surabaya melawan tentara Belanda dalam Revolusi Kemerdekaan Indonesia. 
                    Letak kota Surabaya berada di tepi pantai utara Jawa timur, dan berbatasan langsung dengan Selat madura di utara dan timur, Kabupaten Sidoarjo di selatan, dan Kabupaten Gresik di barat. Kota Surabaya berada pada dataran rendah, dengan ketinggian antara 3-6 M di asata permukaan laut, hal ini juga yang menyababkan suhu udara di Surabaya tergolong panas dan kering.
                    Surabaya telah menjadi kota Metropolis dengan beberapa keanekaragaman yang kaya di dalamnya. Selain itu, Surabaya saat ini juga telah menjadi pusat bisnis, perdagangan, industri, dan pendidikan di Indonesia.
                    Surabaya menjadi pelabuhan utama dan pusat perdagangan komersial di wilayah timur Indonesia, dan sekarang menjadi salah satu kota terbesa di Asia Tenggara. Bersama dengan Lamongan di barat laut, Gresik di barat, Bangkalan di timur laut, Sidoarjo di selatan, Mojokerto dan Jombang di barat daya menjadi kesatuan yang dinamakan Gerbang Kertosusila, seperti Jabodetabek di Jakarta dan sekitarnya.
                    Sebagai ibukota provinsi, Surabaya juga merupakan rumah bagi banyak kantor dan pusat bisnis.
                    Bahasa yang digunakan sehari-hari sebagian besar menggunakan bahasa Jawa, dengan dialek Suroboyoan. Dialek ini cukup berbeda dengan bahasa Jawa dari Jawa Tengah seperti Surakarta atau Yogyakarta. Dialek Suroboyoan memiliki intonasi yang dalam dan tinggi, dan terkesan keras.</p>
                </article>
            <article id="2" class="card">
                <h2>Sejarah</h2>
                <hr>
                <br>
                <h3>Etimologi</h3>
                <p>Kata Surabaya (bahasa Sanskerta: Śūrabhaya) sering diartikan secara filosofis sebagai lambang perjuangan antara darat dan air. Selain itu, dari kata Surabaya juga muncul mitos pertempuran antara ikan sura (ikan hiu) dan baya (buaya), yang menimbulkan dugaan bahwa terbentuknya nama "Surabaya" muncul setelah terjadinya pertempuran tersebut. Kata Surabaya juga diyakini sebagai perpaduan dua nama tokoh besar pada masa lampau yaitu Suropati dan Purbaya.</p>
                <h3>Asal-usul Surabaya</h3>
                <p>Bukti sejarah menunjukkan bahwa Surabaya sudah ada jauh sebelum zaman kolonial, seperti yang tercantum dalam prasasti Trowulan I, berangka 1358 M. Dalam prasasti tersebut terungkap bahwa Surabaya (Śūrabhaya) masih berupa desa di tepi sungai Brantas dan juga sebagai salah satu tempat penyeberangan penting sepanjang daerah aliran sungai Brantas. Surabaya juga tercantum dalam pujasastra Kakawin Nagarakretagama yang ditulis oleh Empu Prapañca yang bercerita tentang perjalanan pesiar Raja Hayam Wuruk pada tahun 1365 M dalam pupuh XVII (bait ke-5, baris terakhir).

                    Walaupun bukti tertulis tertua mencantumkan nama Surabaya berangka tahun 1358 M (Prasasti Trowulan) dan 1365 M (Nagarakretagama), para ahli menduga bahwa wilayah Surabaya sudah ada sebelum tahun-tahun tersebut. Menurut pendapat budayawan Surabaya berkebangsaan Jerman Von Faber, wilayah Surabaya didirikan tahun 1275 M oleh Raja Kertanegara sebagai tempat permukiman baru bagi para prajuritnya yang berhasil menumpas pemberontakan Kemuruhan pada tahun 1270 M. Pendapat yang lainnya mengatakan bahwa Surabaya dahulu merupakan sebuah daerah yang bernama Ujung Galuh (Jung-Ya-Lu menurut catatan china).
                    
                    Versi lain menyebutkan, Surabaya berasal dari cerita tentang perkelahian hidup-mati antara Adipati Jayengrono dan Sawunggaling. Konon, setelah mengalahkan pasukan Kekaisaran Mongol utusan Kubilai Khan atau yang dikenal dengan pasukan Tartar, Raden Wijaya mendirikan sebuah keraton di daerah Ujung Galuh dan menempatkan Adipati Jayengrono untuk memimpin daerah itu. Lama-lama karena menguasai ilmu buaya, Jayengrono semakin kuat dan mandiri sehingga mengancam kedaulatan Kerajaan Majapahit. Untuk menaklukkan Jayengrono, maka diutuslah Sawunggaling yang menguasai ilmu sura.
                    
                    Adu kesaktian dilakukan di pinggir Kali Mas, di wilayah Peneleh. Perkelahian itu berlangsung selama tujuh hari tujuh malam dan berakhir dengan tragis, karena keduanya meninggal setelah kehilangan tenaga.
                    
                    Nama Śūrabhaya sendiri dikukuhkan sebagai nama resmi pada abad ke-14 oleh penguasa Ujung Galuh, Arya Lêmbu Sora</p>
                </article>
                <article id="3" class="card">
                <h2>Budaya</h2>
                <hr>
                <p>Budaya di Surabaya, Jawa Timur, meliputi berbagai tradisi, kesenian, dan lambang yang khas:</p>
                <h3>Tradisi</h3>
                <p>Beberapa tradisi unik di Surabaya, di antaranya:</p>
                <ul class="budaya">
                    <li>Larung Ari-Ari, tradisi menghanyutkan ari-ari bayi ke lautan yang dipercaya akan membawa rezeki </li>
                    <li>sedekah Bumi</li>
                    <li>Gulat Okol</li>
                    <li>Pitonan</li>
                    <li>Temu Manten Pegon</li>
                    <li>Undukan Doro</li>
                </ul>
                <h3>Kesenian</h3>
                <p>Beberapa kesenian khas Surabaya, di antaranya:</p>
                <ul class="budaya">
                    <li>Ludruk, seni panggung yang menyampaikan guyonan khas Surabaya dengan bahasa sehari-hari </li>
                    <li>Tari Remo</li>
                    <li>Tari Lenggang Surabaya, tarian selamat datang</li>
                    <li>Tari Hadrah Jidor</li>
                    <li>Topeng Mulud</li>
                </ul>
                <h3>Lambang</h3>
                <p>Lambang hiu dan buaya yang menjadi ikon dan logo resmi Kota Surabaya </p>
                <h3>Budaya Arek</h3>
                <p>Budaya khas masyarakat Surabaya dan sekitarnya yang mulai tergerus oleh pengaruh budaya luar</p>
                <h3>Surabaya Vaganza</h3>
                <p>Event tahunan yang diadakan pemerintah kota dalam rangka hari jadi Kota Surabaya</p>
            </article>
        </article>
        <article id="3" class="card">
                <h2>Geografis</h2>
                <hr>
                <h3>Geografi</h3>
                <p>Surabaya secara geografis berada pada 07°09'00" – 07°21'00" Lintang Selatan dan 112°36'- 112°54' Bujur Timur. Luas wilayah Surabaya meliputi daratan dengan luas 326,81 km² dan lautan seluas 190,39 km².</p>
                <h3>Batas Wilayah</h3>
                <p>Kota Surabaya berbatasan dengan beberapa wilayah, yaitu:</p>
                <table border>
                    <td>Utara</td>
                    <td >Selat Madura</td>
                    <tr>
                        <td>Timur</td>
                        <td>Selat Madura</td>
                    </tr>
                    <td>Selatan</td>
                    <td>Kabupaten Sidoarjo</td>
                    <tr>
                    <td>Barat</td>
                    <td>Kabupaten Gresik</td>
                </tr>
            </table>
            <h3>Geologi</h3>
            <p>Kondisi geologi Kota Surabaya terdiri dari Daratan Alluvium; Formasi Kabuh; Pucangan; Lidah; Madura; dan Sonde. Sedangkan untuk wilayah perairan, Surabaya tidak berada pada jalur sesar aktif ataupun berhadapan langsung dengan samudra, sehingga relatif aman dari bencana alam endogen. Berdasarkan kondisi geologi dan wilayah perairannya, Surabaya dikategorikan ke dalam kawasan yang relatif aman terhadap bencana gempa bumi maupun tanah amblesan sehingga pembangunan infrastruktur tidak memerlukan rekayasa geoteknik yang dapat menelan biaya besar.</p>
            
        </article>
    </div>
    <aside>
        <article class="card">
            <header>
                <h1 class="Informasi">Informasi Tambahan</h1>
                
                <div class="slider">
                    <img class="slider-image" src="./picture/slide2.jpeg" >
                    <img class="slider-image" src="./picture/silde1.jpeg" >
                    <img class="slider-image" src="./picture/slide4.jpeg" >
                    <img class="slider-image" src="./picture/slide3.jpeg" >
                </div>
                <br>
                <hr>
                    <table>
                        <tr>
                        <th>Provinsi </th>
                        <td>:<a href=""> Jawa Timur</a></td>
                    </tr>
                        <th>Luas </th>
                        <td>: 374,8 Km<sup>2</sup></td>
                    </tr>
                    <th>Kode Pos </th>
                    <td>: 60111-60299</td>
                        </tr>
                        <th>Fauna Resmi </th>
                        <td>: Hiu dan Buaya</td>
                    </tr>
                        <th>Flora Resmi </th>
                        <td>:<a href=""> Nyamplung</a></td>
                        </tr>
                        <th>Kode Area Telepon </th>
                        <td>: +62 31</td>
                        <tr></tr>
                        <th>Kode BPS </th>
                        <td>: 3578</td>
                    </table>
                </header>
            </article>
        </aside>
    </main>
    <footer>
        <p>&copy;2024 Fajar | Dicoding(Tugas akhir)</p>
    </footer>
</body>
</html>
