
<template>
  <header>

    <nav class="header-cont">

      <div>
        <img src="../assets/img/dc-logo.png" alt="logo">
      </div>

      <div>
        <ul>
          <li>
            <a href="#">CHARACTERS</a>
          </li>
          <li>
            <a href="#">COMICS</a>
          </li>
          <li>
            <a href="#">MOVIES</a>
          </li>
          <li>
            <a href="#">TV</a>
          </li>
          <li>
            <a href="#">GAMES</a>
          </li>
          <li>
            <a href="#">COLLECTIBLES</a>
          </li>
          <li>
            <a href="#">VIDEOS</a>
          </li>
          <li>
            <a href="#">FANS</a>
          </li>
          <li>
            <a href="#">NEWS</a>
          </li>
          <li>
            <a href="#">SHOP</a>
          </li>
        </ul>
      </div>

    </nav>

  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
}
</script>


<style scoped lang="scss">

  img{

    cursor: pointer;
    width: 100%;
  }

  nav{

    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;

    width: 70%;
    margin-inline: auto;
  
    ul{

      display: flex;

      li{

        list-style-type: none;
        padding-inline-start: 20px;
        color: black;

       

        a{

          color: inherit;
          text-decoration: none;

           &:hover{
        
            color: rgba(12, 124, 236, 1) ;
            box-shadow: 0px 4px 0px rgba(12, 124, 236, 1);
            padding-bottom: 56px; 
          
          }
        }
      }
    }
  }


</style>
