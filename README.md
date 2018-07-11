# Alfred Workflow: Upload Image to AWS S3

This workflow helps you upload image in your clipboard or local disk to S3 and put the public url of the image to your clipboard.
This workflow is especially helpful if you are a markdown fan and you can easily get public url and use it in markdown document.

## Overview

This workflow is written in Python. And used Boto3 as AWS client to upload image.

## Download

https://github.com/tonyxu-io/Alfred-Workflow-Upload-S3/releases

## Usage

Config Environment Variables:

- access_key: S3 access key
- secret_key: S3 access secret
- bucket_name: S3 bucket name. e.g. `my-bucket-name`
- bucket_uri: S3 bucket uri without trailing slash. e.g. `https://s3-us-west-1.amazonaws.com/my-bucket-name`

Upload image from clipboard:

```bash
upload
```

Upload image from local:

```bash
upload TYPE-FILENAME-HERE
```

## Tutorials

Check out my blog to see how I made this workflow:

https://tonyxu.io/posts/create-alfred-workflow-for-uploading-screenshot-to-s3/
