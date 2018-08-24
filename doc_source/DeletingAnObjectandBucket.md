# Nesne ve Klasör Silmek<a name="DeletingAnObjectandBucket"></a>



![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

Daha önce yüklediğiniz yüklediğimiz ve daha sonra bir kopyasını oluşturduğumuz nesnelere artık ihtiyacımız yoksa bunları silebilir.

Klasör içerisindeki nesleleri ayrı ayrı silebilir yada dilersek komple klasör içini boşaltabiliriz.

Ayrıca içerisinde bulunan bütün objelerle beraber ana klasörü de tamamen silebiliriz. Ancak eğer aynı ana klasör ismini kullanmaya devam etmek istiyorsanız dosyayı silmeyiniz. Biz ana klasörü silmek yerine içeriğinin boşaltılıp boş olarak saklanmasını öneririz. Bir ana klasör silindiğinde başka kullanıcılar tarafından tekrar kullanılabilir hale ancak bazı sebeplerden dolayı sizin tarafınızdan kullanılamayacak hala gelebilir. Örnek olarak siz aynı ana klasörü tekrar yaratana kadar başka bir kullanıcı aynı ismi kayıt altına alabilir.

**To delete an object from a bucket**

1. In the **Bucket name** list, choose the name of the bucket that you want to delete an object from\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/choose-bucket-name.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

1. In the **Name** list, select the check box next to the object that you want to delete, choose **More**, and then choose **Delete**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/more-menu-delete.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

1. In the **Delete objects** dialog box, verify that the name of the object you selected for deletion is listed, and then choose **Delete**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/objects-delete-confirm.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

You can empty a bucket, which deletes all the objects in the bucket without deleting the bucket\.

**To empty a bucket**

1. In the **Bucket name** list, choose the bucket icon next to the name of the bucket that you want to empty and then choose **Empty bucket**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/choose-empty-bucket.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

1. In the **Empty bucket** dialog box, type the name of the bucket for confirmation and then choose **Confirm**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/empty-bucket-confirm.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

You can delete a bucket and all the objects contained in the bucket\. 

**Important**  
If you want to continue to use the same bucket name, don't delete the bucket\. We recommend that you empty the bucket and keep it\. After a bucket is deleted, the name becomes available to reuse, but the name might not be available for you to reuse for various reasons\. 

**To delete a bucket**

1. In the **Bucket name** list, choose the bucket icon next to the name of the bucket that you want to delete and then choose **Delete bucket**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/choose-delete-bucket.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

1. In the **Delete bucket** dialog box, type the name of the bucket for delete confirmation and then choose **Confirm**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/delete-bucket-confirm.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

Next, see [Where Do I Go From Here?](ImplementingS3.md)\.
