# Three.js webGL Video

Deze video maakt  gebruikt van Three.js library. Zou je dit ook will gebruiken hoef je maar een paar stappen te doen.

Zorg dat je als deze scripts vanuit de three.js library ophaalt:

    <script src="../build/three.js"></script>

		<script src="js/shaders/ConvolutionShader.js"></script>
		<script src="js/shaders/CopyShader.js"></script>

		<script src="js/postprocessing/EffectComposer.js"></script>
		<script src="js/postprocessing/RenderPass.js"></script>
		<script src="js/postprocessing/MaskPass.js"></script>
		<script src="js/postprocessing/BloomPass.js"></script>
		<script src="js/postprocessing/ShaderPass.js"></script>


		<script src="js/Detector.js"></script>
    
Vervolgens zet je een video tag en zorg je ervoor dat je een texures map heb waar je jouw video in zet:

<video id="video" autoplay loop webkit-playsinline style="display:none">
			<source src="textures/M41_Linkerbaan.mp4">
		</video>
    
Daarna zet je de gegeven script in de webglvideo.html ook onderin in je eigen html. 
    
Klaar!

Wil je jouw video veranderen dan kan dat makkelijk gedaan worden in de texture map door de video gewoon te vervangen.
