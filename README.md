# Alfred Workflow: Upload Image to AWS S3

This workflow helps you upload image in your clipboard or local disk to S3 and put the public url of the image to your clipboard.
This workflow is especially helpful if you are a markdown fan and you can easily get public url and use it in markdown document.

## Overview

This workflow is written in Python. And used Boto3 as AWS client to upload image.

## Download

https://github.com/tonyxu-io/Alfred-Workflow-Upload-S3/releases

## Usage

1. Take a screenshot using `Command` + `Control` + `Shift` + `4`
2. Bring up Alfred
3. Type `Upload`
    1. Select `Upload Clipboard Image` to directly upload image in your clipboard
    2. Select `Upload Local Image` and search your image file to upload image from your local disk, then type enter
4. Wait until you receive public url in push notification
5. Now you can paste the public url in browser to see the image from S3

## Tutorials

Check out my blog to see how I made this workflow:

https://tonyxu.io/posts/create-alfred-workflow-for-uploading-screenshot-to-s3/
