<script lang="ts">
  import { LINKS } from "$lib/consts";
</script>

<nav id="nav">
  <div class="container-fluid p-0">
    <div class="d-flex justify-content-between align-items-center">
      <div class="logo"><a class="d-block" href="/">&nbsp;</a></div>
      <div class="navigation">
        <div class="d-flex align-items-center">
          <div class="d-none d-lg-flex">
            <a href="https://matters.town/" target="_blank">Matters.Town</a><a
              href="https://traveloggers.matters.town/"
              target="_blank">Traveloggers</a
            ><a href="https://thespace.game/" target="_blank">The Space</a><a
              href="https://logbook.matters.town/"
              target="_blank">Logbook</a
            ><a class="d-block" href="/blog">Blog</a><a
              class="btn social twitter"
              href="https://twitter.com/Mattersw3b"
              target="_blank"><i class="icon" /></a
            ><a
              class="btn social discord"
              href="https://discord.com/invite/matterslab"
              target="_blank"><i class="icon" /></a
            >
          </div>
          <a class="btn outline follow" href="/#follow_us"><span>JOIN US</span></a>
          <div class="mobile d-lg-none">
            <button class="btn menu" onclick="index.menu(true)"><i class="icon" /></button>
            <button class="btn close" onclick="index.menu(false)"><i class="icon" /></button>
          </div>
        </div>
      </div>
    </div>
  </div>
</nav>
<menu id="menu">
  <ul>
    <li><a class="d-block" href="https://matters.town/" target="_blank">Matters.Town</a></li>
    <li>
      <a class="d-block" href="https://traveloggers.matters.town/" target="_blank">Traveloggers</a>
    </li>
    <li><a class="d-block" href="https://thespace.game/" target="_blank">The Space</a></li>
    <li><a class="d-block" href="https://logbook.matters.town/" target="_blank">Logbook</a></li>
    <li><a class="d-block" href="/blog" on:click={() => index.menu(false)}>Blog</a></li>
  </ul>
</menu>

<style>
  @media (max-width: 768px) {
    nav .follow {
      font-size: 13px !important;
      padding: 10px 20px !important;
    }
  }
</style>
