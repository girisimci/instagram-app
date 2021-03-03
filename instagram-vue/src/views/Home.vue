<template>
  <div class="home">
   <CustomText>Selam</CustomText>
   <CustomText class="a1" tag="p">Selam</CustomText>
   <CustomText tag="p" size="small">Selam</CustomText>
   <CustomText tag="p" size="xsmall">Selam</CustomText>
   <CustomText tag="p" size="xxsmall">Selam</CustomText>
   <IconHome/>
  </div>
</template>

<script>
// @ is an alias to /src
import CustomText from '@/components/CustomText';
import IconHome from '../icons/home.svg';

export default {
  name: "Home",
  components:{
    CustomText,
    IconHome
  }
};
</script>

<style>
.a1{
  color: rgb(var(--ba8));
}
</style>