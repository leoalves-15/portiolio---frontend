<template id="teste">
<div class="contain">
    <div class="wrap">
        <div class="fistColumn">
            <div class="moldura">
            <img id="fotoPerfil" src="../assets/perfil.jpg" alt="" srcset="">
            </div>
             <div id="fica" class="contact">
                <div>
                    <span id="nome">
                        leoalves.dev
                    </span>
                </div>
                <div class="btn">
                    <button>
                        Mensagem
                    </button>
                </div>
            </div>
        </div>
        <div class="secondColumn">
            <div id="some" class="contact">
            <div>
                <span id="nome">
                    leoalves.dev
                </span>
            </div>
            <div class="btn">
                <button>
                    Mensagem
                </button>
            </div>
            </div>
            <div class="datas">
               <span class="itemDatas"> 44 posts</span>
                <span class="itemDatas"> 1,004 followers</span>
               <span  class="itemDatas">  890 following</span>
            </div>
            <div class="bio">
                <span class="desc nome">Leo Alves</span>
                <span class="desc tipo">Personal Blog</span>
                <span class="desc">Dev full stack</span>
                <span class="desc">Técnico em T.I 💻-IFBA</span>
                <span class="desc">Lic. em Computação 🖥️- UFBA</span>
                <span class="desc">Consultoria e aulas particulares 👨‍🏫</span>
            </div>
        </div>
    </div>
</div>
</template>
<script>
export default {
  name: "Perfil",
};
</script>
<style src="./Perfil.scss" lang="scss" scoped />