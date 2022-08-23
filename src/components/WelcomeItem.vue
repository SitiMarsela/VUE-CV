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
<div class="content">
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
    <br>
    <h3>Wordpress</h3>
    <div class="progress">
     <div class="progress-bar progress-bar-striped" role="progressbar" aria-label="Default striped example" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
    </div>
    <br>
    <h3>Laravel</h3>
    <div class="progress">
     <div class="progress-bar progress-bar-striped bg-success" role="progressbar" aria-label="Success striped example" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
    </div>
    </div>


    <div class="expe">
      <h1 class="lela">My experience</h1>
      <div class="fix">
        <ul>
          <li>Membuat Halam Website menggunakan css native</li>
          <li>Membuat Halam Website menggunakan Bootsrap</li>
          <li>Membuat desain UI mobile dan web di figma</li>
          <li>Membuat Halam Website menggunakan wordpress</li>
          <li>Membuat Halam Website menggunakan wordpress</li>
        </ul>
      </div>
    </div>
</div>

<footer>
  <div class="jy">
    <h5>Copyright ©2022 SitiMarsela</h5>
  </div>

  <div class="kl">
    <h5>CVSela</h5>
      <div class="jj">
        <a href="/profile">Profile</a>
        <a href="/skill">Skill</a>
      </div>
  </div>
  
</footer>
</template>

<style scoped>
.dudung{
  color: rgb(53, 117, 177);
  margin-bottom: 2rem;
  font-size: 4rem;
}

.lela{
  color: rgb(53, 117, 177);
  font-size: 4rem;
}

.fix{
  padding-top: 3.5rem;
}

.expe{
  padding-top: 2rem;
}

.content{
  display: flex;
  gap: 0rem;
}

@media (min-width: 1024px) {
  .skill {
    min-height: 22rem;
    margin-top: 2rem;
    padding-right: 5rem;
    margin-left: 2rem;
    padding-bottom: 4rem;
    
  }
}

/* .sip{
  display: flex ;
} */

.progress{
  width: 30rem;
}
h3{
  color: rgb(53, 117, 177);
}

li{
  list-style-type: initial;
  color: rgb(53, 117, 177);
  padding-bottom: 1.5rem;
  font-size: 20px;
}

h5{
  padding-left: 3rem;
  padding-bottom: 2rem;
  color: darkgrey;
  padding-right: 2rem;
}

a{
  color: dimgrey;
  padding-right: 2rem;
}

footer{
  display: flex;
}
.kl{
  display: flex;
}

.jy{
  padding-right: 35rem;
}
</style>