# internetchild
You Found Me &lt;3

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@moefe/vue-aplayer@^1.9.9/dist/APlayer.min.css">
  <script src="https://cdn.jsdelivr.net/npm/vue@2"></script>
  <script src="https://cdn.jsdelivr.net/npm/@moefe/vue-aplayer@^1.9.9/dist/APlayer.min.js"></script>
  <title>My Music Website</title>
</head>
<body>
  <div id="app">
    <aplayer
      :audio="playlist"
      :autoplay="false"
      :lrc-type="3"
    ></aplayer>
  </div>

  <script>
    new Vue({
      el: '#app',
      data: {
        playlist: [
          {
            name: 'Boot up',
            artist: 'internet child',
            url: https://www.dropbox.com/scl/fi/u38k0xzxl0rrrp8cwoufh/October-mix-1.wav?rlkey=kqaurwgo8u25z15ia7koyjrik&dl=0),
            cover: (https://www.dropbox.com/scl/fi/0kjffzksa30ptcjhswytp/aOYd0JMr0CnEPDinqfKE-1-c3x2d.jpg?rlkey=fhoinykexzuqasxhsh2o9dprl&dl=0),
            lrc: 'URL_TO_YOUR_LYRICS_FILE_1.lrc',
          },
          // Add more songs following the same format
        ],
      },
    });
  </script>
</body>
</html>
