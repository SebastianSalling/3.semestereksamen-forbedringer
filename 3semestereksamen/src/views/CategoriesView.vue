<script setup>
import Navbar from '@/components/Navbar.vue';
import FooterBottom from '@/components/FooterBottom.vue';
</script>

<template>
    <Navbar/>
    <div class="hero krusogkopper-hero">
    <h1 class="hero-text">Krus og kopper</h1>
  </div>
<div class="section-wrapper">
    <h2 class="heading">SE VORES UDVALG AF KRUS OG KOPPER</h2>
    <p class="paragraf">Tag et kig på vores krus og kopper. Alle produkterne er unikke, da de er lavet i hånden, og der vil derfor være 
        variation i hvert enkelt kunsthåndværk. Det er ikke alle varer, der er præsenteret her, så kom også ned i butikken og gå på opdagelse.</p>
<div class="kategoriprodukter">
    <router-link to="/specifikprodukt">
    <div class="kategoriproduktright">
        <div class="kategoriprodukt-beskrivelse">
            <div class="tekst">
                <h2>FLERFARVET KRUS</h2>
                <p>Lavet af<b> Clip Klap</b>. Dette krus er lavet af stentøj. Kan fås i flere farver.</p>
                <p>275 kr</p>
            </div>
        </div>
        <div class="kategoriprodukt-billede">
            <img src="../assets\images\produkter\kopper\krus-stor-lyseblå-claire-maria-lehmann-og-iben-harboe.webp" alt="">
        </div>
    </div>
    </router-link>
    <div class="kategoriproduktleft">
        <div class="kategoriprodukt-beskrivelse">
            <div class="tekst">
                <h2>ESPRESSOKOP I SORT</h2>
                <p>Lavet af<b> Mia Maya</b>. Denne kop er lavet i indfarvet stentøj. Tåler opvaskemaskine og mikrobølgeovn.</p>
                <p>185 kr</p>
            </div>
        </div>
        <div class="kategoriprodukt-billede">
            <img src="../assets\images\produkter\kopper\espresso-kop-sort-mia-maya.webp" alt="">
        </div>
    </div>
    <div class="kategoriproduktright">
        <div class="kategoriprodukt-beskrivelse">
            <div class="tekst">
                <h2>GRÅ BUNDRILLET KOP</h2>
                <p>Lavet af<b> Christina Friis</b>. Denne serie af kopper er lavet på drejebænken. Kan fås i flere farver.</p>
                <p>300 kr</p>
            </div>
        </div>
        <div class="kategoriprodukt-billede">
            <img src="../assets\images\produkter\kopper\kop-med-hank-og-riller-grå-christina-friis.webp" alt="">
        </div>
    </div>
</div>

</div>
    <FooterBottom/>
</template>

<style>
</style>