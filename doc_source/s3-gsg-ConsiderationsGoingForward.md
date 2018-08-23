# Considerations Going Forward<a name="s3-gsg-ConsiderationsGoingForward"></a>


+ [AWS Account and Security Credentials](#iam-about-shared)
+ [Security](#s3-gsg-Security)
+ [AWS Integration](#s3-gsg-AWSIntegration)
+ [Pricing](#s3-gsg-Pricing)

Bu bölüm AWS S3 servisi kullanmaya başlayacak kişilerin dikkat etmesi gereken konuları işlemektedir.

This section introduces you to topics you should consider before launching your own Amazon S3 product\.

## AWS Hesabı ve Güvenlik <a name="iam-about-shared"></a>

AWS kayıt işlemleri sırasında kullandığınız eposta adresi ve parola sizin hesabınıza ait kök kullanıcı hesabıdır. AWS kök kullanıcı hesabını günlük rutin işlemler için kullanmak yerine bu işler için başka bir hesap kullanmanızı ve kök hesap bilgilerini başkasıyla asla paylamamanızı önerir.  Yönetici kullanıcılar için dahi IAM servisi üzerinden yönetici hesabı açılması ve bütün düzenlemelerin bu işler üzerinden gerçekleştirilmesi önerilir. Daha fazla bilgi için : [İlk yönetici hesabını ve grubunu oluşturmak](http://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html) *IAM User Guide*\.


Eğer hesabın sahibi yada yönetiyseniz ve IAM hakkında fazla fazla bilgi edinmek istiyorsanız 
 [https://aws\.amazon\.com/iam](https://aws.amazon.com/iam) yada teknik dökümanlar için [IAM User Guide](http://docs.aws.amazon.com/IAM/latest/UserGuide/)\.

## Güvenlik<a name="s3-gsg-Security"></a>

Amazon S3 servisinde verilen güvenli şekilde saklanması için gelişmiş bir kimlik doğrulama sistemi mevcuttur. Siz aksini özellikle ayarlamadığınız şekilde sadece AWS hesabının sahibi Amazon S3 klasörlerine ulaşabilir. Klasörlerin erişim yetkilerini nasıl düzenleyebileceğiniz hakkında daha fazla bilgi edinmek için [Managing Access Permissions to Your Amazon S3 Resources](http://docs.aws.amazon.com/AmazonS3/latest/dev/s3-access-control.html) 

Aynı zamanda isterseniz verilerinizi Amazon S3 üzerine yüklemeden önce şifreleyebilirsiniz.

## AWS Entegrasyonu<a name="s3-gsg-AWSIntegration"></a>

AWS S3 servini tek başına yada gerektiği zaman diğer AWS servisleri ile beraber kullanabilirsiniz. Amazon S3 servisinin en sık birlikte kullanıldığı diğer ürünler:

+ [Amazon EC2](https://aws.amazon.com/ec2/)

+ [Amazon Elastic MapReduce](https://aws.amazon.com/elasticmapreduce/)

+ [Amazon SQS](https://aws.amazon.com/sqs/)

+ [Amazon CloudFront ](https://aws.amazon.com/cloudfront/)

+ [Amazon DevPay](https://aws.amazon.com/devpay/)

## Ücretlendirme<a name="s3-gsg-Pricing"></a>

Amazon S3 üzerine veri depolama ve veri transferi ile alakalı ücretlendirme politikası hakkında bilgi alınız. Bu konu hakkında daha fazla bilgi edinmek isterseniz. [Amazon S3 Pricing](https://aws.amazon.com/s3/pricing/)\.
