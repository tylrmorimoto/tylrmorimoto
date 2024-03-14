<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SPACEPORT2000</title>
<script>
// Set your desired high score
const HIGH_SCORE = 2002;

// Function to call when the game sends a score
function checkGameCompletion(playerScore) {
  if(playerScore >= 2002) {
    // Show the button if the high score is met
    document.getElementById('next level').style.display = 'block';
  }
}

// Function to redirect to the Google Drive folder
function redirectToDrive() {
  window.location.href = 'https://drive.google.com/drive/folders/1wnGI1SQyVXdnYNavQONhBeKvKMUXS_FW';
}
</script>
</head>
<body>

<h1>WELCOME TO SPACEPORT2000!</h1>

<!-- Embed the arcade game -->
<iframe src="https://games.aarp.org/games/atari-asteroids" width="800" height="600"></iframe>

<!-- Button to redirect to Google Drive folder, hidden by default -->
<button id="next level" style="display: none;" onclick="redirectToDrive()">Go to Google Drive Folder</button>

</body>
</html>

