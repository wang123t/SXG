<template>
  <div class="brand">
    <div class="py-container">
      <ul class="brand-list">
        <li class="brand-item">
          <img src="../assets/images/brand/brand01.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand02.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand03.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand04.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand05.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand06.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand07.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand08.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand09.png" />
        </li>
        <li class="brand-item">
          <img src="../assets/images/brand/brand10.png" />
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "",
};
</script>

<style scoped lang="less">
.brand {
  margin: 10px 0;

  .py-container {
    width: 1200px;
    margin: 0 auto;

    .brand-list {
      overflow: hidden;
      padding: 15px 0;
      background: #f7f7f7;
      line-height: 18px;

      .brand-item {
        width: 120px;
        float: left;
        height: 37px;

        img {
          border-left: 1px dotted #ccc;
          padding: 0 10px;
        }

        &:first-child {
          img {
            border-left: 0;
          }
        }
      }
    }
  }
}
</style>
