<template>
  <div>

      <v-row>
          <v-flex xs12 md4 v-for="member in team" :key="member.id">
              
        <v-card min-width="300px" class="ma-2" >
            <v-card-title>{{member.name}}</v-card-title>
            <v-card-text class="text-left">
                <strong>

                    Student ID : {{member.id}} <br>
                    E-mail :  <a :href="'mailto:'+member.email">{{member.email}}</a>
                </strong>
            </v-card-text>
        </v-card>
          </v-flex>
      </v-row>
  </div>
</template>

<script>
export default {
    data(){
        return{
            team:[
                {name:"Jeson Dijamco",id:"17967770",email:"mms8338@autuni.ac.nz"},
                {name:"Yousef Aldawoud",id:"18038023",email:"vxn1903@autuni.ac.nz"},
                {name:"Ahmed Aldawoud",id:"18038024",email:"cmj1230@autuni.ac.nz"},
            ]
        }
    },mounted(){
    }
}
</script>

<style>

</style>