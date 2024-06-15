<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <header>
        <h1>Media Elements Example</h1>
    </header>
    <main>
        <div class="media-section">
            <h2>Audio Player</h2>
            <audio controls>
                <source src="audio.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <p class="media-description">This is an example audio player. You can listen to the audio file using the controls provided.</p>
        </div>
        <div class="media-section">
            <h2>Video Player</h2>
            <video controls width="600">
                <source src="video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <p class="media-description">This is an example video player. You can watch the video using the controls provided.</p>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Media Elements Example</p>
    </footer>
</body>
</html>
