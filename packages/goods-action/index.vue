<template>
  <div class="van-goods-action">
    <slot />
  </div>
</template>

<script>
import { create } from '../utils';

export default create({
  name: 'van-goods-action'
});
</script>
