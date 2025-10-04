--<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>AuroviaZ Luxury</title>
<meta name="description" content="Luxury 3D Website">
<script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
</head>
<body>
<a-scene>
<!-- Mansion Background -->
<a-sky color="#000000"></a-sky>

<!-- Luxury Logo -->
<a-text value="AUROVIAZ" color="gold" position="-1 2 -3" scale="2 2 2"></a-text>

<!-- Example Product (Mirror) -->
<a-box position="-1 1 -3" color="silver" depth="0.1" height="2" width="1.5"
shadow></a-box>
<a-text value="Luxury Mirror $199" color="white" position="-1 0 -3"></a-text>

<!-- Example Product (Chandelier) -->
<a-sphere position="2 3 -4" radius="0.5" color="gold"></a-sphere>
<a-text value="Golden Chandelier $499" color="white" position="2 2 -4"></a-text>

<!-- Camera Control (so people can move) -->
<a-entity position="0 1.6 0">
<a-camera wasd-controls look-controls></a-camera>
</a-entity>
</a-scene>
</body>
</html>-
