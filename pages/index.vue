<template>
  <div class="container">
    <div class="img-side">
      <img 
      src="@/assets/img/rope-front.png"
      alt="four"
      class="img"
       />
      <img 
      src="@/assets/img/frist.jpeg"
      alt="four"
      class="img"
       />
    </div>
    <div class="w-1/2 form-side">
      <form>
        <div>
          <p class="title">Color Blind</p>
          <select class="cord-optoin">
            <option >White</option>
            <option >Gray</option>
          </select>
        </div>
        <div>
          <p style="margin-top:8px" class="title">Cord / tape</p>
          <select class="color-optoin">
            <option>Cord</option>
            <option>Tape White</option>
          </select>
        </div>
        <div>
          <p style="margin-top:8px" class="title">Tassel</p>
          <select class="tessal-optoin">
            <option>Tessal</option>
            <option>No Tessal</option>
          </select>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: `${process.env.HOME_PAGE} ends`,
      base: 'abc',
    };
  },
  head() {
    return {
      title: process.env.HOME_PAGE,
    };
  },
};
</script>

<style>
.container {
  width: 80%;
  display: flex;
  margin: 0 auto;
  background: white;
  margin-top: 1rem;
  padding: 25px 30px;
}
.img-side {
  width: 50%;
}
.form-side {
  width: auto;
  margin-left: 8.3333333%;
}
.form-side form {
  padding: 0 15px;
}
.cord-optoin {
  display: block;
  width: 418px;
  border: 1px solid black;
  border-radius: 4px;
  padding: 4.5px 9px;
  font-size: 18px;
  line-height: 28px;
}
.cord-optoin:focus {
  outline: none;
}
.color-optoin:focus {
  outline: none;
}
.tessal-optoin:focus {
  outline: none;
}
.title {
  margin-bottom: 1rem;
}
.color-optoin {
  display: block;
  width: 418px;
  border: 1px solid black;
  border-radius: 4px;
  padding: 4.5px 9px;
  font-size: 18px;
  line-height: 28px;
}
.tessal-optoin {
  display: block;
  width: 418px;
  border: 1px solid black;
  border-radius: 4px;
  padding: 4.5px 9px;
  font-size: 18px;
  line-height: 28px;
}
</style>
