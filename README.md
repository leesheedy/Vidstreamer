<div id="top"></div>




<!-- VIDSTREAMER -->
<br />
<div align="center">
  <a href="https://github.com/leesheedy/Vidstream">
    <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Ftwitter.com%2Fvid_stream&psig=AOvVaw1gW0m75CT3WysTs-A1b8gZ&ust=1642231656345000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCLjDjOjbsPUCFQAAAAAdAAAAABAD" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">VidStreamer</h3>




<!-- ABOUT THE PROJECT -->
## About The Project

Made by Lee sheedy, for streaming data across local networks


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Creating a Server
from vidstream import StreamingServer

server = StreamingServer('127.0.0.1', 9999)
server.start_server()

# Other Code

# When You Are Done
server.stop_server()

### Creating a Client

from vidstream import CameraClient
from vidstream import VideoClient
from vidstream import ScreenShareClient

# Choose One
client1 = CameraClient('127.0.0.1', 9999)
client2 = VideoClient('127.0.0.1', 9999, 'video.mp4')
client3 = ScreenShareClient('127.0.0.1', 9999)

client1.start_stream()
client2.start_stream()
client3.start_stream()
## Usage






<!-- LICENSE -->
## License

See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [Lee Sheedy] lee.sheedy123@gmail.com

Project Link: [https://github.com/leesheedy/Vidstreamer](https://github.com/leesheedy/Vidstreamer)

<p align="right">(<a href="#top">back to top</a>)</p>


++++++
Under construction! Not ready for use yet! Currently experimenting and planning!

