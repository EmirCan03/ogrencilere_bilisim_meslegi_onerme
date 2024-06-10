3.Veri Kümesi Hakkında
Bu veri seti, öğrencilerin teknik ve sosyal becerilerinin yanı sıra hackathonlara katılımları ve belirli araçlar veya dillerdeki yeterlilikleri hakkında ayrıntılı bir görünüm sunar. Öğrenciler arasındaki beceri eğilimlerini ve işe yerleştirme uygunluğunu analiz etmekle ilgilenen eğitim kurumları, işe alım görevlileri veya araştırmacılar için idealdir. Veri seti; Veri Yapıları ve Algoritmalar , Veritabanı Yönetim Sistemleri, İşletim Sistemleri, Matematik ve çeşitli sosyal beceriler gibi alanları kapsayarak her öğrencinin yeteneklerine ilişkin bütünsel bir görünüm sağlar.
Bu veri seti, öğrencilerin becerilerini ve ilgi alanlarını analiz etmek için kullanılabilir ve öğrencilerin UI/UX, yazılım mühendisi, veri bilimi vb. gibi farklı profesyonel profillere uygunluklarının belirlenmesine yardımcı olabilir.

4.VERİ SETİ İÇERİĞİ
 
	DSA:  Veri Yapıları Algoritmalar
	DBMS: Veritabanı Yönetim Sistemleri
	OS: İşletim Sistemleri
	CN: Bilgisayar Ağları
	Mathmetics: Matematik Becerileri
	Aptitute: Genel Yetenek
	Comm: İletişim Yetenekleri
	Problem Solving: Problem çözme yetenekleri
	Creative: Yaratıcılık düzeyi
	Hackathons: Hackathonlara katılım düzeyi
	Skill: Belirli araçlar veya dillerdeki yeterlilikler
	Profile: Potansiyel profesyonel profil uygunluğu

Veri setimiz 707 satır ve 12 sütundan oluşmaktadır. Veri setinde eksik değerler yoktur.
2 tane object türünde verimiz var.

Skill sütununda olan değerler:
 
Skill sütunundaki verileri sayısal değere dönüştürdüğümüzde aldıkları değerler:
 0=Angular, 1=Ansible, 2=BASH/SHELL, 3=C/C++,  4=Cisco Packet tracer, 5=Deep Learning, 6=figma, 7=Github, 8=HTML/CSS,  9=Java, 10=javascprit, 11=Linux, 12=Mysql, 13=Machine Learning, 14=Node.js, 15=Oracle, 16=photoshop, 17=Python, 18=Pytorch, 19=R, 20=react, 21=Tensorflow, 22=Wire Shark 
  
Profile sütununda olan değerler:  
Profile sütunundaki verileri sayısal değere dönüştürdüğümüzde aldıkları değerler:
0=DATA Scientist, 1=Database Administrator, 2=Network Engineer, 3=Software Developer, 4=Tech Support, 5=UI/UX, 6=Web Developer
Temel İstatistik Özeti:
 
Count (Sayı): Her bir sütundaki non-null (null olmayan) değerlerin sayısını temsil eder.
Mean (Ortalama): Her bir sütundaki sayısal değerlerin ortalamasını gösterir. 
Std (Standart Sapma):Her bir sütundaki sayısal değerlerin yayılma (varyans) derecesini ölçer. Daha yüksek bir standart sapma, değerlerin ortalamadan daha fazla dağıldığını gösterir
25%, 50%, 75% (Çeyrekler):Verileri küçükten büyüğe sıraladığınızda, %25, %50 ve %75'inci pozisyonlardaki değerleri temsil eder.
Min (Minimum):Her bir sütundaki en küçük değeri gösterir.
Max (Maksimum):Her bir sütundaki en büyük değeri gösterir.














5.KORELASYON GRAFİĞİ
 
Korelasyon grafiği ortadan çapraz olarak 2’ye bölünmüştür. Farklı renk paleti ile renkler farklı anlamlara gelebilir. Bu grafikte mor renkler negatif korelasyonu, turuncu renkler pozitif korelasyonu temsil eder.
Çok güçlü korelasyona (0.8 ile 1) sahip değişken çiftlerine bakalım:
“OS” ile “DSA”=(0.8)				“Aptitute” ile “CN”=(0.83)			
 “OS” ile “DBMS”=(0.82)			“Aptitute” ile “Mathmatics”=(0.86)		
