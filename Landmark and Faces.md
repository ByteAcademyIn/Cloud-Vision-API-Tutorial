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
            "type": "FACE_DETECTION"
          },
          {
            "type": "LANDMARK_DETECTION"
          }
        ]
      }
  ]
}
