#!/usr/bin/groovy

pipeline {
    agent any
    options {
        disableConcurrentBuilds()
    }
 /*   parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
  }*/
    stages {
        stage('Example') {
            steps {
                ping_test()
                
            }
        }
    }
}
 
}

def ping_test() {
    
   
                sh """  
doping () {
ping -c3 ftp.uadreams.com > /dev/null
}

dook () {
#what to do if ping ok?
echo "ping ok"
}

doerror () {
# what to do if ping failed?
echo "error"
}

doping && dook || doerror
# this is the end of script.
                """
               
       
}
