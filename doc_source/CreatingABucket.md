# Klasör Oluşturma<a name="CreatingABucket"></a>



![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

AWS Hesabınızı oluşturduğunuza göre şimdi AWS Yönetin Konsolu kullanarak yeni bir klasör yaratmaya hazırsınız. Amazon S3 içerisiğinde bulunan her bir nesne mutlaka bir klasör içinde depolanır. Bu yüzden herhangi bir nesneyi depolamadan önce mutlaka bir klasör yaratmalıyız.

**Not**  

Klasör yaratmanın herhangi bir maliyeti yoktur. Amazon S3 içerisinde verilerinini depolamadığınız yada klasörünüz içine yada dışına herhangi bir transfer işlemi gerçekleştirmediğiniz sürece Amazon S3 herhangi bir ücretlendirme yapmayacaktır. Yapacağımız bu işlemlerde çok düşük bir miktarda ücretlendirme olabilir \($1 dan az\)\. Amazon S3 fiyatlandırması ile alakalı daha detaylı bilgi için bu sayfayı ziyaret ediniz.  [Amazon S3 Fiyatlandırma](https://aws.amazon.com/s3/pricing/)\.

**To create an S3 bucket**

1. Sign in to the AWS Management Console and open the Amazon S3 console at [https://console\.aws\.amazon\.com/s3/](https://console.aws.amazon.com/s3/)\.

1. Choose **Create bucket**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/create-bucket.png)

1. In the **Bucket name** field, type a unique DNS\-compliant name for your new bucket\. \(The example screen shot uses the bucket name admin\-created\. You cannot use this name because S3 bucket names must be unique\.\) Create your own bucket name using the follow naming guidelines: 

   + The name must be unique across all existing bucket names in Amazon S3\. 

   + After you create the bucket you cannot change the name, so choose wisely\. 

   + Choose a bucket name that reflects the objects in the bucket because the bucket name is visible in the URL that points to the objects that you're going to put in your bucket\.

   For information about naming buckets, see [ Rules for Bucket Naming](http://docs.aws.amazon.com/AmazonS3/latest/dev//BucketRestrictions.html#bucketnamingrules) in the *Amazon Simple Storage Service Developer Guide*\. 

1. For **Region**, choose US West \(Oregon\) as the region where you want the bucket to reside\.  

1. Choose **Create**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/gsg-create-bucket-name-region.png)

You've created a bucket in Amazon S3\. 

