<template>
   <section id="navbar">
       <nav class="nav">
           <div class="nav__logo">
               <img class="nav__logo-img" src="../assets/unique-logo-v3.png" alt="">
           </div>
           <ul class="nav__list">
               <li class="nav__list-item">
                   <a href="#">Home</a>
               </li>
                <li class="nav__list-item">
                   <a href="#">About</a>
               </li>
               <li class="nav__list-item">
                   <a href="#">Menu</a>
               </li>
               <li class="nav__list-item">
                   <a href="#">Chefs</a>
               </li>
               <li class="nav__list-item">
                   <a href="#">Features</a>
               </li>             
               <li class="nav__list-item">
                   <a href="#">Contact Us</a>
               </li>
           </ul>
       </nav>
   </section>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
    #navbar{
        padding: 3% 7%;
    }
    .nav{
        width: 100%;
        display: flex;
        justify-content: space-between;
        padding: 0 7%;
        position: relative;

        &__logo img{
            width: 200px;
            height: 200px;
            position: absolute;
            top: -5rem;
            left: 5rem;
        }

        &__list{
            display: flex;
            align-items: center;
            list-style: none;
            font-family: 'Cabin', sans-serif;
         /*    font-family: 'Roboto Condensed', sans-serif; */

            &-item{
                font-size: 1.2rem;
                letter-spacing: .1rem;
               

                &:not(:last-child){
                    margin-right: 1.4rem;
                }
                
                & a{
                    text-decoration: none;
                    font-weight: 700;
                    color: rgb(63, 63, 63);

                    &:hover{
                        color: #fb6355;
                    }
                }
            }
        }
    }
</style>>


