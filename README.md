# day-3.1
<html>
  <head>
    <script src="https://aframe.io/releases/1.5.0/aframe.min.js"></script>
  </head>
  <body>
    <script>
      AFRAME.registerComponent('bye', {
        init: function () {
            console.log('Hello!');
        }
      });
    </script>
    <a-scene background="color: #ECECEC">
      <a-box position="-1 0.5 -3" hello rotation="0 45 0" color="#4CC3D9"
          animation="startEvents: click; property: position;
              from: -1 1.5 -3; to: -1 0.5 -3; dur: 1000">
           <script>
      AFRAME.registerComponent('helloo', {
        init: function () {
            console.log('Hello!');
        }
      });
    </script>
      </a-box>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>

      <a-entity cursor="rayOrigin:mouse"></a-entity>
    </a-scene>
  </body>
</html>
