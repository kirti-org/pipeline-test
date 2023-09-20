pipeline       //it starts with pipeline keyword

{
agent any       //any: run stages on any available agent
stages          //it contains stages

{
 stage ('print something')                //stage name
 { steps { sh 'echo Hello_Jenkins' } }    // it tell jenkins

 stage ('build the code')
 { steps { sh 'echo code-is-building' } }

 stage ('deploy the code')
 { steps { sh 'echo deploying the app code' } }


 
}
}
