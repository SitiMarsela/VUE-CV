<!-- <template>
  <div class="item">
    <i>
      <slot name="icon"></slot>
    </i>
    <div class="details">
      <h3>
        <slot name="heading"></slot>
      </h3>
      <slot></slot>
    </div>
  </div>
</template> -->

<!-- <style scoped>
.item {
  margin-top: 2rem;
  display: flex;
}

.details {
  flex: 1;
  margin-left: 1rem;
}

i {
  display: flex;
  place-items: center;
  place-content: center;
  width: 32px;
  height: 32px;

  color: var(--color-text);
}

h3 {
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}

@media (min-width: 1024px) {
  .item {
    margin-top: 0;
    padding: 0.4rem 0 1rem calc(var(--section-gap) / 2);
  }

  i {
    top: calc(50% - 25px);
    left: -26px;
    position: absolute;
    border: 1px solid var(--color-border);
    background: var(--color-background);
    border-radius: 8px;
    width: 50px;
    height: 50px;
  }

  .item:before {
    content: ' ';
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    bottom: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:after {
    content: ' ';
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    top: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:first-of-type:before {
    display: none;
  }

  .item:last-of-type:after {
    display: none;
  }
}
</style> -->



<template>
<div class="skill">
    <h1 class="dudung"> My Skills</h1>
    <h3>HTML</h3>
    <div class="progress">
    <div class="progress-bar progress-bar-striped" role="progressbar" aria-label="Default striped example" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
    </div>
    <br>
    <h3>CSS</h3>
    <div class="progress">
     <div class="progress-bar progress-bar-striped bg-success" role="progressbar" aria-label="Success striped example" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
    </div>
    <br>
    <h3>JavaScript</h3>
    <div class="progress">
     <div class="progress-bar progress-bar-striped bg-info" role="progressbar" aria-label="Success striped example" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
    </div>
    <br>
    <h3>MySQL</h3>
    <div class="progress">
     <div class="progress-bar progress-bar-striped bg-warning" role="progressbar" aria-label="Success striped example" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
    </div>
    </div>
</template>

<style scoped>
.dudung{
  text-align: center;
  color: rgb(255, 255, 255);
  margin-bottom: 2rem;
  font-size: 4rem;
}

@media (min-width: 1024px) {
  .skill {
    min-height: 22rem;
    margin-top: 2rem;
    margin-bottom: 2rem;
    margin-right: 25rem;
    
    /* display: flex; */
    /* align-items: center; */
  }
}

.sip{
  display: flex ;
}

h3{
  color: rgb(26, 59, 48);
}
</style>