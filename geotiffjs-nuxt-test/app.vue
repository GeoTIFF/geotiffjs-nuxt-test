<script>
import { fromUrl } from "geotiff";

const tif = await fromUrl("https://storage.googleapis.com/pdd-stac/disasters/hurricane-harvey/0831/20170831_172754_101c_3b_Visual.tif");
console.log("tif:", tif);

</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
