<template>
    <main id="intro">
        <div class="container">
            <h1>Vue.js 3</h1>
            <p>
                Vue.js (shuningdek, Vue ; /vjuː/) foydalanuvchi interfeyslarini yaratish uchun ochiq manba kodli
                JavaScript
                freymvorki. Loyihalarda boshqa JavaScript kutubxonalari bilan birga ishlatishda oson. Uning yordamida
                reaktiv uslubdagi bir sahifali dasturlar yaratish imkoni mavjud.
                Hozirda Netlify, Netguru, Baidu, Livestorm kabi turli kompaniyalarning asosiy a'zolari hamda freymvork
                tuzuvchisi Evan Yu tomonidan qo'llab-quvvatlanadi.
                2016-yilda JavaScript bo'yicha o'tkazilgan so'rovnomada Vue 89% dasturchilarda qoniqish hosil qilgan.
                GitHub-da ushbu loyiha 188K yulduzga ega va bu GitHub tarixidagi uchinchi yirik loyiha.
                2015-yil oktabr oyida kutubxonaning 1.0 versiyasi, 2016-yil sentabr oyida 2.0 versiyasi chiqdi.
                2.0 versiyasidan boshlab u server tomonida renderlashni ham qo'llab-quvvatlashni boshladi, ya'ni SSR
                (Server
                tomonida ko'rsatish).
            </p>
        </div>
    </main>
</template>

<style lang="scss" scoped>
main {
    background-image: url("https://wk-partners.co.jp/homepage/wp-content/uploads/2019/11/learnvuejs.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 1000px;

    h1 {
        color: white;
        font-size: 100px;
        line-height: 145px;
        width: 400px;
        float: right;
    }

    p {
        margin-top: 200px;
        width: 60%;
        float: left;
        color: aliceblue;
        line-height: 38px;
        font-size: 32px;
    }
}
</style>