# EveryPixel-API

EveryPixel is a powerful search engine that indexes 50 paid and free stock image websites, and allows users to search through a massive database of stock photos in seconds.

The code below is to request information via EveryPixel API by the use of three methods.

## 1. A list of suggested keywords

By sending an image to this method you can get a list of suggested keywords. You may specify a number of returned words or a threshold of its minimum score. Just provide num_keywords or threshold parameter to this method. If you don't want to receive location keywords, filter them using the parameter filter=no_loc. Image should be specified by its url or uploaded with multipart form by parameter 'data'. You should use, respectively, GET and POST methods.

## 2. Stock photo score
This method allows you to get the quality score for your photo. This service doesn't measure how cool or beautiful a person or an object on a photo may look. It cares only about technical parts like brightness, contrast, noise and so on. The service is not dedicated for scoring historical photos, illustrations or 3D visualizations. Image should be specified by its url or uploaded with multipart form by parameter 'data'. You should use, respectively, GET and POST methods.

## 3. User-Generated Photo Scoring
The main difference between Stock photo scoring and this model is in the training dataset. User-Generated Photo Scoring is a model trained on a 347 000 of user photos from Instagram. Estimation parameters for this model were prepared by a group of 10 professional photographers. Scoring methods are based on five classes: very bad (0-20), bad (20-40), normal (40-60), good (60-80) and excellent (80-100). This model is designed to evaluate user photos taken both by a professional camera and by a camera of a smartphone. It doesn't estimate the plot and do not measure how cool or beautiful a person or an object on a photo may look. It cares only about technical parts like brightness, contrast, noise and so on. The service is not dedicated for scoring historical photos, illustrations or 3D visualizations. Image should be specified by its url or uploaded with multipart form by parameter 'data'. You should use, respectively, GET and POST methods.

### For a demo please follow [this link](https://labs.everypixel.com/api/demo).
