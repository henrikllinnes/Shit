<html>
    <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
    <script src="https://unpkg.com/aframe-look-at-component@0.8.0/dist/aframe-look-at-component.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar-nft.js"></script>

	<body>
	  <a-scene ar>
		<a-box width="0.25" height="0.25" depth="0.25" position="-0.25 0.125 -0.75" rotation="0 45 0" color="#4CC3D9"
		gps-entity-place="latitude: 53.33954743099157; longitude: -1.3337337970733645;"
		></a-box>
		<a-camera gps-camera rotation-reader> </a-camera>
	  </a-scene>
	</body>
</html>