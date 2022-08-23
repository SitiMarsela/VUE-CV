<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
<div class="nv">
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h4>
      Software Engineering
    </h4>
    <p>Saya Siti Marsela, siswi SMK Taruna Bhakti Depok, dengan jurusan Rekayasa Perangkat Lunak . Yang berusaha mengasah keterampilan di bidang IT seperti Disain dan Pemrograman. Untuk meningkatkan kemampuan, saya terus menerus mengembangkan pengetahuan dan keterampilan untuk pengalaman kerja dan karir saya.</p>
  </div>

<div class="content">
<div class="huy">
<div class="role">
  <h2>Bidang</h2>
  <h5>FrontEnd</h5>
</div>
<div class="hp">
  <h2>Alamat</h2>
  <h5>Kp. Areman Rt09/Rw08</h5>
</div>
</div>

<div class="oiy">
<div class="email">
  <h2>No.HP</h2>
  <h5>089523029795</h5>
</div>

<div class="sela">
  <h2>Email</h2>
  <h5>sitimarsela939@gmail.com</h5>
</div>

</div>
</div>
</div>
  

</template>

<style scoped>

.email{
  margin-right: 60px;
}
.content{
  margin-top: 60px;
  padding-left: 2rem;
}
.oiy{
  display: flex;
}

.huy{
  
  display: flex;
  gap: 5rem;
  padding-bottom: 3rem;
 
}

h2{
  font-size: 1.7rem;
  color: rgb(53, 117, 177);
  margin-bottom: 1rem;

}

h5{
 color: rgb(110, 110, 110);
  font-size: 1rem;
}
h1 {
  font-weight: 500;
  font-size: 4rem;
  top: -10px;
  
}

h4 {
  font-size: 1.6rem;
  color: rgb(18, 60, 73);
}

.nv{
  display: flex;
  padding-top: 2rem;
}
p{
  color: rgb(110, 110, 110);
}

.greetings{
  width: 30rem;
  height: 25rem;
}
.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}

.green{
 color: rgb(53, 117, 177);
 padding-top: 2rem;
}
</style>
