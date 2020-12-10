<template>
   <section id="hero">
       <div class="hero">
           <div class="hero__reservation">
               <div class="hero__reservation-content">
                   <h2>Unique Flavor</h2>
                   <p>Enjoy the experience</p>
                   <button>Make a Reservation</button>
               </div>
           </div>
           <div class="hero__image">

           </div>
       </div>
   </section>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
    #hero{
        padding:0 5%;
    }
    .hero{
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        width: 100%;
        height: 85vh;

        &__reservation{
            grid-column: 1/2;
            background-image: linear-gradient(to right, rgba(251, 99, 85,.7), rgba(245, 99, 85,.8)), url("https://images.unsplash.com/photo-1596787071320-c06155930dae?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=967&q=80");
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            width: 430px;

            &-content{

                & h2{
                    font-size: 2.8rem;
                    color: white;
                    font-family: 'Roboto Condensed', sans-serif;    
                    letter-spacing: .2rem;
                }

                & p{
                    text-transform: uppercase;
                    color: white;
                    font-family: 'Cabin', sans-serif;
                    letter-spacing: .1rem;
                    margin: .3rem 0 2rem 0;
                }

                & button{
                    border: none;
                    border: 1px solid  #ffffff;
                    background-color:  #ffffff;
                    padding: .7rem 1.4rem;
                    color: #fb6355;
                    font-family: 'Roboto Condensed', sans-serif; 
                    font-weight: 700;
                    border-radius: 3px;
                    font-size: 1.1rem;
                    cursor: pointer;
                    outline: none;

                    &:hover{
                        background-color: #d84e41;
                        color: #ffffff;
                        border: 1px solid  #d84e41;

                    }
                }
            }
        }   

        &__image{
            grid-column: 2/-1;
            background: url("https://images.unsplash.com/photo-1550966871-3ed3cdb5ed0c?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80");
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            
        }
    }
</style>
