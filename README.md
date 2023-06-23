# Sinif-Ag-Analizi

Yönetim Bilişim Sistemleri sınıfındaki öğrenciler arasındaki etkileşim, öğrencilerin telefon numaralarına kayıtlı olup olmadığına göre incelenmiştir. Python programı ve Networkx kütüphanesi kullanılarak, öğrencilerin sınıf ortamında hangi öğrencilerle daha fazla iletişim kurdukları, merkezi bir konumda olan öğrencilerin kim olduğu ve grup içinde etkileşimi düşük olan ve bilgi aktarımı yapmayan bireylerin tespiti yapılmıştır.

--------------------------------------------------------------------------
Araştırmada kullanılan veri seti sınıf mevcudu 45 kişiden oluşan (16 kız,29 erkek) öğrenciler arasında numaralarının kayıtlı olma durumuna göre 0 veya 1 şeklinde matris şeklinde oluşturulmuştur. Excel de oluşturulan veri seti Python programına aynı şekilde aynı türde direkt olarak aktarılmıştır. 

--------------------------------------------------------------------------
Yapılan çalışmanın geneline bakılınca sonuç olarak ağda bulunan düğümler arasında en popüler olan yani diğer düğümler ile iletişimi en yüksek olan E10 düğümüdür. Diğer düğümler ile ilişkisi en düşük düğüm ise E19 düğümüdür. 
	Ağda oluşan kümelere baktığımızda bazı grupların oluşumunda gerçek hayatın etkisi olduğu gözükmektedir. Yani gerçek hayatta yakın arkadaş olan kişiler kümeleri oluşturmaktadır. Örneğin 2.kümede bulunan kız grubu gerçek hayatta da yakın arkadaşlardır.
	Ağda yer alan K7 düğümü otorite ağırlığı en yüksek olan düğümdür. Yine gerçek hayata baktığımızda bu düğümün tüm sınıf grubu içerisinde en aktif olan kişi ve herkes tarafından tanınan kişi olduğunu bilmekteyiz. Aynı şekilde K7 düğümü yakınlık merkeziliği derecelerine baktığımızda başı çekmektedir. Bu da teorimizi güçlü kılmaktadır.
