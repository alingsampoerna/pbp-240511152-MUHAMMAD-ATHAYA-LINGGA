# Analisis Platform Web, Desktop, dan Mobile

## Perbandingan Platform

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| **Arsitektur** | Client-server. Browser sebagai client berkomunikasi dengan server melalui HTTP/HTTPS. Tampilan berjalan di browser, sedangkan logika bisnis dan data umumnya berada di server. | Aplikasi berjalan langsung pada sistem operasi perangkat, baik secara monolitik maupun client-server, dan dapat menggunakan resource lokal. | Aplikasi berjalan pada sistem operasi mobile seperti Android/iOS dalam lingkungan sandbox dan umumnya terhubung ke back-end melalui API. |
| **Bahasa Utama** | HTML, CSS, JavaScript/TypeScript untuk front-end; Node.js, PHP, Python, dan Java dapat digunakan untuk back-end. | Java, C#, C++, dan Python. | Kotlin dan Java untuk Android, Swift untuk iOS, serta Dart/Flutter dan JavaScript/React Native untuk pengembangan lintas platform. |
| **Distribusi** | Diakses melalui URL tanpa instalasi dan dapat di-deploy ke server, hosting, atau cloud. | Didistribusikan melalui installer atau paket seperti `.exe`, `.msi`, `.deb`, atau `.dmg` yang kemudian dipasang pada perangkat. | Didistribusikan melalui toko aplikasi seperti Google Play dan App Store atau melalui file APK pada Android. |
| **Keunggulan** | Dapat digunakan pada berbagai sistem operasi, mudah diperbarui karena cukup melakukan deployment pada server, dan pengguna tidak perlu melakukan instalasi. | Memiliki performa tinggi, dapat mengakses perangkat keras dan file sistem secara lebih luas, serta dapat berjalan secara offline. | Mendukung penggunaan sensor seperti kamera dan GPS, notifikasi push, pengalaman pengguna yang lebih native, serta mudah digunakan saat mobilitas tinggi. |
| **Keterbatasan** | Bergantung pada koneksi internet dan browser. Akses terhadap perangkat keras lebih terbatas dan performanya dapat berada di bawah aplikasi native. | Harus diinstal pada setiap perangkat, bergantung pada sistem operasi, dan proses distribusi serta pembaruan dapat lebih merepotkan. | Memiliki proses review toko aplikasi, beragam ukuran layar dan versi sistem operasi, serta memiliki keterbatasan baterai dan resource perangkat. |
| **Contoh Aplikasi** | Google Docs, Tokopedia versi web, dan GitHub. | IntelliJ IDEA, Visual Studio Code, dan Microsoft Word. | WhatsApp, Gojek, dan Instagram. |

## Kesimpulan Analisis

Platform Web memiliki keunggulan dalam kemudahan akses dan distribusi karena pengguna dapat mengakses aplikasi melalui browser tanpa melakukan instalasi. Platform Desktop lebih unggul dalam performa serta akses terhadap resource perangkat dan dapat digunakan secara offline. Sementara itu, platform Mobile memiliki keunggulan dalam mobilitas serta pemanfaatan fitur perangkat seperti kamera, GPS, dan notifikasi.

Pemilihan platform sebaiknya disesuaikan dengan kebutuhan aplikasi, target pengguna, karakteristik perangkat, serta sumber daya yang tersedia untuk proses pengembangan.