<template>
  <div>
    <div class="percentage-bar" id="pb">
      <div class="fill"></div>
      <p>{{ percentage }}%</p>
    </div>
    <article @scroll="onScroll">
      <h1>
        {{ title }}
      </h1>
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed unde odio
        fuga laborum officiis, eos accusantium aliquam ad sapiente cupiditate
        veniam perspiciatis pariatur magnam in placeat excepturi vero commodi
        autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit. <br /><br />Lorem ipsum dolor, sit amet
        consectetur adipisicing elit. Sed unde odio fuga laborum officiis, eos
        accusantium aliquam ad sapiente cupiditate veniam perspiciatis pariatur
        magnam in placeat excepturi vero commodi autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit. <br /><br />Lorem ipsum dolor, sit amet
        consectetur adipisicing elit. Sed unde odio fuga laborum officiis, eos
        accusantium aliquam ad sapiente cupiditate veniam perspiciatis pariatur
        magnam in placeat excepturi vero commodi autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit. <br /><br />Lorem ipsum dolor, sit amet
        consectetur adipisicing elit. Sed unde odio fuga laborum officiis, eos
        accusantium aliquam ad sapiente cupiditate veniam perspiciatis pariatur
        magnam in placeat excepturi vero commodi autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit. <br /><br />Lorem ipsum dolor, sit amet
        consectetur adipisicing elit. Sed unde odio fuga laborum officiis, eos
        accusantium aliquam ad sapiente cupiditate veniam perspiciatis pariatur
        magnam in placeat excepturi vero commodi autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit. <br /><br />Lorem ipsum dolor, sit amet
        consectetur adipisicing elit. Sed unde odio fuga laborum officiis, eos
        accusantium aliquam ad sapiente cupiditate veniam perspiciatis pariatur
        magnam in placeat excepturi vero commodi autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit.<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit. <br /><br />Lorem ipsum dolor, sit amet
        consectetur adipisicing elit. Sed unde odio fuga laborum officiis, eos
        accusantium aliquam ad sapiente cupiditate veniam perspiciatis pariatur
        magnam in placeat excepturi vero commodi autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit.<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit. <br /><br />Lorem ipsum dolor, sit amet
        consectetur adipisicing elit. Sed unde odio fuga laborum officiis, eos
        accusantium aliquam ad sapiente cupiditate veniam perspiciatis pariatur
        magnam in placeat excepturi vero commodi autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit.<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit. <br /><br />Lorem ipsum dolor, sit amet
        consectetur adipisicing elit. Sed unde odio fuga laborum officiis, eos
        accusantium aliquam ad sapiente cupiditate veniam perspiciatis pariatur
        magnam in placeat excepturi vero commodi autem?<br /><br />
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corporis
        voluptate vitae sequi illum, vel mollitia inventore fuga hic,
        exercitationem eveniet ab, in ullam repudiandae dicta. Porro voluptas
        incidunt fugiat in?<br /><br />
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        incidunt rerum saepe nulla, vel totam ut accusamus minima pariatur
        cupiditate quis sit quae consequuntur explicabo recusandae sapiente
        possimus, tenetur reprehenderit.
      </p>
    </article>
  </div>
</template>

<script>
export default {
  name: "Post",
  props: {
    title: String
  },
  data: () => ({
    percentage: 0
  }),
  methods: {
    onScroll(evt) {
      const post = evt.target;
      const st = post.scrollTop;
      const sh = post.scrollHeight;
      const ch = post.clientHeight;

      const percent = Math.ceil((st / (sh - ch)) * 100);
      this.percentage = percent;

      const pb = post.parentNode.firstChild;
      for (let i = 0; i < pb.children.length; i++) {
        let fillBar = pb.children[i];
        if (fillBar.classList.contains("fill")) {
          fillBar.style.width = this.percentage + "%";
        }
      }
    }
  }
};
</script>

<style lang="scss" scoped>
article {
  width: 100%;
  max-width: 500px;
  height: 100%;
  max-height: 300px;
  overflow-y: scroll;
  margin: 0 auto;
  padding: 15px;
  background-color: #ffffff;
  position: relative;
}
.percentage-bar {
  position: relative;
  width: 100%;
  max-width: 530px;
  height: 25px;
  margin: 0 auto;
  background: #171717;
  .fill {
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    bottom: 0;
    background-color: #ffce00;
    // z-index: 0;
  }
  p {
    position: absolute;
    width: 100%;
    font-size: 18px;
    line-height: 25px;
    text-align: center;
    color: #f3f3f3;
    margin: 0;
    // z-index: 1;
  }
}
</style>
