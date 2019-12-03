
##Ruby script to interact with s3 buckets**

Provides options to:

List buckets              
```
-a lb
```

List bucket sizes         
```
-a lbs
```

Create bucket            
```
-a b -b <bucketname>
```

Add bucket policy         
```
-a ap -b <bucketname> -u <account:user or user>
```

Show bucket policy        
```
-a sp -b <bucketname>
```

Delete bucket policy      
```
-a dp -b <bucketname>
```

Add bucket ACL            
```
-a aa -b <bucketname> -c <canned_acl_profile: pr, pur, purw, aer, ar, bor, bof, ldw>
```

Add object ACL            
```
-a aa -b <bucketname> -k <key> -c <canned_acl_profile: pr, pur, purw, aer, ar, bor, bof, ldw>
```

Delete bucket             
```
-a db -b <bucketname>
```

Detail bucket info        
```
-a ib -b <bucketname>
```

List bucket Files         
```
-a lf -b <bucketname>
```

Add file, zip if folder
metadata optional         
```
-a f -b <bucketname> -k <key> -f <filename> -m <metakey_1:value_1...>
```

Detail file info          
```
-a if -b <bucketname> -k <key>
```

Delete file from bucket   
```
-a df -b <bucketname> -k <key>
```

Download file             
```
-a rf -b <bucketname> -k <key> -f <new_filename>
```

Download file and unzip   
```
-a rfu -b <bucketname> -k <key> -f <filename>
```

Add lifecycle to bucket   
```
-a al -b <bucketname> -l <json file>
```

Delete lifecycle          
```
-a dl -b <bucketname>
```

Show lifecycle            
```
-a sl -b <bucketname>
```
