# DownloadVideoCapCut
Source: https://downloadvideocapcut.com/

This will help you to download videos from capcut: 
<!DOCTYPE html>
<html>
<head>
  <title>CapCut Template Video Loader</title>
  <!-- Include Materialize CSS CDN -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
  <style>
    body {
      background-color: #536976;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      max-width: 400px;
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    /* Custom Input Styles */
    .input-field input[type=text] {
      border: none;
      border-bottom: 1px solid #2196F3;
      outline: none;
      box-shadow: none;
      height: 2rem;
      font-size: 1.2rem;
    }

    .input-field label {
      position: absolute;
      top: 1.2rem;
      left: 0;
      color: #9e9e9e;
      font-size: 1rem;
      pointer-events: none;
      transition: 0.2s ease-out;
    }

    .input-field input[type=text]:focus + label,
    .input-field input[type=text]:valid + label {
      top: -0.8rem;
      font-size: 0.8rem;
      color: #2196F3;
    }

    .input-field .helper-text {
      margin: 0;
      padding-top: 0.5rem;
      font-size: 0.8rem;
      color: #888;
    }

    .center-align {
      display: flex;
      justify-content: center;
      margin-top: 1rem;
    }

    /* Blue Button Styles */
    .btn-blue {
      background-color: #2196F3;
      color: #fff;
    }

    .btn-blue:hover {
      background-color: #1976D2;
    }
  </style>
</head>
<body>
  <div class="container">
    <h3>CapCut Template Video Loader</h3>
    <form>
      <div class="input-field">
        <input type="text" id="videoUrl" class="validate">
        <label for="videoUrl">CapCut Video URL</label>
      </div>
      <div class="center-align">
        <button type="button" class="btn btn-blue waves-effect waves-light" onclick="showPopup()">Load Video</button>
      </div>
    </form>
  </div>

  <!-- Include Materialize JS CDN -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
  <script>
    function showPopup() {
      var videoUrl = document.getElementById('videoUrl').value;

      // Create a popup window with the video URL
      var popupWindow = window.open(videoUrl, 'CapCut Video', 'width=800,height=600');
      
      // Create a button inside the popup window
      var button = document.createElement('button');
      button.textContent = 'Close';
      button.className = 'btn btn-blue waves-effect waves-light';
      button.addEventListener('click', function() {
        popupWindow.close();
    </body>
  </html>
