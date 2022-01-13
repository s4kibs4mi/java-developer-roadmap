// This is a demo Jenkinsfile which will help you to build a pipeline whenever you will need project to build using jenkins.
// This file will let you go through a demo Jenkinsfile and the steps included in it.
// This pipeline will be a sample for any projects whenver you will deal with.

// In this pipeline i will be taking maven as the build tool and the steps i will include is 
// 1 - clean 
// 2 - build
// 3 - compile
// 4 - test
// 5 - deploy


pipeline{

    agent any    //This is the name of the machine you want to run the pipeline.

    tools{
        maven 'maven'   // It is the tool configuration which you declare in your jenkins tool <global tool configuration> needed in the project.

    }

    stages{

        stage('clean stage'){

            sh ' mvn clean'   // Defined in your pom.xml the first stage .It will let you cleanup the last build artifacts.

        }

        stage('compile stage'){

            sh 'mvn compile' // THis is the command to compile your project.You can change it according to your project .

        }

        stage('build stage'){

            sh 'mvn build'   // It shows the build stage where you build your project .Here you can use your own command which is used in the project.

        }

        stage('test stage'){

            sh 'mvn test' // It is the stage where you will test your command.This command will be according to your project.

        }

        stage('package stage'){

            sh 'mvn package'   // THis will packahe your project in a form of jar file.

        }
        stage('deploy stage'){

            sh 'cd target/'   // The jar file will be in the target folder.
            sh 'java -jar <jar-file-name>.war &'   // Then run the jar file in this.

        }



    }
    post{
                  // This block will always execute so put the code here like if you want to receive email on pipeline failure.You can get the code 
                  // from pipeline syntax generator in jenkins.
                  emailext body: '', subject: '', to: 'abc@gmail.com'   // It is just a demo.
    }
}