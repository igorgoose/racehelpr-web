<script>
</script>

<div class="main-container">
  <div id="current-times" class="data-container">
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
  </div>
  <div id="personal-best-times" class="data-container">
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
  </div>
  <div id="run-best-times" class="data-container">
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
    <div class="data-cell">10.0</div>
  </div>
  <div id="fastest-driver-tracker" class="data-container">
    <div class="data-cell">S1</div>
    <div class="data-cell here">S2</div>
    <div class="data-cell">S3</div>
  </div>
</div>

<style>
  .main-container {
    min-height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .data-container {
    flex: 1;
    display: flex;
    align-items: stretch;
    justify-content: center;
    width: 100%;
  }

  .data-container > * {
    display: flex;
    justify-content: center;
    align-items: center;
    flex: 1;
  }

  #fastest-driver-tracker {
    flex: 0.1;
    background: gainsboro;
  }

  .here {
    background: rgb(5, 219, 94);
  }
</style>
