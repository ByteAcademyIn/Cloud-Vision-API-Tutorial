# Cloud-Vision-API-Tutorial
Detect Labels, Faces, and Landmarks in Images with the Cloud Vision API

Once you have created a json file specifying the query type, use this code snippet to run the query:


```bash
curl -s -X POST -H "Content-Type: application/json" --data-binary @request.json  https://vision.googleapis.com/v1/images:annotate?key=${API_KEY}
