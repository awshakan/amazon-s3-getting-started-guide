# Klasör Oluşturma<a name="CreatingABucket"></a>



![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

AWS Hesabınızı oluşturduğunuza göre şimdi AWS Yönetin Konsolu kullanarak yeni bir klasör yaratmaya hazırsınız. Amazon S3 içerisiğinde bulunan her bir nesne mutlaka bir klasör içinde depolanır. Bu yüzden herhangi bir nesneyi depolamadan önce mutlaka bir klasör yaratmalıyız.

**Not**  

Klasör yaratmanın herhangi bir maliyeti yoktur. Amazon S3 içerisinde verilerinini depolamadığınız yada klasörünüz içine yada dışına herhangi bir transfer işlemi gerçekleştirmediğiniz sürece Amazon S3 herhangi bir ücretlendirme yapmayacaktır. Yapacağımız bu işlemlerde çok düşük bir miktarda ücretlendirme olabilir \($1 dan az\)\. Amazon S3 fiyatlandırması ile alakalı daha detaylı bilgi için bu sayfayı ziyaret ediniz.  [Amazon S3 Fiyatlandırma](https://aws.amazon.com/s3/pricing/)\.

**Klasör Yaratmak**

1.  
Amazon Yönetin Konsoluna giriş yapın ve Amazon S3 Consolunu açın. [https://console\.aws\.amazon\.com/s3/](https://console.aws.amazon.com/s3/)\.

1. Seçiniz **Klasör Oluştur**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/create-bucket.png)

1.**Klasör İsmi** kutusuna, benzersiz DNS uyumlu bir isim yazmalısınız. (Bu örnekte klasör ismi admin\-created\) Bu ismi kullanamazsınız çünkü S3 klasör isimleri benzersiz olmalılılar. Aşağıdaki kurallara uyarak kendinize bir klasör oluşturunuz. 

   + Belirleyeceğiniz isim global olarak benzersiz olmalıdır.

   + Klasörü oluşturduktan sonra ismini değiştiremezsiniz. Bu yüzden ismi seçerken dikkatli olunuz. 

   + Seçtiğiniz klasör ismi içeriği ile uyumlu olması önerilir. Bu bir zorunluluk değildir ancak klasör isimleri kullanılan URL içerisinde görünür olacağı bilinerek seçilmelidir. 
   
   Klasör isimleri ile ilgili daha fazla bilgi almak için bu bağlantıyı kullanınız. [ Rules for Bucket Naming](http://docs.aws.amazon.com/AmazonS3/latest/dev//BucketRestrictions.html#bucketnamingrules)

1.  **Bölge** için klasörünüzün bulunmasını istediği yeri seçiniz.

1. Choose **Create**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/gsg-create-bucket-name-region.png)

Tebrikler, ilk Amazon S3 klasörünüzü yarattınız.

