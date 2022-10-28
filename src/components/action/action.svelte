<script>
  import s from "./action.module.css";
</script>

<section class={s.action}>
  <div class={s.content}>
    <div class={s.left}>
      <div class={s.items}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src="./main-img.png" class={s.imageMain} alt="image" />
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src="./action-bg.png" class={s.imageLeft} alt="image" />
      </div>
      <div class={s.items}>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src="./img3.png" class={s.imageUnder} alt="image" />
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src="./actions.png" class={s.imageRacoon} alt="image" />
      </div>
    </div>
    <div class={s.right}>
      <h2 class={s.text}>
        Пусть ваш ребёнок познает мир, а о пятнах на его одежде позаботится
        Meine Liebe. Участвуйте в конкурсе и выигрывайте призы!
      </h2>
      <a href="#" class={s.button}>Участвовать</a>
      <!--<div class={s.background} />-->
    </div>
  </div>
</section>

<style>
</style>
