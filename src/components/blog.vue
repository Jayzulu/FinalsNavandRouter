<template>
    <div class="blog">
      <h1>Welcome to my Blog Page</h1>
      <img id = "game" src = "https://media.istockphoto.com/id/1324673294/photo/video-gaming-console-man-playing-rpg-strategy-game.jpg?b=1&s=170667a&w=0&k=20&c=zV98YgsKQGfquln1lX6D-TaLH1EYlM-DMA1PwQvLwiY=">
      <h2> Games </h2>
      <h3> What are Video Games?Lets describe it together video games are games that are played electronically using a computer or gaming console. These games allow players to interact with a virtual world and complete various challenges. They can be simple or complex, ranging from arcade-style games to elaborate role-playing games. Players can enjoy video games alone, with friends online, or in-person through multiplayer modes. Video games have become a popular form of entertainment that is enjoyed by people of all ages and backgrounds. However, playing video games excessively can result in addiction and negative effects on mental and physical health, so it's important to play in moderation and establish good gaming habits.
        </h3>
    </div>
  
  
  </template>
  
  <script>
  export default {
    name: 'blog',
    data () {
      return {
        title: 'Blog'
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  #game{
    width: 950px;
  }

  h1,h2,h3{
    color: black;
    font-weight: bold;
    background-color: aquamarine;
    
    

  }
 


  </style>
  