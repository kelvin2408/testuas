<template>
    <div class="container-fluid">
        <div class="row row-about p-5">
            <div class="col-md-6 p-4">
                <img src="../assets/foto.jpg" width="290px" height="320px"/>
            </div>
            <div class="col-md-6 p-4">
                <h1 class="mb-5">About Me<span class="text-danger">.</span></h1>
                <p class="text-justify">
                    Halo nama saya Kelvin Irawan merupakan CEO dari Sego Tinem
                    apabila kalian pengunjung website ini memilki masalah dibidang masakan
                    disini kami menawarkan cara yang mudah untuk medapatkanya
                    silahkan hubungi di contact person
                </p>
                <div class="chip">
                   <img src="../assets/wa.png" alt="Person" width="96" height="96"> 08123456778 </div>
            </div>
            {{msg}}
        </div>
    </div>
</template>

<script>
export default {
  props: {
    msg: { String }
  }
}
</script>

<style>
.chip {
  display: inline-block;
  padding: 0 25px;
  height: 50px;
  font-size: 16px;
  line-height: 50px;
  border-radius: 25px;
  background-color: #f1f1f1;
}

.chip img {
  float: left;
  margin: 0 10px 0 -25px;
  height: 50px;
  width: 50px;
  border-radius: 50%;
}
</style>
