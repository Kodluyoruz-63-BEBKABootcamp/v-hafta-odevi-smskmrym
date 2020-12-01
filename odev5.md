- SQLite ve LocalDB kavramlarını karşılaştırınız.

 SQL:

SQL, Yapılandırılmış Sorgu Dili anlamına gelir. Veritabanlarına erişmek ve işlemek için standart bir dildir.
SQL, SEQUEL (Yapısal İngilizce Sorgu Dili), RDBMS (İlişkisel Veritabanı Yönetim Sistemleri) için bir dildir. SQL, IBM Corporation tarafından geliştirilmiştir.

 SQL Server:

SQL Server, Microsoft'un ilişkisel veritabanı yönetim sistemidir (RDBMS). Öncelikle rakipler Oracle Database (DB) ve MySQL'e karşı rekabet etmek için tasarlanmış tam özellikli bir veritabanıdır.
Tüm büyük RBDMS gibi SQL Server da standart SQL dili olan ANSI SQL'i destekler. Ancak, SQL Server, kendi SQL uygulaması olan T-SQL'i de içerir. SQL Server Management Studio (SSMS) (önceden Enterprise Manager olarak biliniyordu) SQL Server'ın ana arayüz aracıdır ve 32 bit ve 64 bit ortamları destekler.
SQL Server bazen MSSQL ve Microsoft SQL Server olarak adlandırılır.

 MYSQL:

MySQL, SQL Server, Oracle, Informix, Postgres vb. Gibi bir veritabanı yönetim sistemidir. MySQL bir RDMS (İlişkisel Veritabanı Yönetim Sistemi) 'dir.
MySQL bir Oracle veritabanıdır. Diğer her şey kadar uygun maliyetli bir şekilde pazarlanmaktadır. Rakipler Microsoft SQL Server'ı içerir.

 SQLite:

SQLite bir SQL sunucusu kadar değildir. Gerçekten sadece bir veritabanı sistemidir. Veritabanları uygulamalara gömülebilir veya bir sunucudan daha çok bir metin dosyasına erişildiği gibi ek "sunucu" kaynağı olmadan yerel olarak kullanılabilir. Daha yakın bir ürün Microsoft SQL CE (Compact Edition) olacaktır.
Mini SQL (mSQL), Huges Technologies tarafından işletmeler ve veri evleri için bellek tasarruflu, taşınabilir ve performans açısından verimli bir seçenek olarak oluşturulan hafif bir veritabanı yönetim sistemidir (DBMS). Başlangıçta 1994 yılında geliştirilmiş ve piyasaya sürülmüş, mSQL'in üç versiyonu piyasaya sürülmüştür. Geliştirilmiş motoru, hem büyük hem de küçük ölçekli veritabanları ve küçük bir depolama çözümü gerektiren uygulamalar için uygundur.

 Msql:

Mini SQL (mSQL) hafif bir SQL veritabanı motoru teknolojisidir. Şimdi büyük ölçüde benzer işlevselliğe sahip MySQL ile değiştirildi. MSQL artık MySQL kadar görünür değil, çünkü çoğu şirket yazılımı kurumsal kullanım için lisanslıyor, dolayısıyla bireysel kullanıcılar yazılımı doğrudan kullanım için almıyor. Mini SQL hala ticari olmayan, kar amacı gütmeyen kuruluşlar ve eğitim ve araştırma amaçlı ücretsiz yazılım olarak kullanılabilir. Cisco, HP, General Electric ve Real Networks gibi birçok şirket mSQL kullanımını uygulamalarıyla birleştirdi.

- Lazy Loading kavramı hakkında temel bir araştırma yapınız.

 Lazy Load diğer adıyla Dynamic Function Loading, bant genişliği tasarrufu ile site hızını artırmayı sağlayan bir moddur. Genel anlamıyla bir nesnenin ihtiyaç duyulmadığında çağrılmamasına dayanmaktadır. Oluşturduğumuz nesneleri ihtiyacımız olmadığı zamanlar kullanmazsak bir performans artışı sağlarız.

Lazy Load, görsel yoğunluğu ve sayfa uzunluğu (aşağı doğru) fazla olan sitelerde, sitenin geç açılmasını engellemek amacı ile ek bir Javascript dosyasının kullanılmasıdır. Bu özelliğin kullanıldığı bir web sayfası açıldığında ekranda henüz yer almayan resimlerin yüklenmesi önlenmektedir. Sayfada var olan tüm görsellerin aynı anda yüklenmesi engellenir ve sadece kullanıcının ekranında yer alan görseller yüklenir. Kısacası; herhangi bir görseli gerekli görmedikçe yaratmamayı öngörür.

Lazy Load daha çok e-ticaret sitelerinde kullanılmaktadır. Görsel listelemenin yoğun olarak kullanıldığı e-ticaret sitelerinde; oluşan görsel fazlalığı site hızını olumsuz etkiler. Bunun ana nedeni sayfaya girildiğinde tüm görsellerin aynı anda sunucudan çağrılması ve yüklenmesidir. Ancak Lazy Load özelliği kullanıldığı zaman sayfada listelenen ürünlerin görselleri aşağı doğru inildikçe yani gerek duyuldukça açılır. Bu şekilde site hızında artış sağlanır. Lazy Load özelliği kullanılmadığında; ürün listeleme yapıldığı zaman; aşağı doğru gidildiğinde tüm fotoğraflar sayfa daha ilk açıldığında yüklenmeye çalışır ve o sayfada kaç ürün varsa tamamı aynı anda sunucudan çağırılır ve yüklenir. Bu durum site hızını düşürürken aynı zamanda sitenin açılmasını ve istediği ürüne ulaşmayı bekleyen ziyaretçilerin siteden çıkmasına neden olmaktadır.

