<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yaşar Kemal - Edebiyatın Yıldız İsmi</title>
    <!-- Tailwind CSS CDN --><script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Montserrat for headings, Lato for body --><link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&family=Montserrat:wght@600;700;800;900&display=swap" rel="stylesheet">
    <!-- Font Awesome CDN for icons --><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
    <style>
        body {
            font-family: 'Lato', sans-serif;
            background-color: #f0f4f8; /* Daha açık, modern gri */
            color: #2c3e50; /* Koyu gri metin */
        }
        h1, h2, h3 {
            font-family: 'Montserrat', sans-serif;
        }
        .content-card {
            background-color: #ffffff;
            border-radius: 1.5rem;
            box-shadow: 0 20px 30px -10px rgba(0, 0, 0, 0.15), 0 8px 12px -4px rgba(0, 0, 0, 0.08);
            padding: 3rem;
            transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1); /* Yumuşak geçiş */
            border: 1px solid rgba(220, 220, 220, 0.4);
        }
        .content-card:hover {
            transform: translateY(-5px) scale(1.005);
            box-shadow: 0 25px 40px -10px rgba(0, 0, 0, 0.2), 0 10px 15px -5px rgba(0, 0, 0, 0.1);
        }
        .text-accent {
            color: #e74c3c; /* Canlı mercan kırmızısı */
        }
        .bg-accent-light {
            background-color: #fff5f5; /* Çok açık mercan */
        }
        .border-accent {
            border-color: #e74c3c;
        }
        .section-divider {
            border-top: 2px dashed #dcdcdc;
            margin: 4rem auto;
            width: 80%;
            position: relative;
        }
        .section-divider::before {
            content: "\f005"; /* Font Awesome star icon */
            font-family: "Font Awesome 5 Free";
            font-weight: 900;
            color: #e74c3c;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: #f0f4f8;
            padding: 0 10px;
            font-size: 1.5rem;
        }
        .timeline-item {
            border-left: 4px solid #e74c3c;
            padding-left: 1.5rem;
            position: relative;
            margin-bottom: 2rem;
        }
        .timeline-item::before {
            content: '';
            position: absolute;
            left: -10px;
            top: 0.5rem;
            width: 18px;
            height: 18px;
            background-color: #e74c3c;
            border-radius: 50%;
            border: 3px solid #f0f4f8; /* Vurgu rengiyle çevrili daire */
            box-shadow: 0 0 0 2px #e74c3c;
        }
        .parallax-bg {
            background-image: url('https://placehold.co/1920x800/2c3e50/ecf0f1?text=Destan+Arkaplan'); /* Daha koyu, sofistike bir arkaplan */
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
            z-index: -1;
        }
        .bg-overlay {
            background-color: rgba(0, 0, 0, 0.6); /* Daha belirgin overlay */
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Hero Section / Başlık Bölümü --><div class="relative min-h-[500px] flex items-center justify-center text-center overflow-hidden parallax-bg">
        <div class="absolute inset-0 bg-overlay z-0"></div>
        <header class="relative z-10 p-6 max-w-4xl mx-auto">
            <h1 class="text-5xl sm:text-7xl font-extrabold text-white tracking-tight leading-tight drop-shadow-lg">
                YAŞAR KEMAL
            </h1>
            <p class="mt-4 text-xl sm:text-3xl font-light text-gray-200 italic drop-shadow-md">
                Anadolu'nun Sözcüsü, Edebiyatın Yıldızı
            </p>
            <div class="mt-8">
                <a href="#biyografi" class="inline-block bg-accent text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-red-700 transition duration-300 text-lg">
                    Daha Fazla Keşfet <i class="fas fa-chevron-down ml-2"></i>
                </a>
            </div>
        </header>
    </div>

    <div class="max-w-7xl mx-auto p-4 sm:p-10 space-y-16 mt-[-80px] relative z-10">

        <!-- Yazarın Fotoğrafı ve Kısa Biyografi --><div id="biyografi" class="grid lg:grid-cols-3 gap-10 items-stretch">
            
            <!-- Portre ve Alıntı --><div class="lg:col-span-1 content-card p-0 overflow-hidden bg-gradient-to-br from-gray-900 to-gray-700 flex flex-col justify-between">
                <!-- GÖRSEL GÜNCELLENDİ -->
                <img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Ya%C5%9Far_Kemal.jpg" 
                     alt="Yaşar Kemal'in Karizmatik Portresi" 
                     class="w-full h-auto object-cover opacity-90 hover:opacity-100 transition duration-500"
                     onerror="this.onerror=null; this.src='https://placehold.co/800x1100/34495e/ecf0f1?text=G%C3%B6rsel+Y%C3%BCklenemedi';"
                     loading="lazy">
                <div class="p-6 text-center text-lg font-semibold text-white bg-gray-800 italic">
                    "Bir toplumda namuslu insanlar, en az namussuzlar kadar cesur olmadıkça o toplum için kurtuluş yoktur."
                </div>
            </div>

            <!-- Biyografi Metni ve Dönüm Noktaları --><section class="lg:col-span-2 content-card bg-accent-light">
                <h2 class="text-4xl font-extrabold text-accent border-b-4 border-accent pb-4 mb-6 flex items-center">
                    <i class="fas fa-user-circle mr-3"></i> Yaşamı ve Sanat Hayatı
                </h2>
                <p class="text-gray-700 leading-relaxed text-lg mb-6">
                    Asıl adı Kemal Sadık Gökçeli (1923–2015), Türk edebiyatının destansı sesi, Anadolu'nun çilekeş insanının ve bereketli topraklarının hikayecisi. Adana'nın Osmaniye ilçesinde doğup büyüyen Yaşar Kemal, çocukluğundan itibaren Çukurova'nın hem güzelliklerine hem de zorluklarına tanıklık etti. Genç yaşta başladığı çeşitli işlerle hayatın tüm katmanlarını deneyimledi, bu da eserlerinin gerçekçi ve derinlikli olmasına zemin hazırladı.
                </p>
                <p class="text-gray-700 leading-relaxed text-lg">
                    Şiirle başlayan edebiyat serüveni, röportajlarıyla tanınmasının ardından 1955'te yayımladığı **İnce Memed** ile zirveye ulaştı. Bu roman, sadece Türkiye'de değil, dünya çapında büyük bir yankı uyandırdı ve Yaşar Kemal'i uluslararası bir figür haline getirdi. Eserlerinde doğa sevgisi, insan onuru, adalet arayışı ve sömürüye karşı direniş temalarını destansı bir anlatımla işledi.
                </p>

                <h3 class="text-3xl font-bold text-gray-800 mt-10 mb-6 border-t pt-6 flex items-center">
                    <i class="fas fa-history mr-3"></i> Hayatından Dönüm Noktaları
                </h3>
                <div class="space-y-6">
                    <div class="timeline-item">
                        <p class="font-bold text-lg text-gray-900">1923: Dünyaya Geliş</p>
                        <p class="text-md text-gray-700">Adana'nın Hemite köyünde doğdu, çocukluğu Çukurova'nın pamuk tarlalarında geçti.</p>
                    </div>
                    <div class="timeline-item">
                        <p class="font-bold text-lg text-gray-900">1951: Gazetecilik ve Edebiyata İlk Adım</p>
                        <p class="text-md text-gray-700">Cumhuriyet gazetesinde röportajlar ve fıkralar yazarak adını duyurdu.</p>
                    </div>
                    <div class="timeline-item">
                        <p class="font-bold text-lg text-gray-900">1955: İnce Memed Destanı</p>
                        <p class="text-md text-gray-700">Modern Türk edebiyatının başyapıtlarından İnce Memed'in ilk cildi yayımlandı.</p>
                    </div>
                    <div class="timeline-item">
                        <p class="font-bold text-lg text-gray-900">1980'ler: Uluslararası Tanınırlık</p>
                        <p class="text-md text-gray-700">Fransa Legion d'Honneur nişanı ve dünya çapında birçok ödülün sahibi oldu.</p>
                    </div>
                    <div class="timeline-item">
                        <p class="font-bold text-lg text-gray-900">2015: Ebediyete İntikal</p>
                        <p class="text-md text-gray-700">8 Mart'ta aramızdan ayrıldı, geride ölümsüz eserler bıraktı.</p>
                    </div>
                </div>
            </section>
        </div>

        <div class="section-divider"></div>

        <!-- Çukurova ve Edebiyat Teması (Görsel Zenginlik) --><section class="content-card bg-gradient-to-r from-teal-50 to-emerald-50 p-10">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-4xl font-extrabold text-teal-800 mb-4 flex items-center">
                        <i class="fas fa-tree mr-3 text-teal-600"></i> Çukurova'nın Ebedi Sesi
                    </h2>
                    <p class="text-gray-700 leading-relaxed text-lg mb-6">
                        Yaşar Kemal'in eserlerinde Çukurova, sadece bir mekan değil, aynı zamanda canlı, nefes alan bir karakterdir. Toros Dağları'nın heybeti, pamuk tarlalarının bereketi, Ceyhan Nehri'nin coşkusu, yazarın kalemiyle destansı bir nitelik kazanır. İnsan ve doğa arasındaki derin ilişki, onun anlatımının merkezinde yer alır.
                    </p>
                    <p class="text-gray-700 leading-relaxed text-lg">
                        Yazar, toprağın rengini, rüzgarın sesini, her çiçeğin kokusunu öyle bir ustalıkla aktarır ki okuyucu kendini o büyülü coğrafyanın içinde hisseder. Çukurova, Yaşar Kemal'in anlatılarında direnişin, umudun ve yaşamın ta kendisidir.
                    </p>
                </div>
                <div class="flex justify-center items-center">
                    <img src="https://placehold.co/700x500/62929a/ffffff?text=%C3%87ukurova+Destan%C4%B1" 
                         alt="Çukurova'nın Pamuk Tarlaları ve Toroslar Manzarası" 
                         class="w-full max-w-lg object-cover rounded-2xl shadow-xl border-4 border-white transform hover:scale-105 transition duration-500">
                </div>
            </div>
        </section>

        <div class="section-divider"></div>

        <!-- Başlıca Eserleri Bölümü --><section class="content-card">
            <h2 class="text-4xl font-extrabold text-accent border-b-4 border-accent pb-4 mb-8 flex items-center">
                <i class="fas fa-book-open mr-3"></i> Başlıca Eserleri
            </h2>
            
            <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-8">
                
                <!-- Eser Kartları --><div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-100 hover:border-accent transform hover:-translate-y-2 transition duration-300">
                    <h3 class="font-bold text-2xl text-accent mb-2">İnce Memed</h3>
                    <p class="text-gray-700 text-base">
                        Zulme karşı başkaldıran bir eşkıyanın destansı hikayesi. Yaşar Kemal'in dünyaya açılan kapısı.
                    </p>
                </div>

                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-100 hover:border-accent transform hover:-translate-y-2 transition duration-300">
                    <h3 class="font-bold text-2xl text-accent mb-2">Yer Demir Gök Bakır</h3>
                    <p class="text-gray-700 text-base">
                        Kıtlık ve çaresizlik karşısında efsaneleşen bir köylünün, Hıdır'ın, öyküsü.
                    </p>
                </div>

                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-100 hover:border-accent transform hover:-translate-y-2 transition duration-300">
                    <h3 class="font-bold text-2xl text-accent mb-2">Deniz Küstü</h3>
                    <p class="text-gray-700 text-base">
                        İstanbul'un kenar mahallelerinde denize küsmüş insanların ve kaybolan değerlerin öyküsü.
                    </p>
                </div>

                <div class="bg-gray-50 p-6 rounded-xl shadow-md border border-gray-100 hover:border-accent transform hover:-translate-y-2 transition duration-300">
                    <h3 class="font-bold text-2xl text-accent mb-2">Ağrı Dağı Efsanesi</h3>
                    <p class="text-gray-700 text-base">
                        Doğu'nun kadim efsanelerinden beslenen, aşk, özgürlük ve isyan temalı epik bir roman.
                    </p>
                </div>
            </div>
        </section>

        <div class="section-divider"></div>

        <!-- Önemli Ödüller ve Adaylıklar Bölümü --><section class="content-card bg-accent-light p-10">
            <h2 class="text-4xl font-extrabold text-accent border-b-4 border-accent pb-4 mb-8 flex items-center">
                <i class="fas fa-award mr-3"></i> Ödüller ve Uluslararası Başarılar
            </h2>
            
            <div class="grid md:grid-cols-2 gap-10 items-center">
                <div>
                    <h3 class="text-3xl font-bold text-gray-900 mb-4">Nobel Edebiyat Ödülü Adayı</h3>
                    <p class="text-gray-700 leading-relaxed text-lg mb-6">
                        Yaşar Kemal, uzun yıllar boyunca Nobel Edebiyat Ödülü için güçlü bir aday olarak görüldü. Eserleri 40'tan fazla dile çevrildi ve ona uluslararası alanda büyük bir ün kazandırdı. Anadolu'nun eşsiz kültürünü, insanının derinliğini ve evrensel temaları dünya okuruyla buluşturdu.
                    </p>
                    <ul class="list-disc list-inside text-gray-700 space-y-3 text-lg pl-4">
                        <li class="flex items-center"><i class="fas fa-trophy text-accent mr-3"></i> 1956: Varlık Roman Ödülü (İnce Memed)</li>
                        <li class="flex items-center"><i class="fas fa-trophy text-accent mr-3"></i> 1974: Sedat Simavi Edebiyat Ödülü</li>
                        <li class="flex items-center"><i class="fas fa-award text-accent mr-3"></i> 1984: Fransa Légion d'Honneur Nişanı Komutanı</li>
                        <li class="flex items-center"><i class="fas fa-globe text-accent mr-3"></i> 1997: Uluslararası Nonino Ödülü (İtalya)</li>
                        <li class="flex items-center"><i class="fas fa-star text-accent mr-3"></i> 2008: T.C. Cumhurbaşkanlığı Kültür ve Sanat Büyük Ödülü</li>
                    </ul>
                </div>
                <div class="flex justify-center items-center">
                    <img src="https://placehold.co/600x400/e74c3c/ffffff?text=Uluslararas%C4%B1+%C3%96d%C3%BCl" 
                         alt="Uluslararası Ödül ve Başarıyı Temsil Eden Görsel" 
                         class="w-full max-w-lg rounded-2xl shadow-2xl border-4 border-white transform hover:scale-105 transition duration-500">
                </div>
            </div>
        </section>

        <div class="section-divider"></div>

        <!-- Footer --><footer class="text-center pt-10 pb-6 text-gray-600 text-md border-t-2 border-gray-300 mt-12">
            <p class="mb-2">
                &copy; 2024 Yaşar Kemal Saygıyla Anma Sayfası. Tüm Hakları Saklıdır.
            </p>
            <p>
                <a href="#" class="text-accent hover:underline">Gizlilik Politikası</a> | 
                <a href="#" class="text-accent hover:underline">İletişim</a>
            </p>
        </footer>
    </div>

</body>
</html># ysrkml
