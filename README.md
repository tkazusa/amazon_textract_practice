# Amazon textract practice
A brief example for [Amazon textract](https://aws.amazon.com/jp/textract/) drawing detected objects on the original document.

## Requirements
Required python modules are followings.

- boto3 >= 1.9.163
- pdf2image >= 1.5.4
- pillow >= 6.0.0

```
pip3 install -r requirements.txt
```

For pdf2image, a PDF rendering library called [Poppler](https://poppler.freedesktop.org/) is also required.

## References
- [Analyzing Document Text with Amazon Textract](https://docs.aws.amazon.com/textract/latest/dg/analyzing-document-text.html)
