```python

{
  "requests": [
      {
        "image": {
          "source": {
              "gcsImageUri": "gs://your-bucket-name/your-filename.png"
          }
        },
        "features": [
          {
            "type": "LABEL_DETECTION",
            "maxResults": 10
          }
        ]
      }
  ]
}
