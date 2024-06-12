<link rel="stylesheet" href="APlayer.min.css">
<div id="aplayer"></div>
<script src="APlayer.min.js"></script>

const ap = new APlayer({
    container: document.getElementById('aplayer'),
    audio: [{
        name: 'name',
        artist: 'artist',
        url: 'url.mp3',
        cover: 'cover.jpg'
    }]
});
