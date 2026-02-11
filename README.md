# McNepoMc.github.io
<button class="no" onmouseover="moveButton()">Nein 😏</button>

<script>
function moveButton() {
  const btn = document.querySelector('.no');
  btn.style.position = 'absolute';
  btn.style.left = Math.random() * 80 + '%';
  btn.style.top = Math.random() * 80 + '%';
}
</script>
