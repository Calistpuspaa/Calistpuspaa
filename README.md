
<html>

    <body>

        <h1>Hai gembel haha</h1>

        <img src="https://media3.giphy.com/media/3oKIPvxye1AAZXBk7m/giphy.webp?cid=6c09b952d3e9ornxy1a31piyxdie7z476nkmkyy8g9jybfx8&rid=giphy.webp&ct=gg">

        <h1>

            Kiw pcrn😍💘

            <button id='btn_music' onclick='music()'>Play/Pause</button>

        </h1>

        <button id='btn_mau' onclick='alert("I <3 U")'>Mau</button>&nbsp;

        <button id='btn_gamau' onclick='gamau(this)' style='position:absolute'>Gamau</button>

        <audio id='bgMusic' src='https://media1.vocaroo.com/mp3/1ka4ueCnCHXn' loop></audio>

    </body>

    <script>

        function gamau(id){

            var mau = document.getElementById('btn_mau');

            var i = Math.floor(Math.random()*300)+1;

            var j = Math.floor(Math.random()*100)+mau.offsetTop;

            id.style.left = i+'px';

            id.style.top = j+'px';

        }

        var audioPlaying = false;

        function music(){

            var audio = document.getElementById("bgMusic");

            if (!audioPlaying) audio.play();

            else audio.pause();

            audioPlaying = !audioPlaying;

        }

    </script>

</html>
