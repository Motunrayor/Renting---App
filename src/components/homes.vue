<template>
    <div id="homes">
        <p>Homes</p>
    </div>

</template>

 <script>
 export default {
   name: 'homes',
 }
 </script>

<style scoped>
#homes{
    width: 100vw;
    height: 68px;
    left: 10px;
    margin-top: 102px;
    background: #ffffff;
    border: 1px solid #C4C4C4;
    box-sizing: border-box;
}
p{
    width: 89px;
    height: 36px;
    margin-left: 676px;
    top: 22px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 28px;
    color: #000000;
}
@media screen and (max-width: 768px){
  #homes{
    width: 100vw;
    height: 68px;
    left: 0px;
    margin-top: 102px;
    background: #ffffff;
    border: 1px solid #C4C4C4;
    box-sizing: border-box;
}
p{
    width: 89px;
    height: 36px;
    margin-left: 300px;
    top: 22px;
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 28px;
    color: #000000;
}
}
</style>
