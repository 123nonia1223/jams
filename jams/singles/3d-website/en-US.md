<!DOCTYPE html>
<html>
  <head>
    <script src="https://aframe.io/releases/1.4.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-cylinder 
        position="0 2 -5" 
        radius="2" 
        height="0.3" 
        rotation="0 0 0" 
        color="#8A2BE2">
      </a-cylinder>
      
      <a-sphere 
        position="0 2.4 -5" 
        radius="0.8" 
        color="#ADD8E6" 
        opacity="0.8">
      </a-sphere>
      
      <a-ring 
        position="0 2 -5" 
        radius-inner="2.1" 
        radius-outer="2.3" 
        rotation="90 0 0" 
        color="#FFD700">
      </a-ring>
      
      <a-cone 
        position="0 1.2 -5" 
        radius-bottom="1.5" 
        radius-top="0.1" 
        height="2" 
        color="#FFFF00" 
        opacity="0.5">
      </a-cone>
      
      <a-plane position="0 0 -5" rotation="-90 0 0" width="20" height="20" color="#228B22"></a-plane>
      
      <a-camera position="0 1.6 0"></a-camera>
    </a-scene>
  </body>
</html>
