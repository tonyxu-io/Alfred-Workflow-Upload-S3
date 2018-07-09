# Alfred Workflow: Upload Clipboard Image to AWS S3

This workflow helps you upload image in your clipboard to S3 and put the public url of the image to your clipboard.
This workflow is especially helpful if you are a markdown fan and you can easily get public url and use it in markdown document.

## Overview

This workflow is written in Python. And used Boto3 as AWS client to upload image.

## Usage

1. Take a screenshot using `Command` + `Control` + `Shift` + `4`
2. Bring up Alfred
3. Type `Upload`
4. Select `Upload to S3`
5. Wait until you receive public url in push notification
6. Now you can paste the public url in browser to see the image from S3
