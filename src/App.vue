<template>
  <div id="app">
    <button class="btn btn-info">btn-info</button>
    <button class="btn btn-warning">btn-warning</button>
    <button class="btn btn-danger">btn-danger</button>
    <button class="btn btn-success">btn-success</button>
    <nav aria-label="Page navigation">
      <ul class="pagination">
        <li>
          <a href="#" aria-label="Previous">
            <span aria-hidden="true">&laquo;</span>
          </a>
        </li>
        <li><a href="#">1</a></li>
        <li><a href="#">2</a></li>
        <li><a href="#">3</a></li>
        <li><a href="#">4</a></li>
        <li><a href="#">5</a></li>
        <li>
          <a href="#" aria-label="Next">
            <span aria-hidden="true">&raquo;</span>
          </a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
#app {
  text-align: center;
  margin: 60px;
}
</style>
