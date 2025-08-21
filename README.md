# CodeAlpha-Tasks
SOURCE CODE FOR RESPONSIVE GALLERY
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Gallery</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Image Gallery</h1>
  
  <div class="gallery">
    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRpJph3mejAU0C6iWktk6ySpM5XqswZ7eEG8yqstM2E6yT6uW9" alt="Image 1">
    </div>
    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTzVLLyKEIMLh2LTkG6LfWZ5hpWJ2BL2GP2Sw" alt="Image 2">
    </div>
    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3Pdn9v3hemAU0C6iWktk6ySpM5XqswZ7eEG8yqstM2E6yT6uW9" alt="Image 3">
    </div>
    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjFqbn_AiW05CQA-YTLVLeKmILH2TLcUKJtiw&usqp=CAU" alt="Image 4">
    </div>
  </div>
  </body>
  </html>
  CSS
  * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  padding: 20px;
  text-align: center;
}

h1 {
  margin-bottom: 20px;
  color: #333;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 15px;
  max-width: 800px;
  margin: 0 auto;
}

.gallery-item {
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  transition: transform 0.3s ease;
}

.gallery-item:hover {
  transform: scale(1.05);
}

.gallery-item img {
  width: 100%;
  height: auto;
  display: block;
}
  </div>
</body>
</html>
