<template>
  

    <div class="container">
         <div class="card-project"  v-for="repo in repos" :key="repo.id">
                 <h1> Titre de Projet:{{ repo.name }}</h1>
                 <p> <strong>URL:</strong>{{ repo.html_url}}</p>
                 <p> <strong>Made with:</strong>  {{ repo.language}}</p>
                <p> <strong>Author :</strong>  {{ repo.owner.login }}</p>
                <p> <strong>created at :</strong>    {{ repo.created_at}}</p>
                 <div class="links">
                       <a :href=" repo.html_url"><img src="../assets/5968866.png" alt=""></a>

                 </div>              

         </div>
    </div>

</template>

<script>
import axios from "axios"
export default {
  name: "ReposiTory",
  data() {
     return{
      repos: null,
     };
     },
     created: function(){
      axios.get('https://api.github.com/users/rague90/repos').then((response) =>{
        this.repos = response.data;
        console.log(this.repos);
      });
     
  }
};
</script>

<style>

/*:-moz-broken.table td,
.table th {
  padding: 20px !important;
}*/

.card-project{
  width: auto;
  height:auto;
  background-color: #fff;
  border-radius: 25px;
  margin-left: 20%;
  margin-right: 20%;

  margin-top: 5%;
  margin-bottom: 5%;
  flex-wrap: 0 0 40;
  box-shadow: rgba(0,0,0,0.24) 0px 3px 8px;

}
.card-project p {
 text-align: left;
 margin-left: 1%

};
.links
{
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-end;
}
.links img 
{
  margin: 5px;
}


</style>