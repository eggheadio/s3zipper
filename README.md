# s3zipper
Microservice that Servers Streaming Zip file from S3 Securely

## Read the blog here
[Original Blog Post](http://engineroom.teamwork.com/how-to-securely-provide-a-zip-download-of-a-s3-file-bundle/)


## Redis Schema

```
zip:<random ref string> = [
    {
        "S3Path":"path/to/sample.txt",
        "FileName":"sample.txt",
        "Folder":"folder/within/zip/file"
    }
    ...
]
```
