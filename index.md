<html>
    <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
    <script src="https://unpkg.com/aframe-look-at-component@0.8.0/dist/aframe-look-at-component.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar-nft.js"></script>

	<body>
	  <a-scene ar
		arjs="sourceType: webcam; debugUIEnabled: false;"
		>
		<a-box width="50" height="5.0" depth="1.0" position="-0.25 0.125 -0.75" rotation="0 45 0" color="#4CC6D9"
		gps-entity-place="latitude: 53.3; longitude: -1.3;"
		></a-box>
		<a-camera gps-camera rotation-reader> </a-camera>
	  </a-scene>
	</body>
</html>