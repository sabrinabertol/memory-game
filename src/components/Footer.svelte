<script lang="ts">
    import 'iconify-icon'
</script>

<footer>
    <a
    href="https://github.com/sabrinabertol"
    target="_blank"
    rel="noopener noreferrer"
  >
  <iconify-icon icon="simple-icons:github"></iconify-icon>
</a>
  <a
    href="https://www.linkedin.com/in/sabrinabertol/"
    target="_blank"
    rel="noopener noreferrer"
  >
  <iconify-icon icon="el:linkedin"></iconify-icon>
</a>
  <a
    href="https://www.buymeacoffee.com/sabrinabertol"
    target="_blank"
    rel="noopener noreferrer"
  >
  <iconify-icon icon="ep:coffee"></iconify-icon>
</a>
</footer>

<style>
  footer {
    position: fixed;
    left: 0;
    width: 100%;
    height: 50px;
    font-size: 1.5rem;
    margin: 10px 0;
    padding: 0 48px;
    display: flex;
    justify-content: flex-end;
    @media (max-width: 768px) {
        justify-content: center;
    }
  }

  footer a {
    margin: 0 12px;
    color:  var(--txt-3);
  }

  footer a:hover {
	opacity: 0.7;
  }
</style>