“CN” ile “DSA”=(0.85)				“Problem Solving” ile “Mathmatics”=(0.8)	
“Mathmatics” ile “DSA”=(0.85)		“Problem Solving” ile “Aptitute”=(0.81)	
“Aptitute” ile ”DSA”=(0.84)


6.KUTU-BIYIK GRAFİĞİ
Örnek:
 
DSA sütunun kutu bıyık grafiğinde alt sınır=5, üst sınır=99
1.Çeyreklik=45
Medyan= 67
3.Çeyreklik=80
 
DBMS sütunun kutu bıyık grafiğinde alt sınır=5, üst sınır=100
1.Çeyreklik=40
Medyan= 76
3.Çeyreklik=80


 OS sütunun kutu bıyık grafiğinde alt sınır=5, üst sınır=95
1.Çeyreklik=53
Medyan= 73
3.Çeyreklik=82.5

CN sütunun kutu bıyık grafiğinde alt sınır=5, üst sınır=100
1.Çeyreklik=38
Medyan= 62
3.Çeyreklik=80

Mathmetics sütunun kutu bıyık grafiğinde alt sınır=0, üst sınır=99
1.Çeyreklik=22
Medyan= 48
3.Çeyreklik=78

Aptitute sütunun kutu bıyık grafiğinde alt sınır=13, üst sınır=99
1.Çeyreklik=35
Medyan= 60
3.Çeyreklik=35

 Comm sütunun kutu bıyık grafiğinde alt sınır=40, üst sınır=90
1.Çeyreklik=62
Medyan= 71
3.Çeyreklik=78

Problem Solving sütunun kutu bıyık grafiğinde alt sınır=1, üst sınır=10
1.Çeyreklik=4
Medyan= 6
3.Çeyreklik=7

Creative sütunun kutu bıyık grafiğinde alt sınır=2, üst sınır=10
1.Çeyreklik=5
Medyan= 6
3.Çeyreklik=7

Hackathons sütunun kutu bıyık grafiğinde alt sınır=1, üst sınır=10
1.Çeyreklik=1
Medyan= 3
3.Çeyreklik=5
Skill sütunun kutu bıyık grafiğinde alt sınır=0, üst sınır=22
1.Çeyreklik=7
Medyan= 10
3.Çeyreklik=17
Profile sütunun kutu bıyık grafiğinde alt sınır=0, üst sınır=
1.Çeyreklik=1
Medyan= 3
3.Çeyreklik=5


7.Histogram Grafikleri

Histogram, bir veri setinin dağılımını gösteren bir grafik türüdür. Genellikle sürekli bir değişkenin değerlerini belirli aralıklara bölen ve her aralıktaki gözlemlerin sayısını gösteren sütunlu bir grafiktir. Bu grafik, veri setinin genel formunu, merkezi eğilimini, dağılımını ve aykırı değerleri görselleştirmek için kullanılır.
Histogramın temel özellikleri şunlardır:
1.	Sütunlar (Barlar): Histogram, belirli aralıklarda bulunan değerlerin sayısını temsil eden dikdörtgen sütunlardan oluşur. Her sütun, bir aralıktaki değerlerin frekansını ifade eder.
2.	Aralıklar (Bins): Veri seti değerlerini bölmek için kullanılan aralıklar histogramdaki sütunları belirler. Genellikle bu aralıklar eşit büyüklükte olup, veri setindeki değerlerin geniş bir yelpazede görüntülenmesini sağlar.
3.	Eksenler: Histogramın yatay ekseninde değerlerin aralıkları, dikey ekseninde ise her aralıktaki değerlerin frekansları yer alır.
Histogramın yorumlanması aşağıdaki adımları içerir:
•	Merkezi Eğilim: Histogram, veri setindeki merkezi eğilimi görselleştirmek için kullanılabilir. Veri setindeki modu (en sık tekrarlanan değer), medyanı veya ortalama değeri belirleme konusunda yardımcı olabilir.
•	Dağılım: Histogram, veri setindeki değerlerin nasıl dağıldığını gösterir. Normal dağılmış bir veri seti, simetrik bir histograma sahip olabilirken, çarpık bir dağılım farklı bir şekilde görünebilir.
•	Aykırı Değerler: Histogram, aykırı değerleri tanımlamak için kullanılabilir. Eğer bir aralıkta diğerlerine göre çok daha fazla gözlem varsa veya bir sütun diğerlerine göre belirgin bir şekilde uzunsa, bu durumda aykırı değerler olabilir.


 

 
