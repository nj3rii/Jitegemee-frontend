<script setup>
import { ref } from "vue"

const courses =ref([
        {
        name:" Computer Science",
        school:"School of Computing and Engineering",
        description:"Best course For computer enthusiasts",
        intake:"July 2025"
    },
    
    {        name:" Medicine",
             school:"School of Medicine",
             description:"Best course for doctors",
             intake:"September 2025"
    },
    

   {
        name:" Communication",
        school:"School of Communication",
        description:"Best school forJournalists",
        intake:"June 2025"
    },
    
    {
        name:" Business Managment",
        school:"School of Business Managment",
        description:"Best school for Entreprenuers",
        intake:"May 2025"
    },

    {
        name:"Accounting",
        school:"School of Accounting ",
        description:"Best school for accountants",
        intake:"June 2025"
    },

        {
        name:"Law",
        school:"School of Law ",
        description:"Best school for lawyers",
        intake:"June 2025"
    },

        {
        name:"Human Resource Management",
        school:"School of Human Resource Mangement ",
        description:"Best school for Human Resource Managers",
        intake:"May 2025"
    },

        {
        name:"Data Analysis",
        school:"School of Data Analysis ",
        description:"Best school for Data Analysits",
        intake:"July 2025"
    },

        {
        name:"Animation Graphics",
        school:"School of Animation and Graphics",
        description:"Best school for Animators and graphic designers",
        intake:"September 2025"
    },
        {
        name:"Film Production",
        school:"School of Film Production ",
        description:"Best school for Film Producers",
        intake:"June 2025"
    }

])


    




</script>


<template>
    <v-container>
        <v-row>
            <v-col md="40" v-for ="course in courses">
                <v-card color="purple">
        
        <v-card-item>
          <v-card-title>{{course.name}}</v-card-title>

          <v-card-subtitle>{{course.school}}</v-card-subtitle>
        </v-card-item>

        <v-card-text>
            {{course.decription}}
          
        </v-card-text>
        </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>