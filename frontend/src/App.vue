<template>
  <router-view />
</template>

<style lang="scss">
@import url('~normalize.css/normalize.css');

* {
  outline: none;
}

::selection {
  background: #d3d3d3;
}

::-webkit-scrollbar {
  width: 7px;
  height: 7px;
}

::-webkit-scrollbar-track {
  border-radius: 3px;
  background: rgba(255, 255, 255, 0.08);
  box-shadow: inset 0 0 5px rgba(255, 255, 255, 0.1);
}

::-webkit-scrollbar-thumb {
  border-radius: 3px;
  background: rgba(255, 255, 255, 0.09);
  box-shadow: inset 0 0 6px rgba(255, 255, 255, 0.1);
}

::-webkit-scrollbar-thumb:hover {
  background: rgba(255, 255, 255, 0.15);
}

@media screen {
  body {
    background: #282a2b;
  }
}

@media print {
  .no-print {
    display: none;
  }
}
</style>
