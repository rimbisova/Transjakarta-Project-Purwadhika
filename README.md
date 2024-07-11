# Transjakarta-Project-Purwadhika
# Latar Belakang dan Identifikasi Masalah
TransJakarta merupakan pionir sistem Bus Rapid Transit (BRT) di kawasan Asia Tenggara dan Selatan. Diluncurkan pada tahun 2004, layanan ini menjadi solusi transportasi massal untuk mendukung mobilitas penduduk di ibukota Indonesia yang padat, Jakarta. Sebagai sistem BRT dengan jalur terpanjang di dunia, TransJakarta membentang sepanjang 251,2 kilometer. Jaringan transportasi ini terdiri dari 13 koridor utama yang dilengkapi dengan 287 halte, menjangkau berbagai area strategis di kota. Dengan infrastruktur yang ekstensif ini, TransJakarta berperan penting dalam mengakomodasi kebutuhan pergerakan penduduk di salah satu kota terpadat di dunia.


# Tujuan Analisa Data
<ul> Meningkatkan profit dan fasilitas transjakarta

# Metode
<li>Mengetahui waktu terpadat (peak hour) pada moda transportasi TransJakarta dan jumlah jam sibuk dan jam tidak sibuk </li>
<li>Mengetahui lokasi terpadat asal dan tujuan berdasarkan data Tap-In dan Tap-Out pengguna TransJakarta</li>
<li>Menganalisa demografi pengguna TransJakarta</li>
<li>Menganalisa penggunaan metode pembayaran</li>

</ul>

# Deskripsi data
Transjakarta.csv
1.	transID: Unique transaction id for every transaction
2.	payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
3.	payCardBank: Customers card bank issuer name
4.	payCardName: Customers name that is embedded in the card.
5.	payCardSex: Customers sex that is embedded in the card
6.	payCardBirthDate: Customers birth year
7.	corridorID: Corridor ID / Route ID as key for route grouping.
8.	corridorName: Corridor Name / Route Name contains Start and Finish for each route.
9.	direction: 0 for Go, 1 for Back. Direction of the route.
10.	tapInStops: Tap In (entrance) Stops ID for identifying stops name
11.	tapInStopsName: Tap In (entrance) Stops Name where customers tap in.
12.	tapInStopsLat: Latitude of Tap In Stops
13.	tapInStopsLon: Longitude of Tap In Stops
14.	stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
15.	tapInTime: Time of tap in. Date and time
16.	tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
17.	tapOutStopsName: Tap out (exit) Stops Name where customers tap out.
18.	tapOutStopsLat: Latitude of Tap Out Stops
19.	tapOutStopsLon: Longitude of Tap Out Stops
20.	stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
21.	tapOutTime: Time of tap out. Date and time
22.	payAmount: The number of what customers pay. Some are free. Some not
