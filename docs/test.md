<style>
    .scene-container { width: 100%; height: 400px; }
    i-scene { background: #333; touch-events: none; }
    i-dom-plane { overflow-y: auto; background: #4c86a8; pointer-events: none; }
</style>

<div class="scene-container">
  <i-scene id="scene" experimental-webgl>
    <i-ambient-light color="white" intensity="0"></i-ambient-light>
    <i-point-light id="light" color="white" intensity="0.8" size="0 0" align="0.5 0.5" position="0 0 300">
      <i-mesh size="10 10 10" align="0.5 0.5" mount-point="0.5 0.5" has="sphere-geometry basic-material" color="white"></i-mesh>
    </i-point-light>
    <i-dom-plane id="plane" size="400 200" align="0.5 0.5" mount-point="0.5 0.5" color="#444">

This is _Markdown_!

A sentence with _italic_ and **bold** and `code`.

</i-dom-plane>
</i-scene>
</div>

<script>
light.three.distance = 800
plane.three.material.opacity = 0
plane.three.material.transparent = true
plane.three.material.dithering = true
plane.rotation = (x, y, z, t) => [x, 30 * Math.sin(t * 0.001), z]
scene.addEventListener('pointermove', function(e) {
  e.preventDefault()
  light.align = [0, 0]
  light.position.x = e.offsetX
  light.position.y = e.offsetY
})
</script>
