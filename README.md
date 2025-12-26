# vertical-image-viewer
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>縦長画像ビューア</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <main class="viewer">
    <img src="images/sample1.jpg" alt="image1">
    <img src="images/sample2.jpg" alt="image2">
  </main>
</body>
</html>
body {
  margin: 0;
  background: #111;
}

.viewer {
  max-width: 800px;
  margin: 0 auto;
}

.viewer img {
  width: 100%;
  height: auto;
  display: block;
}
