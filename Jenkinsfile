pipeline{
     agent any
     stages{

        stage("compile"){
            
            sh 'javac test.java'
        }

        stage("run"){

            sh 'test.java'
        }
     }

}